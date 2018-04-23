# front, back, devops with Docker

This is a starter kit for developping both front and back with docker.

The aim of this repo is to help devlopping being at-first implied in a devops chain : the sooner you start in a machine-as-a code env, the faster your app will deploy.

Some stack has to be choosen here, even the components may be changed:
- proxy : nginx - could be Apache as well
- frontend : Vue.js - could be any npm framework
- backend : Python + FlaskRestPlus - could by any api framework

This starter kit is making something quite neutral: a drag & drop file system like a Dropbox. 
It should take few minutes to modify it to fit your own project.

# Install


Just clone the project :

```
git clone https://github.com/entrepreneur-interet-general/vue-python-starter-kit.git
```

# Start

Run dev environnement :

```
cd vue-python-starter-kit
make dev
```

then go to : `http://localhost`

# Stop

To stop the docker from running :
```
make dev-stop
```

### Note
This project is derived from the matchID project
