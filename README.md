# testssl-docker
testssl.sh plus testssl.sh-webfrontend docker image.

# Usage
To run docker container:

```# docker run -p 8080:80 -d rexcze/testssl-docker ```

Access web interface on http://127.0.0.1:8080/

To access docker image itself with shell run:

```# docker run -it -p 8080:80 --entrypoint /bin/bash rexcze/testssl-docker```

# Used software
This image contains following software:

 - https://github.com/drwetter/testssl.sh/
 - https://github.com/TKCERT/testssl.sh-webfrontend
