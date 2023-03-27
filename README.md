# authenticate with GitHub Container Registry (Windows)
$ winpty docker login ghcr.io

#tag the image
$ docker tag my-java-image:1.0.0 ghcr.io/<your_github_username>/my-java-image:1.0.0

#push it to GitHub Container Registry
$ docker push ghcr.io/<your_github_username>/my-java-image:1.0.0
