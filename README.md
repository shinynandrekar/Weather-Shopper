Sample Dockerized Cypress Tests for weathershopper.pythonanywhere.com

Prerequisites

Docker Node.js and npm

Installation and Usage
Clone the repository: git clone https://github.com/shinynandrekar/Weather-Shopper.git

Change directory to the project root: cd Weather-Shopper

Install dependencies: npm install

To run the Cypress tests, open a new terminal window and run: npm run cypress:run

Docker Usage
Build the docker image, by running the following command: docker build -t weathershopper .

To run the Cypress tests inside the docker instance, run: docker run -it --rm -v ${PWD}:/app -v /dev/shm:/dev/shm weathershopper
