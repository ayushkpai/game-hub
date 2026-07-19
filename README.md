# Game hub

- Open your terminal and clone this repository
    
    First make sure you have a ssh key if you dont have go to my dotfiles repository and follow the instructions

    ```
    git clone git@github.com:ayushkpai/game-hub.git
    ```

- Next install type script and node.js

    Also documented in dotfiles

- Api key

    You need an rawg api key for this project for ferching the games so go to [rawg website](https://rawg.io) and create an api key

- Add the key

    ```
    echo <your_rawg_api_key> >> .env
    ```

- To run the project

    ```
    npm run dev
    ```
