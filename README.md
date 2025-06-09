https://github.com/sonlemin/learn-cicd-starter/actions/workflows/ci.yml/badge.svg
!Images(https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.svgrepo.com%2Fsvg%2F13679%2Fsuccess&psig=AOvVaw2uTjn5qsbTyr1sXMXBLTbz&ust=1749546433857000&source=images&cd=vfe&opi=89978449&ved=0CBcQjhxqFwoTCOCMhb3-440DFQAAAAAdAAAAABAE)
# learn-cicd-starter (Notely)

This repo contains the starter code for the "Notely" application for the "Learn CICD" course on [Boot.dev](https://boot.dev).

## Local Development

Make sure you're on Go version 1.22+.

Create a `.env` file in the root of the project with the following contents:

```bash
PORT="8080"
```

Run the server:

```bash
go build -o notely && ./notely
```

*This starts the server in non-database mode.* It will serve a simple webpage at `http://localhost:8080`.

You do *not* need to set up a database or any interactivity on the webpage yet. Instructions for that will come later in the course!
"sonlemin's version of Boot.dev's Notely app."
