# Project 5: Secure Linux Server Permissions

## Objective
To implement user-based access control in Linux by creating users and groups and restricting access to files and directories using Linux permissions.

## Implementation
1. Created two Linux users: project5_admin and project5_user.
2. Created two groups: project5_admins and project5_users.
3. Added each user to the corresponding group.
4. Created the secure directory /project5/secure.
5. Set directory ownership to root:project5_admins and permissions to 770.
6. Created test files and set their permissions to 660.

## Testing and Results
- Admin user successfully read the protected file.
- Normal user was denied access to the secure directory.
- Normal user could not read the admin file.
- Normal user could not create a file inside the secure directory.

## Conclusion
The project demonstrates Linux user and group management and permission-based access control. Authorised admin-group members can access protected resources, while unauthorised users are restricted.
