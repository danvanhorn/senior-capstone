# Senior Capstone
Master repository for senior capstone docs and source code for 2018-19.

### Initializing the Repository
If this is the first time pulling the code to a machine, run the following command to initialize the submodules:
```
git submodule update --init --recursive
```
If you are just updating all of the submodules, use the following command to get the latest from the remote repositories for the submodules:
```
git submodule update --recursive --remote
```

### Running the application

1. Run **brewhops-api** in one terminal.
1. Run **brewhops-app** in another terminal.
1. Open a brower at the url speicifed in the brewhops-app terminal output.  Most likely `localhost:8080`.
