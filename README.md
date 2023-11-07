# whoosin-
web app for finding everyones availability for motives


## Tech stack

Frontend:
- Typescript
- Next
- Tailwindcss
- Storybooks
- Cypress

Backend: 
- Express
- Firebase
- MySQL

## Setting up development server

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