In This Video I Am Going To Tell You That How To Upload A Project To Github Using Git Version Control System. Time Stamp: Intro - [00:00](https://www.youtube.com/watch?v=8bOMhoa35Ew&t=0s) What Is GitHub - [01:16](https://www.youtube.com/watch?v=8bOMhoa35Ew&t=76s) Downloading Git Version Control System - [01:45](https://www.youtube.com/watch?v=8bOMhoa35Ew&t=105s) GitHub Link [https://github.com](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbnVCVWkxZHNabHFfaUVhOG5IekZnSXJrVHBXUXxBQ3Jtc0tuRTNiS2thUFQxLW5fMi1waURkc1QtcWpNZTBCX3piWmFRZFBNOUpTdEk0Q0Y2Qk5SY1pBY1NicHhqNFMySlFtUUZhSWROSmtFcFVocmZJd1Rqc1E4ZlM4Y3JTdF9YWHQxQm1kREx0dnpUZ3NnREprQQ&q=https%3A%2F%2Fgithub.com) Download Git Version Control System [https://git-scm.com/downloads](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbTFfam1URlh4R0NzZFBsYWFhQzZKSGNHMUc0QXxBQ3Jtc0tuekhGWVFWYUhCNVI2a0p0enBXSkpUQjl2SXNpSXY2c1VOU1NwTnBIQlkxQXlFZllKWW1oVEdJeFlzN0lHT0JGMEpkeHc2d1VKdzRXWVpYcWk0aFA0RUxkd3RLMGg4SGplU0kzSS1ONl9Fc2lSQURNRQ&q=https%3A%2F%2Fgit-scm.com%2Fdownloads) My Official Website [https://oceanofanythingg.blogspot.com](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbV9LRFd2NlkxbU5MNHh3cW9DaU5XLWxkMTBsZ3xBQ3Jtc0tubzFPTkM4QnNPQWIwSWFORmlmNzVDbm9IT3RfY0M0dERVQWVWS3NkQi1RalRsdmd6czB0UlE3LVhmY0QyS0ZuR1k4T1BGZ1RwVnB3SVpNczh2d2tSZW1VRkk1M0hJZ05XV3dob3ZmLVF3Nm9KZy1Ldw&q=https%3A%2F%2Foceanofanythingg.blogspot.com) Watch Video In My Website. My Portfolio Website [https://oceanofanythingofficial.github.io](https://oceanofanythingofficial.github.io)

### Create New Repository

We need to create a new repository on GitHub website. Go to link and create repository [click here](https://github.com/) . Click New repository from the menu on your right once you are logged into your GitHub account.

### Now Open [git](https://git-scm.com/downloads)bash

Now go to the Terminal on your computer system. Use cd to navigate to the local project directory that you want to publish on GitHub.

CD to navigate to your directory

``` {.wp-block-preformatted style="background-color: white; border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; color: #333333; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
cd/your_directory_name
```

### Initialize Local Directory

### 

Now we will intialize our project. Use the below command to initialise the local directory as Git repository.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
git init
```

### Add Local repository

### 

Add all the files in the local directory to staging using the command below.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
git add . 
```

This command stages all the files in the directory, ready for commit.

### Commit Repository

### 

You can now commit the staged files using the command below. It is explanatory and helpful.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
git commit -m "Hello World"
```

### Add Remote Repository url

### 

Now, copy the remote repository URL provided by github to you when you published your repository on GitHub.

Now we will add the copied URL for your GitHub repository as remote repository using the code below.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
git remote add origin https://github.com/yourusername/your-repo-name.git
```

This command add our GitHub repository as a remote that you can then push your local repository changes.

### Push Local Repository to github

### 

In the last step, use the below command line in your terminal to push the local repository to GitHub. It will upload the file or project on github.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
git push origin master
```

If you use -u in the command, it will remember your preferences for remote and branch and you can simply use the command git push next time.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
git push -u origin master
```

### Pull Repository from github

### 

Pull the desired branch from the upstream repository. This method will retain the commit history without modification.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
git pull origin master
```

All the command to use upload the file and projects on github.

``` {.wp-block-preformatted style="border-radius: 1.5rem; border: 1px solid rgb(230, 230, 230); box-sizing: inherit; font-family: Monaco, "Courier 10 Pitch", Courier, monospace; font-size: 0.875rem; font-weight: 400; line-height: 1.43; margin-bottom: 2rem; margin-top: 0px; max-width: 100%; overflow-wrap: break-word; overflow: auto; padding: 2rem; white-space: pre-wrap;"}
 cd/your project directory 1) git init 2) git add . or git add ['filename'] 3) git commit -m "My first File commit" 4) git remote add origin https://github.com/yourusername/your-repo-name.git 5) git pull origin master 6) git push origin master
```

In just few minutes. We have successfully upload the project or file on github using command line


