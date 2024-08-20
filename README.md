# Satiscribble-Main
This is the main repository for Satiscribble. It contains all the submodules for each microservice used in Satiscribble.

# Intialisation
To intialise each submodules, run the following function in your terminal.
```
git submodule update --init --recursive
```

To update each submodules after updates have been made to the submodule code base, you may run the following.
```
git submodule update --remote
```

To push changes to the submodules if they were edited, simply run the following.
```
cd path/to/submodule
git add <filenames>
git commit -m "commit message"
git push origin <branch name>
```

# Setup
Each submodule will be hosted on Docker. Please look into the READMEs of each microservice for setup instructions and more details.

# Contributors✨
Special thanks to the following


