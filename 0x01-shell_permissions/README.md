# Shell Permissions
This repository contains shell scripts for practicing Linux permissions. Each task represents a different permission concept and is solved using a shell script.

## Scripts

- `0-iam_betty`: Changes your user ID to betty. You should use exactly 8 characters for your command (+1 character for the new line).
- `1-who_am_i`: Prints the effective userid of the current user.
- `2-groups`: Prints all the groups the current user is part of.
- `3-new_owner`: Changes the owner of the file hello to the user betty.
- `4-empty`: Creates an empty file called hello.
- `5-execute`: Adds execute permission to the owner of the file hello.
- `6-multiple_permissions`: Adds execute permission to the owner and the group owner, and read permission to other users, to the file hello.
- `7-everybody`: Adds execution permission to the owner, the group owner and the other users, to the file hello
- `8-James_Bond`: Sets the permission to the file hello as follows: No permission at all for owner and group, and all the permissions to other users.
- `9-John_Doe`: Sets the mode of the file hello to -rwxr-x-wx.
- `10-mirror_permissions`: Sets the mode of the file hello the same as olleh's mode.
- `11-directories_permissions`: Adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users. Regular files should not be changed.
- `12-directory_permissions`: Creates a directory called dir_holberton with permissions 751 in the working directory.
- `13-change_group`: Changes the group owner to holberton for the file hello.

## Usage

Each script can be run in a Linux shell. Note that some scripts might require superuser permissions to execute correctly.

For example, to run `0-iam_betty`, use:

```bash
./0-iam_betty
```

Note: Always ensure that your scripts are executable before attempting to run them. You can do this by using the `chmod` command:

```bash
chmod +x script_name
```

## License

This project is licensed under the MIT License.
