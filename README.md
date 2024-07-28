# GameFiesta

GameFiesta is a video game discovery web app that helps you find new and interesting games to play. With GameFiesta, you can search for games by platform, genre, and more. You can also view details about a game, such as its description, release date, and screenshots.

## 📸 Screenshots

|                                                  |                                                  |
| :----------------------------------------------: | :----------------------------------------------: |
| ![Screenshot 6](https://i.imgur.com/Yctj1rY.png) | ![Screenshot 5](https://i.imgur.com/kD6YAAv.png) |
| ![Screenshot 3](https://i.imgur.com/FzFkZbS.png) | ![Screenshot 4](https://i.imgur.com/xhBdGEg.png) |
| ![Screenshot 2](https://i.imgur.com/pvJnO0p.png) | ![Screenshot 1](https://i.imgur.com/UlEGkUD.png) |

## Getting Started

To get started with GameFiesta, follow these steps:

1. Clone this repository to your local machine.
2. Run `npm install` to install the required dependencies.
3. Get a RAWG API key at https://rawg.io/apidocs. You'll have to create an account first.
4. Paste the API key in **.env.local** file for your development environment. For production, use a **.env** file instead.
5. Run `npm run dev` to start the web server.
6. Open http://localhost:5173/ in your browser. Walla! You're ready to start using GameFiesta.

Alternatively, you can run the application using Docker run the below commands:

1. Open and start the Docker Application on your computer.
2. Login into docker by running, `docker login` command and ensure the login is successful.
3. Build the Docker Image:

    ```bash
    docker build -t game-fiesta:1.0 .
    ```

4. Run the Docker Container:

    ```bash
    docker run -p 5173:5173 -d game-fiesta:1.0
    ```

Alternatively, you can pull the docker image (from docker hub) and simply run, without having to build or clone it.

1. Pull the Docker Image:

    ```bash
    docker pull habibo1234/game-fiesta:1.0
    ```

2. Run the Docker Image:

    ```bash
    docker run -p 5173:5173 -d habibo1234/game-fiesta:1.0
    ```

## Links

-   Project Repo URL : [github.com/oyerohabib/game-fiesta](https://github.com/oyerohabib/game-fiesta)
-   Project Live URL : [gamefiesta.netlify.app/](https://gamefiesta.netlify.app/)

## Process

1. First create a static mockup of the website using Chakra Ui.
2. Then create a dynamic mockup of the website using React Query and Zustand.
3. Then create a responsive mockup of the website using Chakra Ui media query.

### Built with

-   Chakra-Ui
-   React Query
-   Zustand
-   Vite
-   Typescript
-   Mobile-first workflow
-   Semantic HTML5 markup

## What I learned

During this project, i learned how to use Chakra-Ui and how to use rawg-io api. I also learned how to use React Query for client-side caching, Zustand for state-management and Vite for packager bundler. Also strengthens my knowledge of React Router v6, Custom Hooks and Typescript.

## Useful resources

-   [Chakra-Ui](https://chakra-ui.com/) - Chakra-Ui documentation
-   [Rawg-Io](https://rawg.io/apidocs) - Rawg-Io documentation
-   [Zustand](https://docs.pmnd.rs/zustand/getting-started/introduction) - Zustand documentation
-   [React Query](https://tanstack.com/query/latest/docs/framework/react/overview) - React Query documentation

## Contributing to project

Thank you for considering contributing to the GameFiesta App! We welcome contributions from the community to help improve and grow the project.

Please note that this project adheres to the [Contributor Covenant Code of Conduct](CONTRIBUTING.md). By participating, you are expected to uphold this code. Please report any unacceptable behavior.

## License

This project is licensed under the [MIT License](LICENSE).
