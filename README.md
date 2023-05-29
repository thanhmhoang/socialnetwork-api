# Social Network API

## Description

For this Module 18 Challenge, the challege was to to build an API for a social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. While using Express.js for routing, a MongoDB database, and the Mongoose ODM. The motivation for this project is that MongoDB is a popular choice for many social networks due to its speed with large amounts of data and flexibility with unstructured data. Over the last part of this course, we’ll use several of the technologies that social networking platforms use in their full-stack applications. Because the foundation of these applications is data, it’s important that you understand how to build and structure the API first. 

## User Story

```md
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```


## Acceptance Criteria

```md
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```

## Installation

To use this application, please follow the link to the GitHub repository, https://github.com/thanhmhoang/ecommerce-backend. Once on the GitHub repo, click on the green "Code" button, then click "SSH" and copy the text in the box to be used as your SSH key. Next if you are on Windows, open your Git Bash, and your terminal if on Mac. Then proceed to where you would like this folder me location in your device and run the command 
The application will be invoked by using the following command:
```bash
git clone git@github.com:thanhmhoang/socialnetwork-api.git
```
Please make sure that your MongoDB is  downloaded and running. 

Users will also need to install the following dependencies to run the application properly, this can be done by running the following command:

```bash
npm i express moment mongoose@6.9.2
```

If the dependencies are already listed in the package.json file provide, users can simply run the following command:

```bash
npm i
```

## Usage

To use this application, once you have completed the installation instructions, open the folder in VS code. 

Once the VS code is open, right click on the "server.js" folder on the root level, then run the following command below to start the program:

```bash
npm start
```
Users can then run the application in Insomnia to GET data for each route(User, Thought, Reaction, Friend) as well as CREATE, UPDATE, and DELETE data in those routes.

Follow this link for a video walk-through of the application: https://youtu.be/v5oELK_aGQY


## Credits

Thien Nguyen - Former UW Bootcamp student

## License

MIT License
![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)
        
Copyright (c) 2023 Thanh Hoang.
        
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated
documentation files (the "Software"), to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and
to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions
of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO 
THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.