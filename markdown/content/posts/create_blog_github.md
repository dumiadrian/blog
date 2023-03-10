---
title: "Create_blog_github"
date: 2023-03-10T22:48:47+02:00
draft: true
---
****


# 1. Create an account on Github
****


# 2. Download Github Desktop
****


# 3 Install hugo (macbook air m1)
```bash
brew install hugo
```
If you need to install brew
	Open the terminal and run the following command:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
And press ENTER
![image](https://user-images.githubusercontent.com/127399572/224429191-5c87ebdc-3f4c-43d1-82af-4ffe079d8e76.png)		
Add Homebrew to your PATH: copy that 2 lines in your terminal and press Enter
****


# 4. Create a new repository
![image](https://user-images.githubusercontent.com/127399572/224429306-6504ebb3-7f0a-4fe4-bb67-68cdc918ff11.png)
![image](https://user-images.githubusercontent.com/127399572/224429344-b1d86bf4-dfe7-46d9-bd56-35e425617074.png)
![image](https://user-images.githubusercontent.com/127399572/224429389-e0fbdf6d-7087-4061-ad47-4efe2e994554.png)
![image](https://user-images.githubusercontent.com/127399572/224429431-9d2b867f-5845-4adc-892c-a8c0cd4264be.png)
![image](https://user-images.githubusercontent.com/127399572/224429473-48dc0878-720a-4d45-8e17-19fa29f020ce.png)
****


# 5. Create a new site 
Open a terminal, -> Go to desktop and run the following command:
```bash
hugo new site blog
```
![image](https://user-images.githubusercontent.com/127399572/224429965-11d26952-d860-4303-8de1-ed459ff110c1.png)
****


# 6. Now you need to git clone your theme 
Go to -> /blog/themes and run the command:
```bash
git clone https://github.com/niklasbuschmann/contrast-hugo.git
```
You need to modify config.toml file
![image](https://user-images.githubusercontent.com/127399572/224430049-3138731a-0571-47c1-ab08-cb7b0bfad349.png)

baseURL -> is from your github pages

Create a new posts
```bash
hugo new posts/mypost.md
```
Modify the post:
```bash
cd /content/posts
nvim mypost.md
hugo server -D
```
****


# 7. Build the code -> hugo -D -t contrast-hugo
![image](https://user-images.githubusercontent.com/127399572/224430182-9879bec1-3abf-444b-96d9-0ce9207dddc0.png)
****


# 8. Now you need to copy all files from public folder into the git folder.


Add images: Go to git -> Issues -> Images -> Copy the image in  "Leave a comment". -> Comment

