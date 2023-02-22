# Week 1 — App Containerization

## Add env vars to the container
- Add the environment vars to your local develoment environment aka (your command line interface)
- Pipe the environment variables from your CLI to The Container using the following command
    - ``` docker run --rm -p 4567:4567 -it -e FRONTEND_URL -e BACKEND_URL backend-flask```
    - or exceplicitly specify them as follows:``` docker run --rm -p 4567:4567 -it -e FRONTEND_URL='*' -e BACKEND_URL='*' backend-flask```
