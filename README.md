# kube-esrally
A tool for Elasticsearch benchmark in Kubernetes

```bash
$ git clone git@github.com:kamolhasan/kube-esrally.git
$ cd kube-esrally
```

```bash
$ docker build .
$ docker tag 0997d121ca63  kamolhasan/esrally:0.0.4
$ docker push kamolhasan/esrally:0.0.4
$ kubectl run -it esrally --image=kamolhasan/esrally:0.0.4 -- /bin/sh
```