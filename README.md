<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/bogdaniordan/joblish-bogdaniordan">
    <img src="https://images-platform.99static.com/qOrmQjoiLt3NRXu-vC7cbU2qz-Y=/118x118:1064x1064/500x500/top/smart/99designs-contests-attachments/105/105232/attachment_105232267" alt="Logo" width="300">
  </a>

  <h3 align="center">Joblish</h3>

  <p align="center">
    An awesome job platform made for job hunters and companies.
    <br />
    <a href="https://github.com/bogdaniordan/joblish-bogdaniordan"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/bogdaniordan/joblish-bogdaniordan">View Demo</a>
    ·
    <a href="https://github.com/bogdaniordan/joblish-bogdaniordan/issues">Report Bug</a>
    ·
    <a href="https://github.com/bogdaniordan/joblish-bogdaniordan/issues">Request Feature</a>
  </p>



<!-- TABLE OF CONTENTS -->
<details open="open">
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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This is an useful job web app made for job seekers where they can search, browse and apply to various jobs. There is also a company app where companies post jobs and hire people.

Here's why:
* Job seekers can browse and apply to various jobs from different sectors.
* Job seekers can build their profile with details and job prefernces.
* Job seekers can manage their applications and accept/deny job offers.
* Companies get a dashboard where they can search candidates and post new jobs.
* Companies can manage their applicants and offer job to succesful applicants.

### Built With

