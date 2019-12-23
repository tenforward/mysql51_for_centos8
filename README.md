# Patches for building mysql 5.1 on CentOS8

"0001-change-library-directory-from-lib-to-lib64.patch" is required if openssl is not installed under /usr. Otherwise, it's not required.

In addition to these patches, bison 2.7 is required to build MySQL 5.1.
