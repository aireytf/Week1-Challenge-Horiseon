# Week1-Challenge-Horiseon

## Description

This repository serves to showcase my work in completing the Module 1 Challenge of my edX Bootcamp. 

The challenge was an on-the-job ticket to refactor an existing site for a marketing agency. The focus being on improving the accessibility of the existing site. 

This project required that I refactor the website to meet accessibility standards whilst maintaining the application's appearance, as per the starter code and as shown in the following Demo screenshot: 

![Demo](/starter/assets/images/01-html-css-git-challenge-demo.png)

I achieved the above by completing the following tasks:
- I implemented semantic structure to the HTML elements;
- I ensured the HTML elements follow a logical structure independent of styling and positioning;
- I added alt attributes, where they were missing in image elements;
- I gave sequential order to the heading attributes;
- I gave the title element a concise, descriptive title; and
- I ensured all the application's links function correctly, by fixing the link to the Search Engine Optimization content on the site. 

## Table of Contents 

- Usage
- Credits
- License

## Usage

To view my work on this challenge, you can review the sections of this repository and my refactored version of the site which is deployed at https://aireytf.github.io/Week1-Challenge-Horiseon/ 

Explore the different sections of the website and click on the navigation links in the header, to test the accessibility of the website. 

To review my changes to the starter code, on the deployed site referenced above, open the Chrome DevTools by pressing Command+Option+I (macOS) or Control+Shift+I (Windows). A console panel should open either below or to the side of the webpage in the browser. There you will see the refactored code.

## Credits

I utilised the resources at w3schools.com in the README provided for this challenge, to apply appropriate semantic and logical structure, and to follow accessibility standards for this site. 

I had difficulty deploying this application, as only this README from my repository was being shown on the live site. I researched the issue on stackoverflow.com and found a solution there that worked, which was to use the deployment option of GitHub Actions in Pages and using Jekyll to change the source for the site from [./] to [./starter/] , to redirect inside the subfolder 'Starter' that I initally pushed to GitHub with the starter code for this challenge. This meant that the index.html inside the 'Starter' folder was being deployed to the site, as needed. 

## License

As per the contents of this repository, this project is under an MIT license. As I initially created this repository without a license, I took the opportunity to figure out how to add one after a respository has already been created. This was as simple as adding a new file to the repository and selecting a license template (having given the new file the name LICENSE). 
