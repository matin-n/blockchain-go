# Blockchain in Golang for COMP424
## Code your own blockchain in less than 200 lines of Go!

### Deployment steps:
- `git clone https://github.com/matin-n/blockchain-go`
- navigate to this directory and rename the example file `mv example.env .env`
- `go run main.go`
- open a web browser and visit `http://localhost:8080/`
- to write new blocks, send a `POST` request (I like to use [Postman](https://www.getpostman.com/apps)) to `http://localhost:8080/` with a JSON payload with `Data` as the key and an string as the value. For example:
```
{"Data":"Hello World"}
```
- Send as many requests as you like and refresh your browser to see your blocks grow! 

### Screenshot

![screen](https://user-images.githubusercontent.com/40713017/43980872-96efb3f4-9ca4-11e8-81c5-fa290ce243c0.png)
