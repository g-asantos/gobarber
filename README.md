
<p align="center">
   <img src=".github/logo.svg" width="200" filter="brightness(0.1)"/>
</p>


# GoBarber!

> GoBarber created using ReactJS(web) and React Native(mobile)

<p align="center"><img src=".github/gobarber.gif?raw=true"/></p>




### Installation(web)

Get in the project's path , then install the dependencies with:

```sh
yarn
```

Start it with:

```sh
yarn start
```

### Installation(mobile)

Starting the api:

```sh
docker-compose up -d && yarn && yarn typeorm migration:run && yarn dev:server
```

Starting the web: 

```sh
yarn && yarn start
```

Starting the mobile:


- Android:
```sh
yarn && yarn android
```
- iOS:

```sh
yarn && yarn ios
```

## Author

  **Guilherme Azevedo dos Santos**

* Github: [@g-asantos](https://github.com/g-asantos)
* Linkedin: [@guilherme-azevedo-dos-santos-417a70159](https://www.linkedin.com/in/guilherme-azevedo-dos-santos-417a70159/)

## License

[MIT](https://choosealicense.com/licenses/mit/)