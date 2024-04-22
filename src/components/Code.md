```yml
project:
   name: zerops-astro

  services:
   - hostname: astronode
    type: nodejs@18
    buildFromGit: https://github.com/fxck/zerops-astro-static
    ports:
      - port: 3000
        httpSupport: true
    enableSubdomainAccess: true
    minContainers: 1
```