#### Backend
* [Spring Boot (JPA)](https://spring.io/projects/spring-boot)
* [Lombok](https://projectlombok.org/)
* [PostgreSQL](https://www.postgresql.org/docs/13/app-psql.html)

#### Frontend
* [React](https://reactjs.org/)
* [React-Bootstrap](https://react-bootstrap.github.io/)
* [npm](https://www.npmjs.com/)

#### Version control
* [Github](https://www.gtihub.com/)

#### Project Management
* [Trello](https://www.atlassian.com/software/jira?&aceid=&adposition=&adgroup=89541897982&campaign=9124878150&creative=415542514747&device=c&keyword=jira&matchtype=e&network=g&placement=&ds_kids=p51242161283&ds_e=GOOGLE&ds_eid=700000001558501&ds_e1=GOOGLE&gclid=Cj0KCQiAnKeCBhDPARIsAFDTLTIUjm6m9LQssN_d15V_dYNqPiWaS_df09mdcnHPj-QkqTKrZfAjB6kaAhdEEALw_wcB&gclsrc=aw.ds)



<!-- GETTING STARTED -->
## Getting Started

This application can be tested by installing all prerequisites, clone both the back end and the client app, running them and enjoy!

### Prerequisites

All prerequisites must be installed, accordingly to the technologies used in this project, for example:
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

* Backend

1. Clone the repo
   ```sh
   git clone https://github.com/bogdaniordan/joblish-backend
   ```
2. Run the server

* Frontend

1. Clone the job seeker and company repos
   ```sh
   git clone https://github.com/bogdaniordan/joblish-frontend
   git clone https://github.com/bogdaniordan/joblish-companies-frontend
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run the app
   ```
    npm start
   ```

<!-- USAGE EXAMPLES -->
## Usage

Further I will shortly name, describe and visualize some main features of the app.
### Job seeker application
* Future employees can browse and apply to various jobs.

![Screenshot from 2021-10-21 12-51-20](https://user-images.githubusercontent.com/72221647/138556378-6b2974d4-4dc3-4c61-9d1b-e76fd1acb43c.png)
![Screenshot from 2021-10-21 12-58-05](https://user-images.githubusercontent.com/72221647/138556402-5e14254a-2561-4702-b870-c31a82c7f3dd.png)
![Screenshot from 2021-10-21 16-04-11](https://user-images.githubusercontent.com/72221647/138556421-ea13cc44-7a18-4efc-95e3-26621cb4162c.png)

* Job hunters can manage their profile, save favorite jobs, add job preferences and check listed companies.

![Screenshot from 2021-10-21 16-04-20](https://user-images.githubusercontent.com/72221647/138556477-7f26f64a-bf37-430d-aabb-87f848b9fe4c.png)
![Screenshot from 2021-10-21 16-04-27](https://user-images.githubusercontent.com/72221647/138556490-a58e62bc-17c9-4fcf-b7f6-7218ed71357e.png)
![Screenshot from 2021-10-21 16-04-59](https://user-images.githubusercontent.com/72221647/138556500-9ef0dc37-06bb-4938-a6ce-f21e3c509658.png)

### Companies application

* Companies have a dashboard where they can accept/reject applications, search for new ones and edit/remove jobs.

![Screenshot from 2021-10-21 16-06-06](https://user-images.githubusercontent.com/72221647/138556615-a714c89c-5a4b-4384-93dd-0cd260db2a75.png)
![Screenshot from 2021-10-21 16-06-15](https://user-images.githubusercontent.com/72221647/138556623-6e7701c4-2118-4a00-90e3-06c262e349a1.png)
![Screenshot from 2021-10-21 16-06-27](https://user-images.githubusercontent.com/72221647/138556640-346d937d-2e0c-4ea7-b093-272541983cdd.png)

<!-- ROADMAP -->
## Roadmap

The project development took place through 8 Agile iterations, each iteration taking 5 days. A short complete roadmap bellow:

![agile-logo](https://user-images.githubusercontent.com/72221647/138440913-f67be820-c3a8-46d2-a35c-1f847acb2c48.png)

* Sprint 1: Built the front end for the job seeker app (jobs search, profile, applications) 
* Sprint 2: Added the backend functionality (database objects, services, controllers, security)
* Sprint 3: Started building the companies dashboard (browse applicants, deny/accept applicants, add/edit jobs)
* Sprint 4: Finished building all the remaining features, debugging, added CSS stlying 

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Bogdan Iordan - [@My Github](https://github.com/bogdaniordan) [@My LinkedIn](https://www.linkedin.com/in/bogdan-iordan/) - bogdan.iordan47@gmail.com


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [Codecool Romania :thumbsup:](https://codecool.com/ro/)
* [React Documentation](https://reactjs.org/)
* [Spring Documentation](https://docs.spring.io/)


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/badge/Contributers-2-brightgreen
[contributors-url]: https://github.com/marius-ceobanu/Poke-Battlez-Frontend/graphs/contributors
[forks-shield]: https://img.shields.io/badge/Forks-0-blue
[forks-url]: https://github.com/marius-ceobanu/Poke-Battlez-Frontend/network/members
[stars-shield]: https://img.shields.io/badge/Stars-2-blue
[stars-url]: https://github.com/marius-ceobanu/Poke-Battlez-Frontend/stargazers
[issues-shield]: https://img.shields.io/github/issues/marius-ceobanu/Poke-Battlez-Frontend
[issues-url]: https://github.com/marius-ceobanu/Poke-Battlez-Frontend/issues
[linkedin-shield]: https://img.shields.io/twitter/url?label=Linkedin%20-%20Marius&logo=LINKEDIN&style=social&url=https%3A%2F%2Fwww.linkedin.com%2Fin%2Fmarius-ciprian-ceobanu-3431157b
[linkedin-marius-url]: https://www.linkedin.com/in/marius-ciprian-ceobanu-3431157b
[github-marius-shield]: https://img.shields.io/twitter/url?label=GitHub%20-%20Marius&logo=Github&style=social&url=https%3A%2F%2Fgithub.com%2Fmarius-ceobanu
[github-marius-url]: https://github.com/marius-ceobanu
[github-razvan-shield]: https://img.shields.io/twitter/url?label=GitHub%20-%20Razvan&logo=Github&style=social&url=https%3A%2F%2Fgithub.com%2Frgrigore
[github-razvan-url]: https://github.com/rgrigore
[chat-png]: doc_images/chat.png
[register-png]: doc_images/register.png
[login-png]: doc_images/login.png
[login-gif]: doc_images/login.gif
[PM-gif]: doc_images/PM.gif
[team-gif]: doc_images/team.gif
[challenge-gif]: doc_images/challenge.gif
[battle-gif]: doc_images/battle.gif
[agile]: doc_images/agile-logo.png
