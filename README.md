# Firstofall
First of all I need to write down step by step process
I have to write down step by step process
first create a repository and give it a name 
then go and creat a folder and give it a name I named mine my repository name
then go to gitbash
cd and enter
then go to your folder that you created in my case its Firstofall
cd firstofall
then LS enter
write the command as follows
git config --global user.name "your own user name here" enter
git config --global user.email "your own email address here" enter
then use clone command as follows
git clone paste the git code you copied from your repository page from git
next give LS command and you will see an new directory by name of Firstofall
then go to cd fistofall and you will see a new dirctory by name of README.md
now you can go back to your folder that you created firstofall and creat a file (New Text Documnet) you give it any name you want for example first learn.txt or whatever you want
you can open that text file and write anything you want in it and save it 
write LS command on your gitbash and you will see the file by name you created it in my case it would be first learn.txt
since the bash command already recognize it as txt file so i am going to delete txt from this file in my folder "firstlearn"
now add this file to your gitbash
git add firstlearn ( or whatever name you saved your txt file on)
now place a command 
git status enter
you will see an new file and firstlearn.txt file
now we need to commit this command
git commit -m"firstlearn.txt'
now you need to forward this to your github account and the command for that is git push
git push -u origin main(master) enter
for the first time it will ask your git user name and password
then go to your git repository and refresh the page
you will see README.m and text file that you created.
and when you open this firstlearn text file you see what you wrote in it
if you want to make change in txt file go to your folder open your text file and bring changes in your text and go back to gitbash and 
git status enter and you will see one folder in red saying modified 
go to git
git commit -m "second commit" firstlearn.txt and enter
then push it
git push -u origin main(master) enter
go and refresh your page and you will see the changes
