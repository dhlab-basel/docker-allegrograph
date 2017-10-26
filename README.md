# docker-allegrograph

Unofficial AllegroGraph Server Image from Franz: https://franz.com

This repository contains a docker image for running AllegroGraph Server 6 on the latest CentOS.

# Build

To build the image, execute the following command:

```
docker build -t dhlabbbasel/agraph .
```

# Run

Run the following command to start the Docker container:

```
docker run --rm -it -p 10000-10035:10000-10035 --shm-size 1g --name agraph dhlabbasel/agraph
```

Access the AllegroGraph WebView in your browser: http://localhost:10035/

Log in using the default superuser account: username test / password xyzzy.

Creator
This repository is provided and maintained by DHLab Basel.


