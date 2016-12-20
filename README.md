# docker-hypercli
Docker image for hyper.sh cli based on Alpine Linux

## basic usage sample


```sh
docker run --rm -it chickenzord/hyper hyper images
```

## additional run arguments

auth using config from host

```
-v $HOME/.hyper/config.json:/root/.hyper/config.json
```

auth via environment variables

```sh
-e HYPER_ACCESS=my-hyper-access-key
-e HYPER_SECRET=my-hyper-secret-key
```

