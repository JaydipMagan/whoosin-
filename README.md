# whoosin-
web app for finding everyones availability for motives

## Contents 

1. [Tech stack](#techstack)
1. [Setup](#setup)

## Tech stack <a name="introduction"></a>

Frontend:
- Typescript
- Next
- chakra
- Storybooks
- Cypress

Backend: 
- Express
- Firebase
- MySQL

## Setting up development server <a name="setup"></a>

For MacOS:

1. Install [Docker](https://www.docker.com/get-started/).

1. Change into the project directory 

    `cd whoosin`

1. Build the docker image

    ```
    docker build -t whoosin-dev
    ```

1. Run the docker container

    ```
    docker run -p 3000:3000 whoosin-dev
    ```

1. Open [localhost:3000](localhost:3000) on your browser.

Storybook:

To run storybooks locally build the docker image and run.

1. Build the docker image
    ```
    docker build -t whoosin-sb -f ./docker-storybook
    ```

1. Run the docker container
    ```
    docker run -p 3000:3000 whoosin-sb
    ```
