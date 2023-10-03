## TUTORIAL FOR GIT & GITHUB  BASICS  :octocat:. This tutorial has three sections:

* Git
* GitHub
* Using Git

For a more in depth understanding of today lesson visit these links 

Tech with Tim Channel
https://www.youtube.com/watch?v=jG4Vs81kMlc&pp=ygUOZ2l0IGFuZCBnaXRodWI%3D

FreeCodeCamp Channel
https://www.youtube.com/watch?v=RGOj5yH7evk&pp=ygUOZ2l0IGFuZCBnaXRodWI%3D

DZone website
https://dzone.com/articles/top-20-git-commands-with-examples

# 1. Git : 

![git](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/a8ba92da-659e-46d9-a84a-8dd51acd6b3f)

## 1.0 What is Git, Etymology and a short history.
* [ ] Version Control (aka Revision control, source control)
* [ ] Distributed version control system, Linus Torvalds, 2005
* [ ] GIT: Global Information Tracker or the stupid content tracker or unpleasant person in British slang

## 1.1 Understanding Git and Github 
Most of the the times you've heard fellow developers  🗣️ talking about collaboration and are often wondering 🤔 what is that but worry no more ,after this lesson you'll be a git and github "pro" 😎 coder 


![setting-git](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/b951d840-6e25-4c4d-aefe-4224c53de2f1)


## 1.2 Installing Git
What is git exactly 
Git is a version-control system but really what it boils down to is a system for naming files 


Linus Torvalds





![git-inv](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/1e1e6f15-2371-4c64-a2c6-4d03f47e4070)



Linus Torvalds, creator of Linux, along with others in the Linux development community, built and released Git in 2005. They undertook the project because there was a lack of free and open source version control systems that could meet their requirements for Linux kernel development.

![linux-achiev](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/d567f3e9-03ea-4d3e-a8fd-07e29928de79)


He was a key figure in collaboration today as we know it 

When creating a software ,it is a series of small milestones where each milestone 🪨 is wring code and a bunch of different  files your app will constantly move from a state of chaos 🔥 to stability 🌊 and gives you a way to track these changes and create branches that you can experiment 🧪 on and merge them later

it is used for 
* Tracking code changes
* Tracking who made changes
* Coding collaboration

What does Git do? 🤔
* Manage projects with Repositories
* Clone a project to work on a local copy
* Control and track changes with Staging and Committing
* Branch and Merge to allow for work on different parts and versions of a project
* Pull the latest version of the project to a local copy
* Push local updates to the main project

 For Windows,
 install Git for Windows:
 https://git-scm.com/download/win

 For Linux, open gnome-terminal for GNome desktops  or Konsole for KDE desktops and type the command to install git based on your Linux distribution. 

 For a RedHat based Linux (Like CEntOS)
```
 sudo yum install git
```

 For Fedora
```
 sudo yum install git-core
```

 For a Debian based Linux (like Ubuntu)
```
 sudo apt-get install git 
```

 For Arch Linux
```
 sudo paceman -Sy git
```

 For Gentoo Linux
```
 sudo emerge ask —verbose dev-util/git
```

 For a MAC, open Terminal and execute following command
```
 brew install git
```

# 2. GitHub: 

![github](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/c3711e7f-d0d8-4646-afaf-e585085c06ea)

## 2.1 What is GitHub 
 GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.🌍

 Registering/Creating the account on GitHub
 You need
* A valid Email address
* A Computer or Phone
* Good internet

![gihub-web](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/e2d3bcdf-9ae1-4c69-b9d9-aae8c18450ac)

## 2.2 How to Sign Up for an Account
Now that you’re aware of GitHub’s benefits, you probably want to sign up for an account and try it out yourself. First navigate to the home page of the GitHub website, https://github.com.

In the upper-right corner click on the Sign Up button, as outlined in this screenshot:

Home page of the GitHub website with the mouse pointing at the **Sign Up** button which is highlighted

## 2.3 Create Your Account
You’ll see a page with a form under the heading “Create your account”.

Create your account page of GitHub website

