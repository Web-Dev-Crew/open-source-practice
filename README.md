# open-source-practice

Repository for you to raise a Pull Request to practice open-source! 🎉
you can follow the documents or if you are lazy like me you can watch this video instead: VIDEO PLACEHOLDER

## tools

before we begin you should install git on your computer : [download git](https://www.git-scm.com/)

## Steps 🪜

### 1. fork this repository 
- Click the gray Fork button at the top right of this page. <br/> This creates your copy of the project and saves it as a new repository in your GitHub account.

<br/>

## 2. clone your fork
- after you forked this repository successfully, you should copy the repository url
- use the command below in order to clone the repository into your own local computer
  this will clone the project
```bash
git clone url .
```
example: 
```bash
git clone https://github.com/Web-Dev-Crew/open-source-practice.git .
```

<br/>

## 3. Edit the code

- Create a new branch by running `git branch branchName`
  example: `git branch openSourcePractice`
- you are currently at `main` branch, you can switch your branch by running `git switch branchName`
- add your name in the `index.html` inside a div 
  example: 
  ```html
   <div> MhL5 <div>
  ```
- add the changes you made to git using: `git add .` ( . means all the changes )
- commit your changes with a message : `git commit -m "added my name"`
- push your changes into your remote repository in github: `git push -u origin branchName` (here you might get prompted to enter your email and name if its your first time, also a login into github)

<br/>

### 4. Sending a pull request

- open your forked repository on github and click on `compare & pull request`
- send a pull request
( you should compare `Web-Dev-Crew/open-source-practice` `main` with your `forked repository` `the branch you made`
- write a title and a description and create your own first pull request
- now your Done, sit tight and wait for your pull request to be merged.
