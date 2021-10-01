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

Once you are inside the pod:

```bash
$ esrally race --pipeline=benchmark-only --target-hosts="sample-es.demo:9200" --client-options="basic_
auth_user:'elastic',basic_auth_password:'Ff7f~v-W!cnlS3Cq',use_ssl:true,verify_certs:false" --track=geon
ames --kill-running-processes
```

**N.B.:** Use `esrally race --help` to understand the meaning of the passed flags.
- `--target-hosts`: comma seperated `host:port` values.
- `--kill-running-processes`: kill running race if any.
- `--client-options`: Configure the client.