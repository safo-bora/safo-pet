# How to Create a Website with Simple 5 Steps from Scratch by GitHub Pages
This guide will walk you through creating and deploying a simple website using GitHub Pages.

## Steps

### 1. You Should Have a GitHub Repository
Before you begin, make sure you have a GitHub account and a repository where you will store the files for your website.

### 2. Basic Settings
#### 2.1. Read and Write Permissions:
- Go to the "Settings" tab within your repository.
- Click on "Actions" and then "General."
- Add "Read and write permissions" and "Allow GitHub Action to create and approve pull request."

#### 2.2. Build and Deployment Settings:
- Go to the "Settings" tab within your repository.
- Click on "Pages."
- Under "Build and deployment," select the branch you want to deploy (for example, Branch -> Main).

### 3. Create GitHub Configuration File
You'll need to create a configuration file to instruct GitHub Pages how to build your site. 
Here's an example:
https://github.com/safo-bora/safo-pet/blob/8af67421a75cf044635bf0330217c5f5f73871e3/.github/workflows/main.yml

### 4. Create HTML That You Want to Deploy
Design and write the HTML code for the web pages you want to display. 
You can also include CSS and JavaScript files to enhance the functionality and appearance of your site.

###  5. Commit Your HTML and Verify the Build
Once you've created the necessary files, commit them to your repository.
Go to the "Actions" tab within your repository to verify that the build is successful (green).
Once the build is complete, open the generated URL to view your live website.
Done!
Congratulations, you've successfully created and deployed a website using GitHub Pages! 

Now everyone can open and see your website!

# Pet Project WebSite (Example):
https://safo-bora.github.io/safo-pet/ 
