# TiketFilm.com [DEPRECATED API COMPFEST]

TiketFilm.com is a website with Booking Film Ticket System topic. This website build using React js, Spring Boot, and MySQL tech stack.

## Requirements
<ul>
  <li>Visual Studio Code (IDE)</li>
  <li>IntellijIDEA (IDE)</li>
  <li>Java version 17</li>
  <li>Ngrok</li>
  <li>Internet Connection</li>
</ul>

## Installation

Clone the repository in this [link](https://github.com/orgs/TiketFilm/repositories) .

Clone Project Spring Boot
```bash
https://github.com/TiketFilm/TiketFilmSecurityAPI.git
```

</br>

Clone Project React
```bash
https://github.com/TiketFilm/TiketFilmClient.git
```

</br>

## Adjusment
After cloning the project, to run the project, we need some adjusment for the Spring Boot public API URL. Because we use ngrok, so the public url change overtime.
<ul>
  <li>Download ngrok: https://ngrok.com/download</li>
  <li>Run the application</li>
  <li>Write the code below into the console</li>

  ```
  ngrok http <port-number>
  ```
  <li>Copy the new url that shown</li>
  <li>Change the the base url in the react application the AxiosConfig.js file</li>
  
  ![image](https://github.com/TiketFilm/.github/assets/87352987/e4586581-dba0-4cad-8b81-0ab06b84f204)

</ul>

</br>

## Run React Project
```bash
# install npm
npm install

# start the npm
npm start

```

## Run Spring Boot API
After cloning and extract the project, you just need to run the application, and then the service will started.


## Preview

![image](https://github.com/TiketFilm/.github/assets/87352987/e4eb7ae7-3a8a-4e66-a4e7-e27335751d07)


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
