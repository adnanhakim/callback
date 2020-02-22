# DJ Whiteboard

## About

A Node.js/Express project for live teacher-student integrated session management using sockets, wherein the student can write, compile, run and post codes and the teacher can edit the codes live.

> NOTE: This application was a modification for deployment in the college.
>
> For more details on the original build, click the link below
>
> whiteboard
> [github.com/whiteboard](https://github.com/bhaveshsingh0206/Whiteboard)

## Technology Stack

1. Frontend developed using vanilla HTML, CSS and JS
1. Backend developed using Node.js/Express
1. Data stored in MongoDB
1. Live code interaction done using [socket.io](https://www.npmjs.com/package/socket.io)
1. User session management done using [passport.js](https://www.npmjs.com/package/passport)
1. Compiler provided by [compilex](https://www.npmjs.com/package/compilex)
1. Editor provided by [Ace](https://ace.c9.io/)
1. Developed using [goorm IDE](https://ide.goorm.io/)

## Developers

-  Adnan Hakim [github.com/adnanhakim](https://github.com/adnanhakim)

   -  UI Designing, Frontend and Dashboard Backend

-  Ali Abbas Rizvi [github.com/rizvialiabbas](https://github.com/rizvialiabbas)

   -  Compiler, Notification and Practice Room

-  Arsh Shaikh [github.com/arshshaikh06](https://github.com/arshshaikh06)

   -  UI Designing, Frontend and Editor

-  Bhavesh Singh [github.com/bhaveshsingh0206](https://github.com/bhaveshsingh0206)

   -  Sockets Handling and Backend

-  Rahil Desai [github.com/Rahildesai7](https://github.com/Rahildesai7)

   -  Schema and Backend

-  Hussain Sadriwala [github.com/hussainf46](https://github.com/hussainf46)

   -  Forgot Password Module

## Features

-  Teachers can create rooms using sockets
-  Students can join rooms using a password
-  Once student has joined a room, he/she can write code using an editor
-  The student can also compile the code in an online editor
    - Languages supported are C, Java and Python
-  Teacher can view the code of any student _live_
-  Teacher can also edit the code of any student _live_
-  The student can then post the code in a dashboard for all other students to see
-  Other students can also download the code and run it locally
-  Students can send messages to teachers if they are not online
-  Teachers can view these messages and reply to them
-  Student can also view all his codes in his profile
-  Dashboard also provides statistics to users such as
   -  No of posts of the day
   -  No of posts of that user

## Screenshots

### Dashboard

Profile information and statistics on the left, posted codes in the middle and sending offline messages(notifications) to the teachers on the right

![Dashboard](https://i.imgur.com/0KBAvEg.png?2)

### Room Selection

Only teachers can create rooms, and students get information about each room and can join the room by entering the password

![Room Selection](https://i.imgur.com/hQKdkbn.png)

### Room (For the student)

Student can edit, compile, run and post only their own code

![Room(Student)](https://i.imgur.com/Y9n73xH.png)

### Room (For the teacher)

Teacher can view the online students on the left and can view and edit their code live

![Room(Teacher)](https://i.imgur.com/pv8mLb3.png)

## MIT LICENSE

> Copyright (c) 2020 Team Void
>
> Permission is hereby granted, free of charge, to any person obtaining a copy
> of this software and associated documentation files (the "Software"), to deal
> in the Software without restriction, including without limitation the rights
> to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
> copies of the Software, and to permit persons to whom the Software is
> furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.
