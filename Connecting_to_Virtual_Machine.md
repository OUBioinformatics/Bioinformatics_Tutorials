## Connecting to virtual machine

*Before you can log on, Boris needs your OU 4x4 so he can add you as a user.
*If you are on a Windows machine, you will need to use Bash or Xterm (http://mobaxterm.mobatek.net/), not the Windows Command Prompt

1. Connect using your OU 4x4

   ```
  ssh smit1234@mbio5810.oscer.ou.edu
  ```
1. You will be asked for your password.  This is the same password you use to log into your other OU accounts.
If you enter your password correctly, you may get the following message:

  ```
  Could not chdir to home directory/home/smit1234: No such file or directory
  ```
  However, if you were able to log in, you should have your own directory in the "users" directory
  
  ```
  ls users
  ```
1. Make a personal data directory

  ```
  cd users/smit1234
  mkdir data
  ```
