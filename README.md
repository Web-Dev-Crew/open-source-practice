# open-source-practice

Repository for you to raise a Pull Request to practice open-source! 🎉

## tools

before we begin you should install git on your computer : [git](https://www.git-scm.com/)

## Steps 🪜

## 1. fork this repository

- Click the gray Fork button at the top right of this page. <br/> This creates your copy of the project and saves it as a new repository in your GitHub account.
 ![image](https://github.com/MhL5/open-source-practice/assets/135700087/c3129f9d-16a6-4724-85e8-c3c5050e88f4)

<hr>

 ![image](https://github.com/MhL5/open-source-practice/assets/135700087/3b5096ee-7d2f-4505-a754-bc0fa48ecc57)

<br/>

## 2. clone your fork

- after you forked this repository successfully, you should copy the repository url
 ![image](https://github.com/MhL5/open-source-practice/assets/135700087/b3c85df5-ec3f-4b49-b470-7d82cd89d560)


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
<br/>

## 3. Edit the code

- Create a new branch by running `git branch branchName`
  example: `git branch openSourcePractice`
  ![image](https://github.com/MhL5/open-source-practice/assets/135700087/33730409-98ec-45de-99da-c3d986d2cf69)

- you are currently at `main` branch, you can switch your branch by running `git switch branchName`
  ![image](https://github.com/MhL5/open-source-practice/assets/135700087/908e1489-8ed0-4a55-beed-5817204785b3)


- add your name in the `index.html` inside a div 
  example: 
  ```html
   <div> MhL5 <div>
  ```
  ![image](https://github.com/MhL5/open-source-practice/assets/135700087/f5d2fc8a-652a-4f26-bcb7-3d350b54605d)


- add the changes you made to git using: `git add .` ( . means all the changes )
  ![image](https://github.com/MhL5/open-source-practice/assets/135700087/58112c79-bfde-4767-a38c-6e43845e39ad)

  
- commit your changes with a message : `git commit -m "added my name"`
  ![image](https://github.com/MhL5/open-source-practice/assets/135700087/1ead3866-e0ea-4b97-999e-7d9ba314f2ca)


- push your changes into your remote repository in github: `git push -u origin branchName` (here you might get prompted to enter your email and name if its your first time, also a login into github)

<br/>

![image](https://github.com/MhL5/open-source-practice/assets/135700087/854bbdfd-8b9b-4b5d-99d7-acf50ad68b0c)



### 4. Sending a pull request

- open your forked repository on github and click on `compare & pull request`
![image](https://github.com/MhL5/open-source-practice/assets/135700087/a334d4eb-a91b-4304-918f-fe584f975560)


- send a pull request
( you should compare `Web-Dev-Crew/open-source-practice` `main` with your `forked repository` `the branch you made`
![image](https://github.com/MhL5/open-source-practice/assets/135700087/819a2f22-a039-49ea-914d-309756c01c71)



- write a title and a description and create your own first pull request

- now your Done, sit tight and wait for your pull request to be merged.
