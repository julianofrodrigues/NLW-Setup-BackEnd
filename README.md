<h1 align="center"> 🗓 NLW-Setup-Back-End </h1>

# Project Summary

Back-end of the NLW Setup, project built for construction of housing worksheet.<br>
The front-end is at this repository: https://github.com/julianofrodrigues/NLW-Setup-FrontEnd <br>
The mobile project is in this other repository: https://github.com/julianofrodrigues/NLW-Setup-FrontEnd

## 📁 Project Access
To try it is very simple:<br>
-Clone the repository
```bash
$ git clone https://github.com/julianofrodrigues/NLW-Setup-BackEnd
```
-Rename env.example to .env <br>

-Download the libraries
```bash
$ yarn install
```
Or
```bash
$ npm install
```
-Create Database
```bash
$ npx prisma migrate dev
```
-Run Seeds
```bash
$ npx db seed
```
-View the Database
```bash
$ yarn prisma studio
```
Or
```bash
$ npm prisma studio
```
-Start the Project
```bash
$ yarn dev
```
Or
```bash
$ npm run dev
```
Ready, now just access the routes through Insomnia, Postman or any other of your choice.
## ✔️ Techniques and technologies used
- ``JavaScript``
- ``TypeScript``
- ``Node``
- ``Fastify``
- ``SQLite``
- ``Prisma``
- ``Cors``
- ``Zod``
- ``DayJs``