Fill in each field for username, email address, and password. Choosing a username and email are especially important! Be sure to read through the following tips.

Username
When choosing a username, it’s wise to choose one you wouldn’t mind future employers or colleagues seeing. A combination of your first and last name like firstnamelastname or using initials, like i_lastname, are good because they make it easy to find you on GitHub or identify you when you make pull requests or reviews. Remember, you’re likely using this account to share or access code.

Also be aware that usernames are first come, first serve and may not be available if someone else already claimed the username. Additionally, usernames may only contain alphanumeric characters and hyphens are not allowed at the beginning or end.

Email Address
Like with usernames, pick an email that you’re comfortable sharing with peers and potential hires. Because of the way Git works, it’s important to note that your email can be exposed publicly when you make a pull request or merge in code to a repository, making it visible to anyone looking through your projects. When you sign up for a new GitHub account, your email address is hidden by default.

## 2.4 Finish Creating Your Account
Lastly, fill out the password field. When you’re done filling out the various fields, verify your account. You will receive an email from GitHub prompting you to verify.

Once you see a green checkmark, click on the blue Create an Account button.

Go to your email account, find the email from GitHub, and click on the button inside it to finish creating your account.

## 2.5 Settings
After successfully creating an account, you should see a page display asking you “What do you want to do first?” Go through the steps to complete your own set up process. You should now see a welcome page:

You can either answer the optional questions or move on by clicking on the Complete setup button to finish creating your account.

Your browser should display a personal dashboard with a section for your projects and some messages:

GitHub personal dashboard

Now you have your own GitHub account! You can continue to customize your account by:

* setting your email to private

* setting up two-factor authentication

That’s it, you now have your very own GitHub account. 🎉


# 3. Using Git

![git-img](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/e8f2ac77-91b9-40aa-9761-7ed1b1d2ce3e)


## 3.1 Setting up Git to connect to Github account
To set your git username type this in the terminal
```
git config --global user.name "your username"
```

To set your Git email, type this in your terminal:
```
git config --global user.email "youremail@gmail.com"
```

You will be asked to authenticate your GitHub account, so just sign in with the same email to confirm.

## 3.2 Create a repo on Github

![newRepo2-1](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/1c8c2a5a-3c31-46c8-b3a0-b38d16a15bc4)


Click the + sign at the top right corner to create a new repository. Repositories are like your code folders online.

 You will be prompted to this page 
 ![newRepo2-1](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/8b17d043-0403-4685-b2b1-904a1de28841)
 Name your repository and give it a description (this is optional).

Click the "Create repository" button to create the repository. You will be prompted to this page
![newRepoGitHub-1](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/0e00afd5-8f6f-4a6c-8ae7-7f7284ab2c22)


## 3.3 Push your Local Code to github
For a more indepth analysis on setting up vscode and git watch this video 
https://www.youtube.com/watch?v=lYiE5lBS13E&pp=ygUYZ2l0IGFuZCBnaXRodWIgaW4gdnNjb2Rl

open a folder with some files or  add some files (.html .js .php)
You can use the code editor built-in terminal to use Git to push your code to GitHub. Click ctrl + shift + ' to open the terminal in VSCode.

Input the commands below one after the other in your terminal. Press the Enter key to proceed after every input.
```
‌echo "# sample-code" >> README.md

git init

git add .

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/yourusername/sample-code.git

git push -u origin main
```

## 3.4 Pushing changes

#If you have not cloned (Our case) an existing repository and want to connect your repository to a remote server, you need to add it with

$git remote add origin https://github.com/yourusername/MyFirst.git
Replace the URL with the repository you created in step 3.3

 Now you are able to push your changes to the selected remote server i.e. your remote repository on GitHub.
 Your changes are now in the HEAD of your local working copy. To send those changes to your remote repository, execute 
 ```
 $git push -u origin master
```

That's it we are done with the first lesson covering  Basics of Git ,Github and Vscode integration and are ready to be a kickass developer 


![ending](https://github.com/IOT-Club-Mangu/GIt-Github-Crash-Course/assets/98217039/28022b03-81e0-410e-bc11-5822ccef9ee7)

