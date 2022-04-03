1. Clone into user directory ( or somewhere else if u wish)
2. `chmod 700 doo`
3. add to bashrc or zshrc `alias doo="~/doo/doo"`

### USAGE

Create doo file in your docker project:

```
container-name:%%THE DOCKER CONTAINER NAME%%
start:THE COMMAND U WISH eg. docker compose up CONTAINERNAME
```

Go to directory and start the container:

`doo start`

Now you can use the exec commands:

`doo npm install`
