<div align="center">

  <!-- Add badges using the following format: -->
  <!-- ![Name](urlToShieldHere)(urlToGithubHere) -->

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>

<!-- PROJECT LOGO -->

<div align="center">

  <h3 align="center">Gettin Social With API's</h3>

  <p align="center">
    <a href="https://github.com/Jbyrd126/Gettin_Social_With_API-s"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="#usage">View Demo Video</a>
    ·
    <a href="https://github.com/Jbyrd126/Gettin_Social_With_API-s/issues">Report Bug</a>
    ·
    <a href="https://github.com/Jbyrd126/Gettin_Social_With_API-s/issues">Request Feature</a>

  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

<!-- Add screenshots using the following format: -->
<!-- ![Screenshot alt description](directPathOfScreenshots) -->

This project was built with MongoDB

### Built With

<div align="center">

[![Javascript](https://img.shields.io/badge/Language-JavaScript-ff0000?style=plastic&logo=JavaScript&logoWidth=10)](https://javascript.info/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-80ff00?style=plastic&logo=MongoDB&logoWidth=10)](https://www.mongodb.com/home)
[![Node.js](https://img.shields.io/badge/Framework-Node.js-ff0000?style=plastic&logo=Node.js&logoWidth=10)](https://nodejs.org/en/)
[![Express](https://img.shields.io/badge/Framework-Express-80ff00?style=plastic&logo=Express&logoWidth=10)](https://expressjs.com/)
[![npm](https://img.shields.io/badge/Tools-npm-ff0000?style=plastic&logo=npm&logoWidth=10)](https://www.npmjs.com/)
[![VS Code](https://img.shields.io/badge/IDE-VSCode-ff0000?style=plastic&logo=VisualStudioCode&logoWidth=10)](https://code.visualstudio.com/docs)

</div>

<!-- GETTING STARTED -->

## Getting Started

Once completely built, this application will function as a social media backend that can be tested locally.

### Local Installation / Testing

1. Clone the rep

```
git clone git@github.com:Jbyrd126/Gettin_Social_With_API-s.git
```

2. Install dependencies

```
npm run install
```

3. Seed the database

```
npm run seed
```

4. Launch the app in development environment

```
npm run start
```

5. Visit:

```
http://localhost:3001/api/ (http://localhost:3001/api/)
```

<!-- USAGE EXAMPLES -->

## Usage

[Video Demo](https://watch.screencastify.com/v/Fa9vkaJwHA5DFLJt6Pxk)

### Available Routes

#### User Routes

/api/users - Get all users, create user
/api/users/:userId - Get single user, update user, delete user

#### Friend Routes

/api/users/:usertId/friends/:friendId - Add friend, delete friend

#### Thought Routes

/api/thoughts/ - Get all thoughts, create thought
/api/thoughts/:thoughtId - Get single thought, update thought, delete thought

#### Reaction Routes

/api/thoughts/:thoughtId/reactions - Create reaction
/api/thoughts/:thoughtId/reactions/:reactionId - Delete reaction

<!-- ROADMAP -->

## Roadmap

#### MVP

- [x] Back End
  - [x] Skeleton
  - [x] Seeds
  - [x] Read Routes
  - [x] Create Routes
  - [x] Update Routes
  - [x] Delete Routes

#### Future Development

- [ ] Add front end

See the [open issues](https://github.com/Jbyrd126/Gettin_Social_With_API-s/issues) for a full list of proposed features (and known issues).

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

<!-- LICENSE -->

## License

This project is licensed under the MIT license.

See LICENSE.txt for more information.

<!-- CONTACT -->

## Contact

[Rob Byrd](https://github.com/Jbyrd126)- jbyrd126@gmail.com

Project Link:

[Github Repository](https://github.com/Jbyrd126/Gettin_Social_With_API-s)

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

Big ups to our Instructor John Dinsmore and shots way out to our TA Mary Elenius for tryin to push this mouth breather towards the light!
