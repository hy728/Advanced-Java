<strong> **DO NOT DISTRIBUTE OR PUBLICLY POST SOLUTIONS TO THESE LABS. MAKE ALL FORKS OF THIS REPOSITORY WITH SOLUTION CODE PRIVATE. PLEASE REFER TO THE STUDENT CODE OF CONDUCT AND ETHICAL EXPECTATIONS FOR COLLEGE OF INFORMATION TECHNOLOGY STUDENTS FOR SPECIFICS. ** </strong>

# WESTERN GOVERNOR UNIVERSITY 
## D387 – ADVANCED JAVA
Welcome to Advanced Java! This is an opportunity for students to write multithreaded object-oriented code using Java frameworks and determine how to deploy software applications using cloud services.

FOR SPECIFIC TASK INSTRUCTIONS AND REQUIREMENTS FOR THIS ASSESSMENT, PLEASE REFER TO THE COURSE PAGE.
## BASIC INSTRUCTIONS
For this assessment, you will modify a Spring application with a Java back end and an Angular front end to include multithreaded language translation, a message at different time zones, and currency exchange. Then, build a Docker image of the current multithreaded Spring application and containerize it using the supporting documents provided in this task.

测试
## SUPPLEMENTAL RESOURCES 
1.	How to clone a project to IntelliJ using Git?

