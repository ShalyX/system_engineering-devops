In Linux, multiple users can share the same system. Each user has their own home directory, permissions, and environment. Being able to switch between users is a fundamental skill for system administrators and for managing different user accounts on a single machine. This task introduces you to the command used for changing your current user identity.

The objective of this task is to ensure you know the concise command for switching your current user to another existing user.

Task: Create a script that switches the current user to the user named betty.

Requirements:

Your command for switching the user should be exactly 8 characters long new line). This challenges you to find the most direct and efficient command.
You can assume that the user betty will exist on the system when your script is executed.
Here is an example illustrating a check on the length of your command (the checker will verify the functionality):

julien@ubuntu:/tmp/h$ tail -1 0-iam_betty | wc -c
9
julien@ubuntu:/tmp/h$
