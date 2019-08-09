# Course - Omnistack Week
The best programming technologies, right to the point and the right way.
In the midst of so much information and the amount of tools that come up every day, you need someone to lead you in the right direction.

[Omnistack Week](https://rocketseat.com.br/week-8/aulas)

## Installation
Installation of `NODEJS`
``` sh
$ sudo apt-get install nodejs
```

Installation of `YARN`
``` sh
$ curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
$ echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
$ sudo apt-get update && sudo apt-get install yarn
```

## IDE
Visual Studio Code - [Download](https://code.visualstudio.com/Download)

Download the visual studio code and install in your computer
``` sh
$ dpkg -i code.deb
```

Settings
``` json
{
    "editor.minimap.enabled": false,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "editor.tabSize": 2,
    "editor.fontSize": 14,
    "editor.lineHeight": 24,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "files.autoSave": "off",
    "workbench.colorTheme": "Dracula"
}
```

`Extensions` of visual studio code: 

- [Theme Dracula](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [Rocketseat ReactJS](https://marketplace.visualstudio.com/items?itemName=rocketseat.RocketseatReactJS)
- [Rocketseat React Native](https://marketplace.visualstudio.com/items?itemName=rocketseat.RocketseatReactNative)
- [FiraCode](https://github.com/tonsky/FiraCode)

## Tools
- [INSOMNIA](https://support.insomnia.rest/article/23-installation#ubuntu)
- [MONGODB COMPASS](https://www.mongodb.com/products/compass)

## Database
In this project we will use `mongodb` with `atlas`
- See more: [Mongodb Atlas](https://www.mongodb.com/cloud/atlas)

## Backend

Project Initialization:
- Create a folder named: `backend`
- Just run the command below

``` sh
$ yarn init -y
```
Adding `express` to the `backend` project
``` sh
$ yarn add express
```
Adding `nodemon` to the `backend` project
``` sh
$ yarn add nodemon -D
```
Adding `mongoose` to the `backend` project
``` sh
$ yarn add mongoose
```
Adding `axios` to the `backend` project
``` sh
$ yarn add axios
```
Adding `cors` to the `backend` project
``` sh
$ yarn add cors
```

Running `nodemon` with `yarn`
``` sh
$ yarn dev
```

## Frontend

Project Initialization:
- Just run the command below
``` sh
$ yarn create react-app frontend
$ cd frontend
$ yarn start
```
Adding `express` to the `frontend` project
``` sh
$ yarn add express
```
Adding `react-router-dom` to the `frontend` project
``` sh
$ yarn add react-router-dom
```
Adding `axios` to the `frontend` project
``` sh
$ yarn add axios
```

### About project
See more: [OmniStack 8.0](https://rocketseat.com.br/week-8/aulas)

### Copyright
[Danilo Righetto](https://www.linkedin.com/in/danilo-righetto/)
