# Practice 2

## 1. Create a playbook

- Creates a directory named /home/student/backup.
- Finds all files in /var/log that are older than 7 days.
- Copies those files to /home/student/backup.
- Removes the original files from /var/log.

## 2. Modify the web application deployment playbook

- Use the template module to generate the config.ini file from a Jinja2 template. The template should include variables for the database host, username, and password.
- Add a task to create a log rotation configuration file in /etc/logrotate.d/ for the application logs.
