<!-- markdownlint-disable MD030 -->

# Flowise - LangchainJS UI

<a href="https://github.com/FlowiseAI/Flowise">
<img width="100%" src="https://github.com/FlowiseAI/Flowise/blob/main/images/flowise.gif?raw=true"></a>

Drag & drop UI to build your customized LLM flow using [LangchainJS](https://github.com/hwchase17/langchainjs)

## 🐳 Docker

1. Go to `docker` folder at the root of the project
2. Create `.env` file and specify the `PORT` (refer to `.env.example`)
3. `docker-compose up -d`
4. Open [http://localhost:3000](http://localhost:3000)
5. You can bring the containers down by `docker-compose stop`

## 👨‍💻 Developers

Flowise has 3 different modules in a single mono repository.

-   `server`: Node backend to serve API logics
-   `ui`: React frontend
-   `components`: Langchain components

### Prerequisite

-   Install Yarn
    ```bash
    npm i -g yarn
    ```

### Setup

1. Clone the repository

    ```bash
    git clone https://github.com/FlowiseAI/Flowise.git
    ```

2. Go into repository folder

    ```bash
    cd Flowise
    ```

3. Install all dependencies of all modules:

    ```bash
    yarn install
    ```

4. Build all the code:

    ```bash
    yarn build
    ```

5. Start the app:

    ```bash
    yarn start
    ```

    You can now access the app on [http://localhost:3000](http://localhost:3000)

6. For development build:

    ```bash
    yarn dev
    ```

    Any code changes will reload the app automatically on [http://localhost:8080](http://localhost:8080)

## 📄 License

Source code in this repository is made available under the [MIT License](LICENSE.md).
