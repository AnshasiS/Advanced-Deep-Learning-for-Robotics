<p align="center"> <img src="https://media.giphy.com/media/PRVDslxfTmwXkLinrk/giphy.gif"></p>
<h1 align="center"> Advanced Deep Learning Robotics (WS21/22) </h1>
<h3 align="center">Instructor: Berthold Bäuml </h3>
<h3 align="center">Tutor: Johannes Tenhumberg</h3>



## 📦 Tech Stack

<div align="center">
  
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Python-yellow?style=for-the-badge&logo=python&logoColor=white)](https://jupyter.org/try)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter%20Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=orange)](https://jupyter.org/try)
[![Made with Docker](https://img.shields.io/badge/Made%20with-Docker-blue?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
<br><br>
</div>

---
<br>

## 🏁 Quick Start

This repository acts as a central hub for the code development by `TEAM_ID 11` for the course **"Advanced Deep Learning in Robotics"**.

#### 🎯 Objective of the Project
The main objective of the project is to implement an algorithm to learn from experience for faster(time-efficient) motion planning, for a motion task, with respect to the classical optimization-based planning approach.

#### 🔭 Technical Outline
The general goal of the project is to implement a deep learning solution to generate experiences on known world configurations based on an initial guess, and then using the experiences for faster decision making in motion planning. We ought to investigate multiple models and approaches for the above mentioned task and then experimenting with different tweaks here and there, to find the best solution. After sufficient generation of experiences, we want to test our results in the setup and compare its performance with the previous solution (Only optimized path approach). 
<br>
If time permits, we want to generate various experiences for the same initial guess and save the best path.

#### 🧑‍🤝‍🧑 Team Members
* Tabdar Khan Bashir
* Sabeeh Musharraf
* Said Anshasi

---
<br>

## 🔧 Usage

#### Pre-requisites:

- Docker and docker-compose must be installed
- An account on hub.docker.com would save you from unforeseen errors
- Generate and save your Personal access token with you (This is used as password in the terminal). [See this for reference](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
#### Steps:

1. Clone the repository using `git clone https://github.com/tabdar-khan/adlr_team_11.git`
2. Go inside the the directory usind `cd` command.
3. Copy the db file i.e. `SingleSphere02.db` inside the repository.
4. Run `docker login` inside the terminal and enter your hub.docker.com credentials.
5. Run `docker-compose up` in the terminal to pull the images and, create & run a docker container. (This might take some time)
6. After the container is created, go to your browser and enter `http://localhost:8888` into the address bar.


---
<br>

## 📋 Git Workflow
**Note: Please adhere to these rules so that we all are on the same page and there are no hickup in anyone's work**

- Create your own branch using `git checkout -b <your_branch_name>`. <your_branch_name> should be your github username.
- Work and commit changes in your own branch and please do not use the `main` branch.
- When need be, the branches will be merged inside the master branch.

---
<br>
<h1 align="center"> 🥳🎉🎆🎈Happy Coding Folks! 🎈🎆🎉🥳 </h1>
<p align="center"><img src="https://media.giphy.com/media/RbDKaczqWovIugyJmW/giphy.gif"/></p>
