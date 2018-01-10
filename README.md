# less with animate && flex layout demo

* build 
```bash
yarn build:less
```
* run
```bash
yarn run start
```
* run with docker
- local run 
```bash
docker build -t demo .
docker run -d -p 8080:8080 demo
```
- remote 
```bash
docker run -d -p 8080:8080 dalongrong/animate-less
```