### EX NO 4

### AIM:

The aim is to create a collaborative directory /common/admin with specific characteristics regarding group ownership, permissions, and default group ownership for files created within it.

### PROCEDURE:

1.Create the Directory

2.Set Group Ownership to 'admin'.

3.Set Permissions for the Directory

4.Set the SetGID Bit.

### PRAOGRAM / COMMANDS:
```
Developed by: Samyuktha S
Register Number: 212222240089
```
```
sudo mkdir -p /common/admin
sudo chown :admin /common/admin
sudo chmod 770 /common/admin
sudo chmod g+s /common/admin
```

### OUTPUT:
![image](https://github.com/SamyukthaSreenivasan/Collaborative-library/assets/119475703/a1a01d2d-caf2-4fd3-96c7-cfd998eb9041)

### RESULT:

Thus the prograom to create a Collaborative library is been successfully implemented.
