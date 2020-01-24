# S2I sample

More base image can be found [HERE](https://microbadger.com/images)

```bash
s2i build . centos/nodejs-6-centos7:latest s2i-app
docker run -p 8080:8080 s2i-app
```
