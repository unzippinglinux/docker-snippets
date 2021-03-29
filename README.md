# docker-snippets
Snippets relevent to docker.

## to fetch data from dockerhub
`FROM python:latest`
## copy from to(the docker image). Basically importing files to the image.
`COPY main.py /`
## command to run the app
`CMD [ "python", "./main.py" ]`
