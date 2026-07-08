# Bandit Wargames
The Bandit wargame is aimed at absolute beginners. It teaches the basics needed to be able to play other wargames.


# Level 0
---

The goal of this level is to log into the game using SSH. The host to which you need to connect is `bandit.labs.overthewire.org`, on port `2220`. The username is `bandit0` and the password is `bandit0`. 

SSH (Secure Shell), is a cryptographic network protocol that allows you to securely connect to and manage a remote computer or server over an unsecured network like the internet.

For this challenge, we have been provided with the following:
- a hostname
- a username, 
- a password and,
- a port number

```
$ ssh username@hostname -p portNumber
```

%% clear what is below %%
```
$ ssh bandit0@bandit.labs.overthewire.org -p 2220
```

After successfully running the command, you will be prompted for a password. Which was given in `Bandit Level 0` page.

# Level 1
___

Progressing into the next level, `Bandit Level 1` , requires you to view the contents of a file named `readme` . This file is in the home directory of `Bandit Level 0` and the password for progressing into `Bandit Level 1` is stored inside.

%% ### Goal:
The password for the next level is stored in a file called readme located in the home directory. Use this password to log into bandit1 using SSH. Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game %%

We are given some commands that might help us solve the challenge:

| cat | file | cd  | du  | ls  |
| --- | ---- | --- | --- | --- |
%% solution tips %%

After getting the password in `Bandit Level 0` to progress into `Bandit Level 1`. Log out from the current ssh session and use the password to log in as `bandit1` to hostname `bandit.labs.overthewire.org` to enter `Bandit Level 1`.

```
ssh bandit1@bandit.labs.overthewire.org -p 2220
```

_You are now a Level 1 Bandit_

# Level 2
___

m