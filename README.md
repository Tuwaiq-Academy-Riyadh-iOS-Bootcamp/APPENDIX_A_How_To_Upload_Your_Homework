# APPENDIX_A_How_To_Upload_Your_Homework
If you still forget the steps of uploading your homework and you still need a document to refer to everytime, then congrats, you're a real programmer 🤟🏻. This repo is intended to help you to remember the steps everytime.

## Step1: Fork
Fork is used to make a copy of any repo in github to your account, so the first step is to make a copy from `Tweiq's` homework repo into your account, this can be simply done by clicking on the fork button from the original repo.

**NOTE: make sure you are in the right repo before clicking on Fork**

![image](https://user-images.githubusercontent.com/29100623/137931784-c74c2275-5793-491f-8b0c-db0128afc332.png)


## Step2: Clone
2.1 Create a new folder in your computer 
2.2 Open the terminal 
2.3 write in the terminal: `cd ` 
**NOTE YOU SHOULD WRITE `CD` THEN MAKE A SPACE**
2.4 Drag & drop the folder you created into the terminal so that you get its path written in terminal 👌🏻
2.5 press ENTER to execute the command.
2.6 get the url of the repo you want to clone by opening **YOUR COPY OF THE REPO** in github and then click in the green `code` button as shown in the following image:

**NOTE: IMPORTANT: make sure you are cloning your copy of the repo not the one in Tuwaiq's Account (check the (important) in the image) **

![image](https://user-images.githubusercontent.com/29100623/137933888-a301f415-7c34-45f5-92d7-d8344083b866.png)
2.7 return back to the command line and write: `git clone <paste the url here>`

Now you have a copy of your copy of the repo in your computer ✌🏻

## STEP3: Make your changes
3.1 Create a new xcode project, and make sure the project is created in the cloned folder (beside the readme.md file)

## STEP4: Save your changes in git (commit)
Now you are ready to submit your homework, but first, you should save (commit) the changes you made in your machine (locally)...
4.1 return back to the command line.
4.2 when you made the clone step, a new folder should be created inside the folder you created, therefore, make sure you `cd` into that folder before using `git commit`, otherwise, it won't work.
4.3 before you commit, you should decide which files should be integrated and tracked by git, and you need to track all the files. To do that, write the command:
```
git add .
```
**NOTE: (`.`) here means all the files in the folder**
4.4 Now the files are added to git and ready to make be saved (commited), so you can use the following command to commit the changes:
```
git commit -m "<replace this whith any message describing what you did>"