> Ensure that you have Git installed on your system and that IntelliJ is installed using [Toolbox](https://www.jetbrains.com/toolbox-app/). Make sure that you are using version 2022.3.2. Once this has been confirmed, click the clone button and use the 'IntelliJ IDEA (HTTPS)' button. This will open IntelliJ with a prompt to clone the proejct. Save it in a safe location for the directory and press clone. IntelliJ will prompt you for your credentials. Enter in your WGU Credentials and the project will be cloned onto your local machine.  

2. How to create a branch and start Development?

- GitLab method
> Press the '+' button located near your branch name. In the dropdown list, press the 'New branch' button. This will allow you to create a name for your branch. Once the branch has been named, you can select 'Create Branch' to push the branch to your repository.

- IntelliJ method
> In IntelliJ, Go to the 'Git' button on the top toolbar. Select the new branch option and create a name for the branch. Make sure checkout branch is selected and press create. You can now add a commit message and push the new branch to the local repo.

## SUPPORT
If you need additional support, please navigate to the course page and reach out to your course instructor.
## FUTURE USE
Take this opportunity to create or add to a simple resume portfolio to highlight and showcase your work for future use in career search, experience, and education!

![这是图片](Docker_Container_Stats.png "Magic Gardens")

Project Introduction
Background
In the contemporary digital age, the hospitality industry is experiencing a significant transformation driven by technological advancements. The need for efficient, user - friendly, and feature - rich hotel management systems has become more crucial than ever. The LandonHotelApp is developed in this context. With the increasing complexity of hotel operations, such as room management, reservation handling, and providing multilingual services to a diverse customer base, there is a pressing demand for a comprehensive solution. This application aims to bridge the gap between traditional hotel management methods and the modern requirements of the digital era, enhancing both the operational efficiency of the hotel and the experience of its guests. (Author: [Your Name])
Objectives
Enhanced Operational Efficiency: Automate and streamline various hotel operations, including room management, reservation processing, and data collection. By reducing manual tasks, the application aims to minimize errors and save time for hotel staff, allowing them to focus on providing high - quality customer service.
Improved Customer Experience: Offer guests an intuitive and convenient platform to search for available rooms, view room details, make reservations, and access multilingual welcome messages. The application strives to meet the diverse needs of guests from different cultural backgrounds, providing a seamless and personalized experience.
Data - Driven Decision Making: Collect and analyze data related to room occupancy, reservation patterns, and customer preferences. This data will be used to support strategic decision - making for the hotel, such as pricing strategies, marketing campaigns, and resource allocation. (Author: [Your Name])
Function Overview
Room Management: The system provides hotel administrators with a comprehensive set of tools to manage room information. They can add, edit, or delete room details, including room numbers, room types, prices, and availability status. Based on maintenance schedules or other factors, administrators can mark rooms as available or unavailable in real - time.
Reservation Handling: Guests can easily search for available rooms by specifying their check - in and check - out dates. The application will display a list of all available rooms along with their corresponding prices and room types. Guests can then make reservations directly through the platform, and hotel staff can manage these reservations, including confirming, modifying, or canceling them.
Multilingual Support: To cater to international guests, the application offers multilingual support. Guests can select their preferred language to view welcome messages and use the application. This feature ensures that guests from different cultural backgrounds can easily understand and interact with the application.
Unit and End - to - End Testing: The application comes with built - in support for unit and end - to - end testing. Developers can run unit tests using ng test via [Karma](https://karma - runner.github.io), and end - to - end tests using ng e2e after adding the necessary testing package. (Author: [liyouyang])

Commit Message
"Initial commit of the English README project introduction, including background, objectives, and function overview."
Code Changes
markdown
# Project Introduction

## Background
In the hospitality industry, efficient management of hotel rooms and reservations is crucial for providing high - quality services to guests. The Landon Hotel, aiming to streamline its operations and enhance customer experience, has initiated the development of this application. As the market becomes more competitive, the hotel needs a comprehensive system to manage room availability, handle reservations, and provide a user - friendly interface for guests to search and book rooms. This project is developed to meet these needs and adapt to the digital transformation trend in the hospitality industry. (Author: [Your Name])

## Objectives
1. **Enhanced Operational Efficiency**: Automate the process of room management and reservation handling, reducing manual errors and saving time for hotel staff.
2. **Improved Customer Experience**: Provide guests with an easy - to - use platform to search for available rooms, view room details, and make reservations at any time.
3. **Data - Driven Decision Making**: Collect and analyze data related to room occupancy, reservation patterns, and customer preferences to support strategic decision - making for the hotel. (Author: [Your Name])

## Function Overview
1. **Room Management**: The system allows hotel administrators to manage room information, including room numbers, prices, and room types. They can also mark rooms as available or unavailable based on maintenance schedules or other factors.
2. **Reservation Handling**: Guests can search for available rooms by specifying check - in and check - out dates. The system will display all available rooms and their prices. Guests can then make reservations directly through the platform. Hotel staff can also manage reservations, including confirming, modifying, or canceling them.
3. **Multilingual Support**: To cater to international guests, the application provides multilingual support. Guests can choose their preferred language to view welcome messages and use the application. (Author: [liyouyang])

Commit Message
"Review and improvement of the English README project introduction, enhancing language accuracy and clarity."

# Project Introduction

## Background
In the highly competitive hospitality sector, efficient management of hotel rooms and reservations is of utmost importance for delivering superior services to guests. The Landon Hotel, in an effort to optimize its operations and elevate the customer experience, has embarked on the development of this application. With the intensifying market competition, the hotel requires a comprehensive system that can effectively manage room availability, handle reservations, and offer a user - friendly interface for guests to search and book rooms. This project is designed to address these requirements and keep pace with the digital transformation trend in the hospitality industry. (Author: [Your Name])

## Objectives
1. **Enhanced Operational Efficiency**: Automate the room management and reservation handling processes to minimize manual errors and save valuable time for hotel staff.
2. **Improved Customer Experience**: Provide guests with an intuitive platform that enables them to effortlessly search for available rooms, view detailed room information, and make reservations at their convenience.
3. **Data - Driven Decision Making**: Gather and analyze data on room occupancy, reservation trends, and customer preferences to support informed strategic decision - making for the hotel. (Author: [Your Name])

## Function Overview
1. **Room Management**: The system empowers hotel administrators to manage room details such as room numbers, prices, and room categories. They can also update the room availability status based on maintenance schedules or other relevant factors.
2. **Reservation Handling**: Guests can search for available rooms by specifying their check - in and check - out dates. The system will promptly display all available rooms along with their corresponding prices. Guests can then make reservations directly through the platform. Hotel staff can manage reservations comprehensively, including confirmation, modification, and cancellation.
3. **Multilingual Support**: To accommodate international guests, the application offers multilingual support. Guests can select their preferred language to view welcome messages and utilize the application seamlessly. (Author: [Your Name])


# Installation and Deployment
(Author: [陆玟颖])
## Prerequisites
Ensure that Node.js (version [specific version number] or higher) and npm (Node Package Manager) are installed on your system. Visit the Node.js official website to download the appropriate installer for your operating system (e.g., Windows, Mac, Linux). Follow the installation wizard prompts, keeping default settings to complete the installation quickly. Verify the installations by running node -v and npm -v in your terminal; these commands should return the respective version numbers. If your npm version is outdated, upgrade it using npm install -g npm to ensure access to the latest features and security patches. npm typically installs automatically with Node.js and is used to manage project dependencies.