# Fdggs
`Fdggs` is the short name of `From database generate go struct`.
Fdggs generates a go compatible struct type with the required column names, data types, and annotations just fill in the database information in the web UI. Making go web develop very easy by saving a lot of time writing structure.`Fdggs`is based/inspired by the work of Seth Shelnutt's db2struct, and Db2Struct is based/inspired by the work of ChimeraCoder's gojson package gojson.
# Web UI
- Easy to use
Only a few clicks on the web UI can generate the corresponding golang struct with `ORM` or `json` or `xm` ... tags.
# How to use?
### Docker deploy
- docker-compose up -d
- Use `localhost:8081` you will get the next page
![](https://tva1.sinaimg.cn/large/006tNbRwgy1g9w1ru6tl4j31wb0u0aft.jpg)
- Just Put your mariaDB/mysql info into it and you will get your golang code.
### Source code deploy
- git clone the source code
- cd Fdggs/
- go run main.go
- cd frontend && npm run dev/start
- Use `localhost:8081` you will get the web UI
- The same operation with docker deployment.