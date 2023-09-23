# Learning Portal Project

This is by far my one of the complex project I have ever did. Btw , it's a learning portal application where two type of user:
1. Student
2. Admin

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation
To get started with this project, follow these steps:

1. **Clone the Repository:**
```bash
git clone https://github.com/ZmnRobin/learning-portal-client.git

```
2. **Navigate to the Project Directory:**
```bash
cd learning-portal-client
```
3. **Install Dependencies:**

Run the following command to install the project's dependencies:
```bash
npm install
```

This will download and install all the required packages and libraries.

4. **Start the Development Server:**

Once the installation is complete, you can start the development server by running:
```bash
npm start
```
## Usage
After opening the project in your localhost then you can use this project locally.
### When you are an Student:
1. You can create account and login with your account.
2. After successfull login you will be redirected to coursePlayer page, where you can see uploaded content video by the admin.
3. Then if any video have assignment and quiz then you can see that under the video player.
4. You can submit assignment by providing github link.
5. Also you can participate in quiz, there will be multiple quiz for some video.
5. There is a leaderboard section, where you can see your quiz and assignment mark and also your rank in the leaderboard.

### When you are an Admin:
1. There is no registration system for admin,for accessing admin first you have to login with admin credentials:

2. **Go to /admin route first:**
```bash
https://github.com/ZmnRobin/learning-portal-client.git/admin

```
3. ** The put the admin email and password like this: (Remember: Test all functionalities but don't do anything wrong!)

```bash
email: admin@gmail.com
pass: LPadmin123456

```
4. After login to admin you can see 4 options.
5. Here you can add add,update and delete video for the course.
6. You can add assignment for a particular video. One video have only one assignment.Also delete and update them.
7. You can add quiz , one video can be multiple quiz , also you can update delete them.
8. You can see all assignment submission , and then give marks to the student who didn't get marks. 

## License

All rights reserved to Rokonuzzaman Robin.
