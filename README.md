# docker-for-vapor

Vapor 3 base image based on Swift 4.2.

## Usage

This is base build. Maybe you want to make your own Dockerfile.

```bash
docker run --name vapor-app -v <vapor_project_dir>:/app pohhen/vapor:<tag>
````

Note! Volume will override your host folder '.build' folder with the one build inside cotainer.
