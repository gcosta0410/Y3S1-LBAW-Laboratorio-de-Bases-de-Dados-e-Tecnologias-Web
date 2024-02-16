# Installation

Follow [README_lbaw](README_lbaw.md) to setup the environment

Build the docker image:
`docker build -t lbaw2225 .`

Run to launch the website:
`docker run -it -p 8000:80 --name=lbaw2225 -e DB_DATABASE="lbaw2225" -e DB_SCHEMA="lbaw2225" -e DB_USERNAME="lbaw2225" -e DB_PASSWORD="Mfabfwyw" lbaw2225`