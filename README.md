# How To Upload Your Homework From `Fork` to `Pull Request`
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
```
Now, your changes are saved in git, and you need to upload them to your copy of the repo in github.

## Step 5: Submitting Your Work
5.1 first, you should upload the changes you saved locally in git to the cloud; to do that, you can simply write in the Terminal:
```
git push
```
Now, if you check your copy of the repo in github, you should see the `readme.md` along with another folder which contains the code you wrote.
**NOTE: if you only see the `readme.md` file without any other files or folder, then there is something went wrong in one of the previous steps**
5.2 And finally, the remaining part to submit your changes back again to `Tuwaig's` repo of the homework, to do that:
5.2.1 From the main page of your copy of the repo, click on the `Pull Requests` tab.
5.2.2 click on `New Pull Request`
![image](https://user-images.githubusercontent.com/29100623/137937434-284e8f07-df20-465d-9eb5-31bdb9b8ac3a.png)

5.2.3 click on `Create Pull Request`
![image](https://user-images.githubusercontent.com/29100623/137937574-5cc833ca-2b2f-469c-8989-1600b27cc94b.png)


5.2.4 fill the input with your name and click on `Create Pull Request`
![image](https://user-images.githubusercontent.com/29100623/137937852-8840ff8a-f2bd-48ce-90e4-4e4e68eb4c09.png)

And that's it, now your pull request should appear if you open the `Pull Requests` tab from `Tuwaiq's` repo.


**NOTE: If you need to make some changes on your code and upload it again, then you can do the following**
1- make the changes
2- `git add .`
3- `git commit -m "<what you did>"`
4- `git push`
And now, there is no need to make the pull request again as the changes will reach to the pull request that you already made ✌🏻😃


