# Detecting Suspicious Activity

## Objective

Learn about **detective security controls**.

---

## Step 1 – View authentication logs

```bash
sudo cat /var/log/auth.log
```

## Step 2 – Search for login attempts
```bash
grep "Failed password" /var/log/auth.log
```

## Step 3 – View recent logins
```bash
last
```

## Questions
- What information appears in authentication logs?
- Why are logs important in cybersecurity?
- What might indicate suspicious activity?


## Deliverables
Include screenshots of:
- authentication logs
- failed login search results
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/09aec18f-20df-4fb9-ac2c-66dc2783010d" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/aeae996f-cc8d-4ca9-a29e-19108e8f4d76" />

