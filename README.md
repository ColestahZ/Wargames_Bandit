# Wargames_Bandit
http://overthewire.org/wargames/bandit/

## WarGames: Bandit ##

###Bandit - Level 0###

The goal of this level is for you to log into the game using SSH. The host to which you need to connect is **bandit.labs.overthewire.org**. The username is **bandit0** and the password is **bandit0**. Once logged in, go to the Level 1.

    Username: bandit0
    Password: bandit0

###Bandit - Level 1###

The password for the next level is stored in a file called **readme** located in the home directory. Use this password to log into **bandit1** using SSH. Whenever you find a password for a level, use SSH to log into that level and continue the game.

    Username: bandit1
    Password: boJ9jbbUNNfktd78OOpsqOltutMc3MY1

###Bandit - Level 2###

The password for the next level is stored in a file called **“-“** located in the home directory. Since dash is a special character in bash use **“cat ./-“**

When cat sees the string **-** as a **filename**, it treats it as a synonym for **stdin**. To get around this, you need to alter the string that cat sees in such a way that it still refers to a file called **-**. The usual way of doing this is to prefix the **filename** with a path **./-** or **/home/Tim/-**.

    Username: bandit2
    Password: CV1DtqXWVFXTvM2F0k09SHz0YwRINYA9

###Bandit - Level 3###

The password for the next level is stored in a file called spaces in this **filename** located in the home directory.

In a shell/command line context, wrap the **filename** in single or double quotes (but note they are not the same WRT other issues), or escape the spaces with \. 


> e.g:	foo my\ file\ with\ spaces\ in\ the\ name

    Username: bandit3
    Password: UmHadQclWmgdLOKQ3YNgjWxGoRMb5luK
    
###Bandit - Level 4###

###Bandit - Level 5###

###Bandit - Level 6###

###Bandit - Level 7###

###Bandit - Level 8###

###Bandit - Level 9###

###Bandit - Level 10###

###Bandit - Level 11###

###Bandit - Level 12###

###Bandit - Level 13###

###Bandit - Level 14###

###Bandit - Level 15###

###Bandit - Level 16###

###Bandit - Level 17###

###Bandit - Level 18###

###Bandit - Level 19###

###Bandit - Level 20###

###Bandit - Level 21###

###Bandit - Level 22###

###Bandit - Level 23###

###Bandit - Level 24###

###Bandit - Level 25###

###Bandit - Level 26###

###Bandit - Level 27###
