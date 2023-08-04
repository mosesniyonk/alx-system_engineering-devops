# 0-iam_betty

This script allows you to switch the current user to the user "betty" using the `su` command.

## Usage
```bash
./0-iam_betty


# 1-who_am_i

This script prints the effective username of the current user using the `whoami` command.

## Usage
```bash
./1-who_am_i


# 2-groups

This script prints all the groups the current user is part of using the `groups` command.

## Usage
```bash
./2-groups

# 3-new_owner

This script changes the owner of the file "hello" to the user "betty" using the `chown` command.

## Usage
```bash
sudo ./3-new_owner

# 4-empty

This script creates an empty file called "hello" using the `touch` command.

## Usage
```bash
./4-empty

# 5-execute

This script adds execute permission to the owner of the file "hello" using the `chmod` command.

## Usage
```bash
./5-execute

# 6-multiple_permissions

This script adds execute permission to the owner and the group owner, and read permission to other users, for the file "hello" using the `chmod` command.

## Usage
```bash
./6-multiple_permissions


# 7-everybody

This script adds execution permission to the owner, the group owner, and other users, for the file "hello" using the `chmod` command.

## Usage
```bash
./7-everybody


# 8-James_Bond

This script sets the permission of the file "hello" as follows:
- Owner: no permission at all
- Group: no permission at all
- Other users: all the permissions

## Usage
```bash
./8-James_Bond


# 9-John_Doe

This script sets the mode of the file "hello" to:
- Owner: read, write, and execute
- Group: read and execute
- Other users: execute

## Usage
```bash
./9-John_Doe


# 10-mirror_permissions

This script sets the mode of the file "hello" to the same as the mode of "olleh."

## Usage
```bash
./10-mirror_permissions


# 11-directories_permissions

This script adds execute permission to all subdirectories of the current directory for the owner, the group owner, and all other users.

## Usage
```bash
./11-directories_permissions


# 12-directory_permissions

This script creates a directory called "my_dir" with permissions 751 in the working directory.

## Usage
```bash
./12-directory_permissions


# 13-change_group

This script changes the group owner of the file "hello" to the group "school" using the `chgrp` command.

## Usage
```bash
sudo ./13-change_group

