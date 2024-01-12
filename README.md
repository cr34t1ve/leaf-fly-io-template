# Leaf Fly.io Template

A basic template for deploying leaf apps on [fly.io](https://fly.io).

## File Structure

The project's file structure is as follows:

```text
/
├── .fly/
│   └── scripts/
│   └── entrypoint.sh
├── docker/
├── .dockerignore
├── .htaccess
├── composer.json
├── composer.lock
├── Dockerfile
├── fly.toml
├── index.php
├── README.md
├── welcome.html
```

The difference between this and a regular leaf app is the addition of the fly config files.

## Usage

Initialize your Leaf app on [fly.io](https://fly.io).

```bash
$ fly launch
```

Now deploy the app

```bash
$ fly deploy
```

Done!

🍁 Happy Garderning
