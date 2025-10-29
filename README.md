<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Unlicense License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="frontend/src/assets/poro1.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">PORODUCTIVITY</h3>

  <p align="center">
    Grow your poro(s) while getting things done!
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    &middot;
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    &middot;
    <a href="https://github.com/othneildrew/Best-README-Template/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
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
        <li><a href="#architecture-overview">Architecture Overview</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#sprint-1">Sprint 1</a></li>
    <li><a href="#sprint-2">Sprint 2</a></li>
    <li><a href="#sprint-3">Sprint 3</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#team-members">Team Members</a></li>
    <li><a href="#future-improvements">Future Improvements</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
<p align="center">
  <img src="frontend/src/assets/logo.png" alt="Logo" width="200" height="80">
</p>

The objective of this project is to create a Tamagotchi website that encourages productivity for all student users. This will be achieved by ensuring that the website has catered features and a clean user interface. The primary benefit of the applicatin is to reduce the mental load of the stakeholder by ensuring accurate, interactive, and usable tracking of the user’s student life. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Vite][Vite.js]][Vite-url]
* [![React][React.js]][React-url]
* [![Flask][Flask.js]][Flask-url]
* [![SQLite][SQLite.io]][SQLite-url]

### Project Managed With
[Google Spreadsheets](https://docs.google.com/spreadsheets/d/1rluqQt9uZa2duyi9nvsF7COYfvUs9HSwb7KjWsBwLcM/edit?usp=sharing)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


---

## 🏗️ Architecture Overview

**Frontend:** React (Vite)  
**Backend:** Flask REST API  
**Database:** SQLite  
**Integration:**  
- The frontend sends API requests to Flask for user authentication, XP, and task data.  
- Flask handles business logic (XP computation, data persistence).  
- SQLite stores user info, task lists, and pet states.  
- React dynamically updates the UI (XP bar, evolution state, Pomodoro timer) based on backend responses.  

```text
[Frontend: React/Vite] → [Flask API] → [SQLite Database]
             ↑                          ↓
       Real-time XP Updates ← Task & Timer Inputs
