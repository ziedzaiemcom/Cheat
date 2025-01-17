# Cheat

Cheatsheets web viewer. Designed to help remind *nix system administrators of options for commands that they use frequently, but not frequently enough to remember.

<img src="https://raw.githubusercontent.com/ziedzaiem/Cheat/main/assets/preview.png" width="300" alt="preview.png" />

## Submodule

```
git submodule update --init --recursive

git submodule update --recursive --remote

```

[Source](https://stackoverflow.com/questions/1030169/pull-latest-changes-for-all-git-submodules)

## Run

Just put this directory contents in any web server.

```
Python 2.x
$ python -m SimpleHTTPServer 8000
Python 3.x
$ python -m http.server 8000
$ python3 -m http.server 8000
```

## Docker

- Github : https://github.com/ziedzaiemcom/Cheat
- Docker Hub : https://hub.docker.com/r/ziedzaiemcom/cheat

You can use [Dive](https://github.com/wagoodman/dive) to inspect Docker image contents.

### Run

```
docker compose build
docker compose up -d
```

### Push to Docker Hub

```
docker tag cheat-cheat:latest ziedzaiemcom/cheat:0.0.2
docker login -u ziedzaiemcom
docker push ziedzaiemcom/cheat:0.0.2
```

### Pull From Docker Hub

```
docker pull ziedzaiemcom/cheat:0.0.Z

```

Exposed Ports  :
- 80

## Credits

Inspired from [cheat](https://github.com/cheat/cheat). Uses community-sourced cheatsheets provided by [cheatsheets](https://github.com/cheat/cheatsheets)

## Licence

MIT.