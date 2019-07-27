# nodebots-hackaton

Simple people counter for events.  

[Nodebots Day Counter Video](https://www.youtube.com/watch?v=n3qfNKKpsBc)  

![NodeBots Day Counter](img/nodebots-day-counter.png)

## Running the server  

```bash
npm i
npm start
```

## Running the frontend separately  

```bash
cd frontend
http-server
```

## Exposing to the world  

```bash
ssh -R 80:localhost:3000 nodecounter@ssh.localhost.run
```

## Public Url  

https://nodecounter.localhost.run

