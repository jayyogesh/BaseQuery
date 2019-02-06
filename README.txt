DISCLAIMER:
READ UP ON YOUR LOCAL LAWS FIRST BEFORE USING THIS PROGRAM, I WOULDN'T WANT ANY OF YOU BEAUTIFUL BASTARDS TO GO TO JAIL.
The reason I wrote this program is due to the fact that there are a ton of database dumps online. You can find them in 
places such as RAIDFORUMS.com or databases.today but there was no easy way to sort and search through it all. As 
far as where I am from it is LEGAL to download databases from publically accessible websites since they are common knowledge.
As far as I understand the CFAA(Computer Fraud and Abuse Act) only makes it ILLEGAL to access information without authorization. 
That said, if you're downloading passwords and account info it's (of course) still ILLEGAL to use any of that data to log in to 
any accounts that don't belong to you because then you are accessing information without authorization! Please don't be stupid,
only use this program within the bounds of the law.


Everything about this program is meant to be as simple as possible for YOU!


There are only a few things you need to do.
[1] Place any databases that you have into the "PutYourDataBasesHere" folder
    - As of right now, BaseQuery can only accept files in the format where each line is either "test@example.com:password" or "password:test@example.com"
    - It doesn't matter if the line formats are mixed up within the file. For Example) The first line may be "email:password" and the second can be "password:email"
    - One entry per line!! 
    - MAKE SURE THAT YOUR FILES DO NOT HAVE SPACES IN THE NAMES OF THE DATABASE FILES!
    - If you need a better visual there is an example.txt file in the folder "PutYourDataBasesHere"
    - You should delete the example file before running the program.
[2] Now that you have all of your files in the correct folder
    - Open up a terminal
    - type './run.sh' if that doesn't work type 'bash run.sh'
[3] Follow the instructions on the screen
    - That's it, enjoy!



Everything should be pretty well documented. If you see any bugs or errors let me know!
Also if you have any suggestions or think you can improve the efficiency of the code shoot me a message.
Author Github:   https://github.com/g666gle      
Author Twitter:  https://twitter.com/g666gle1

Developed On:
DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=18.04
DISTRIB_CODENAME=bionic

Bash Version:
GNU bash, version 4.4.19(1)-release (x86_64-pc-linux-gnu)

Python Version:
3.6.7

