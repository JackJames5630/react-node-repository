# Clinic Managemnt 1.0
## have changed 
> System Management for Doctors

This is a React and Express stack application with Mysql data base .It is a small systems to manage patients with their appointments with the doctor and make prescription of them.

## Frontend

there is config file to api into utils folder `api.js`, to contact with backend.

## Backend 

there is config file to data base into config folder `db.js`, to contact data base with api.

# Quick Start 🚀

### Add a config.js file in config folder with the following

```
module.exports = {
  username: [your username],
  password: [your password],
  database: [your data base],
  host: 'localhost',
  dialect: 'mysql',
  jwtSecret: [your secret into jwt],
};
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root


into backend folder
```bash
npm run server
```

into frontend folder
```bash
npm start
```

### Build for production

```bash
cd client
npm run build
```

### Test production before deploy

After running a build in the client 👆, cd into the root of the project.  
And run...

Linux/Unix 
```bash
NODE_ENV=production node server.js
```
Windows Cmd Prompt or Powershell 
```bash
$env:NODE_ENV="production"
node server.js
```
