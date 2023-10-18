# Weather APP

Application to check the weather forecast based on your current location.

## Demo

![treeview do projeto](https://github.com//denis0612/weather-app/blob/main/assets/demo.jpg?raw=true)

Para testar o aplicativo no device, basta acessar o link:
https://expo.io/@matsvilas/projects/weather-app

## Como Rodar o projeto

Run the following commands:
```
$ git clone https://github.com/denis0612/weather-app
$ cd weather-app
$ yarn ou npm install
$ yarn start
```

## Project organization

The Project was organized thinking about the scalability of possible tools and features.

![treeview do projeto](https://github.com//denis0612/weather-app/blob/main/assets/treeview.png?raw=true)

1. The `views` folder will store the application routes and all dependent files that are not repeated elsewhere.
2. The `components` folder will store all visual elements that are repeated between `views`.
3. The `api` folder stores the entire communication layer between the application and information sources.
4. The `hooks` folder stores customHooks, which are functions that use and trigger the react life cycle.
5. The `navigation` folder contains the application's routing logic.

## App State

Developed with possible user flow in mind, the `appState` Custom Hook shows the current state of the application, in case the user has refused to use Location. And so when he returns to the application, when he releases access, he will reload the flow.

## Next steps

- Unit testing: To guarantee the integrity of the components and prevent the application from breaking in the event of significant changes to the API. The test will serve to prevent these possible errors.
- Animation: Use animations to change the base colors of the application according to the period being used. And add animations based on the weather forecast.
- Styles: Add a property to the Text called `variant` that will define which font is being used.

## Layout Reference

- Layout link: https://www.figma.com/community/file/885501292477669105/Weather-Forecast-App
