# Practice 1

## 1. Create a playbook to install the nginx web server on all hosts in your inventory. 

The playbook should:
- Update the package cache.
- Install the nginx package.
- Ensure the nginx service is running.

## 2. Create a playbook to create a new user account on all hosts in the webservers group

The playbook should:
- Create a user named deploy.
- Set the user's password to a secure value (you can use a placeholder for now; we'll cover password management in a later module).
- Add the user to the sudo group.

## 3. Modify the playbook from exercise 2 to handle errors gracefully

If the user account already exists, the playbook should not fail. Instead, it should print a message indicating that the user account already exists. Use register and failed_when to implement this.

## 4. Create a playbook that copies a file from your Ansible control node to all hosts in your inventory

The playbook should:
- Copy the file /tmp/my_file.txt to /tmp/my_file.txt on the remote hosts.
- Set the owner and group of the file to root.
- Set the permissions of the file to 0644.
