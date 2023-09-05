# WeatherWiseNet
## Project Overview
This project provides a user interface to view the Reflectivity plots for various regions in the US for a given Date and Time. It allows users to login with their Google account and search history for each user is maintained for faster data retrieval of recent searches. It makes use of distributed systems architecture containerized using Docker dealing with Micro-services written in different programming languages.
# Tech Stack Used:
1. Front-End: React.JS
2. Back-End: Java, Python, JavaScript (Node.js)
3. Database: MongoDB, PostgreSQL, Redis

# Napkin Diagram
![Napkin Diagram](https://github.com/RahulUbale/Epsilon/assets/68568128/ffd14305-675e-4c14-a780-3ad0d525bbde)

# Architecture Diagram
![image](https://github.com/RahulUbale/Epsilon/assets/68568128/cc272f1c-d395-457e-a923-92f73b23cde3)

# Steps to Run the Project:
1. All dependencies stated above should be installed before performing the below steps.

2. Create a folder named "epsilon 1.1".

3. Open a terminal in the folder created above and run the following commands:
   - Run `git clone https://github.com/airavata-courses/epsilon.git docker`
   - Run `cd docker`
   - Run `git checkout homework1-release-docker-comp`

4. Open Docker Desktop.

5. Run `docker-compose up --build -d reactui`.

6. For Mac & Linux:
   - Run `sh migrate.sh`.

7. For Windows:
   - Open Git Bash in the same folder.
   - Run `sh migrate.sh`.

Note: React UI may take some time to load all resources from the Docker image. Please wait for 5 minutes after this step before proceeding to the next step.

8. After completing the above steps, click [here](link) to use Epsilon.


# Dependencies needed to clone the entire project
1. MongoDB - Running on Port 27017
2. Conda - https://anaconda.org/conda-forge/arm_pyart
3. PostgreSQL - Running on Port 5432
4. Redis - Running on Port 6379


