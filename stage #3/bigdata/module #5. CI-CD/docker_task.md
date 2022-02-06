## Docker Basics

#### Docker Topics

TBD:  add topics 
    
__Links:__
TBD: List links

## Task

__Deadline:__ 3 working days.

__Disclaimer:__ In case of any questions related to the task please immediately contact any of the mentors to avoid misunderstanding.

#### Legend
After successful implementation of the task you should have an application from the modules #3 and #4 up and running in Docker containers.

#### Workplace Setup
- Setup [Docker Desktop](https://www.docker.com/products/docker-desktop). 
- If you are using Windows 10 and higher, consider using WSL 2 as backend, otherwise use Hyper-V backend. For more details, refer to the manual [Install Docker Desktop on Windows
](https://docs.docker.com/desktop/windows/install/).


#### Requirements
Create a multi-container Docker application: 
1. Write a Dockerfile to create a container image, which should be able to:
    - Build the project created in the modules #3 and #4 with maven;
    - Run your application for a sample month range and any passed API.
    - Arguments for the java application should be passed as environment variables.
    
2. Create a multi-container Docker application using Docker Compose;
3. Define services for PostgreSQL and java application in your docker-compose.yml file.
  
#### Required technologies to be used
- Docker CLI;
- Consider using lightweight Java images (e.g. -slim, -alpine).

#### Acceptance
- Reviewee should demonstrate launch of the containers and Java application execution.
- Reviewee should demonstrate PostgreSQL database filled with the data from API.
