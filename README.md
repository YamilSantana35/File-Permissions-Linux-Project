# File-Permissions-Linux-Project

This project reinforces critical concepts for securing Linux file systems:

ls -la is your go-to tool for auditing file and directory permissions.

Permission strings tell you exactly who can do what with a file or directory.

chmod is a powerful tool to enforce least-privilege.

Always double-check changes to ensure security policy compliance.

Security Principles Practiced

Least Privilege: Limit access rights for users to the bare minimum.

Defense in Depth: Secure sensitive directories and hidden files.

Audit & Monitor: Continuously assess permissions to avoid unauthorized exposure.

Resources

man chmod

man ls

Linux File Permissions Tutorial

Lessons Learned

A small change in permissions can lead to a major security breach if not controlled.

Proper use of chmod and understanding symbolic vs numeric modes (e.g., chmod 700 vs chmod u+rwx) is essential.

Hidden files are often overlooked and require explicit permission management.

