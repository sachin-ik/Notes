# Notes
Environment variables in Linux system:
1. Can be defined system-wide in /etc/profile.
2. Can be defined per user in ~/.profile
3. Variables that are not specific to command line interpreters are better put in 
/etc/environment, since those variables will be injected into all user sessions thanks to a Pluggable Authentication Module(PAM)-even when no shell is executed.

