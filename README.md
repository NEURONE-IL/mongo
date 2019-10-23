# MongoDB Docker script for NEURONE

Created by Daniel Gacitúa

Based on [Alex Bejan's blog post](http://blog.bejanalex.com/2017/03/running-mongodb-in-a-docker-container-with-authentication/)

This Docker script deploys a MongoDB 3.4 image with authentication. Originally created for NEURONE, but released as a standalone script for any project.

## Usage

1. Download this image from Docker Hub
2. This image has the following Environment Variables for customizing auth credentials, set them when generating a new container based on this image

| Environment Variable           | Default Value     |
|--------------------------------|-------------------|
| `MONGODB_ADMIN_USER`           | `admin`           |
| `MONGODB_ADMIN_PASS`           | `4dmInP4ssw0rd`   |
| `MONGODB_APPLICATION_DATABASE` | `admin`           |
| `MONGODB_APPLICATION_USER`     | `restapiuser`     |
| `MONGODB_APPLICATION_PASS`     | `r3sT4pIp4ssw0rd` |

## License

This script is released under MIT License.

MongoDB and other dependencies are released under their own licenses.