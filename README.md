`docker run -p 8000:3000 -v /usr/src/app/node_modules -v $(pwd):/usr/src/app 4789212025af`

```
=> map the react server 3000 port to 8000 in my local dev:

docker run -p 8000:3000 

=> use the node modules in the container, since we don't have them locally:

-v /usr/src/app/node_modules

=> use the files locally to serve from the container:

-v $(pwd):/usr/src/app 4789212025af
```