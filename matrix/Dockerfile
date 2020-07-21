FROM scratch

LABEL maintainer="munka.simon@gmail.com>"
LABEL description="simulates Matrix screen"

ADD alpine-minirootfs-3.12.0-x86_64.tar.gz / 

RUN apk add cmatrix

CMD [ "cmatrix" ]
