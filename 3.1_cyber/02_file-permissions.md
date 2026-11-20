# Understanding File Permissions

## Task 1 --- Create a File

Run:

    touch secret.txt
    ls -l secret.txt

### Screenshot

<img width="1126" height="2000" alt="image" src="https://github.com/user-attachments/assets/b5a68c6c-715c-4eb5-95d2-ec353dedf6a9" />


### Questions

1.  Who owns the file?
2.  What are the default permissions?

### Reflection

Why is file ownership important in Linux systems?

------------------------------------------------------------------------

## Task 2 --- Restrict File Permissions

Run:

    chmod 600 secret.txt
    ls -l secret.txt

### Screenshot

<img width="1920" height="321" alt="image" src="https://github.com/user-attachments/assets/b493c691-fb9c-4c8d-8e49-00172d9435f8" />


### Questions

1.  Who can read the file now?
2.  Who cannot access it?


------------------------------------------------------------------------

## Task 3 --- Open Permissions (Security Risk)

Run:

    chmod 777 secret.txt
    ls -l secret.txt

### Screenshot
<img width="1920" height="322" alt="image" src="https://github.com/user-attachments/assets/90c3d1ea-c843-4b43-ba6b-c708eb098eb4" />

### Questions

1.  Who can access the file now?
2.  Why might this configuration be dangerous?

