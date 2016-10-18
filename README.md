# ArchitectNow.Boilerplate.Angular2
This repo contains a boilerplate Angular2 project used by ArchitectNow to kickstart specific client projects.  This code is also used in various presentations and demonstrations.

# Prerequisites
- [Node](https://nodejs.org/en/download/current/) (version >= 6)

# How to Install 
```bash
# Note: If on windows, open command line as administrator
# Clone this repo
git clone --depth=1 https://github.com/ArchitectNow/ArchitectNow.Boilerplate.Angular2
# Navigate to the frontend folder contaning the `package.json`
cd ArchitectNow.Boilerplate.Angular2/src/ArchitectNow.Boilerplate.Angular2
# install webpack and other frontend tools via npm
npm install
npm start

# if npm start fails, rebuild the project and try again
npm rebuild
npm start
```

# How to Rename Project (windows only)
1. Navigate to scripts folder
2. Run PrepareProject.bat
3. Enter the desired namespace
4. Delete the scripts folder 

# TODO:
 - add bash option for renaming project
