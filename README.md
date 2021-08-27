# docker-angular-cli

Docker images to build an angular cli from node 10 official docker image.

## Tags 

The tags allowed are:

**12**: [12](https://hub.docker.com/layers/toni03/angular-cli/12/images/sha256-df6e89cf52d940c826f327ad7ca4218fd4b9d54c6cac091e696c6cac7bd8752a?context=explore), 
[12.2](https://hub.docker.com/layers/toni03/angular-cli/12.2/images/sha256-df6e89cf52d940c826f327ad7ca4218fd4b9d54c6cac091e696c6cac7bd8752a?context=explore), 
[12.2.3](https://hub.docker.com/layers/toni03/angular-cli/12.2.3/images/sha256-df6e89cf52d940c826f327ad7ca4218fd4b9d54c6cac091e696c6cac7bd8752a?context=explore), 
[12-node-12](https://hub.docker.com/layers/toni03/angular-cli/12-node-12/images/sha256-df6e89cf52d940c826f327ad7ca4218fd4b9d54c6cac091e696c6cac7bd8752a?context=explore), 
[latest](https://hub.docker.com/layers/toni03/angular-cli/latest/images/sha256-df6e89cf52d940c826f327ad7ca4218fd4b9d54c6cac091e696c6cac7bd8752a?context=explore)

**10**: [10](https://hub.docker.com/layers/toni03/angular-cli/10/images/sha256-66172efa95c6b6d3250b42de7b3ffd0d35bd670a4917e50ca3013da956d7c566?context=repo),
[10.2](https://hub.docker.com/layers/toni03/angular-cli/10.2/images/sha256-66172efa95c6b6d3250b42de7b3ffd0d35bd670a4917e50ca3013da956d7c566?context=repo), 
[10.2.0](https://hub.docker.com/layers/toni03/angular-cli/10.2.0/images/sha256-66172efa95c6b6d3250b42de7b3ffd0d35bd670a4917e50ca3013da956d7c566?context=repo), 
[10-node-10](https://hub.docker.com/layers/toni03/angular-cli/10-node-10/images/sha256-66172efa95c6b6d3250b42de7b3ffd0d35bd670a4917e50ca3013da956d7c566?context=repo)

**9**: [9](https://hub.docker.com/layers/toni03/angular-cli/9/images/sha256-fa6f6a08f50b57de594f019bef4ac8acd276fc629b19eed1098a0d77c9b6833b?context=repo), 
[9.1](https://hub.docker.com/layers/toni03/angular-cli/9.1/images/sha256-fa6f6a08f50b57de594f019bef4ac8acd276fc629b19eed1098a0d77c9b6833b?context=repo), 
[9.1.12](https://hub.docker.com/layers/toni03/angular-cli/9.1.12/images/sha256-fa6f6a08f50b57de594f019bef4ac8acd276fc629b19eed1098a0d77c9b6833b?context=repo), 
[9-node-10](https://hub.docker.com/layers/toni03/angular-cli/9-node-10/images/sha256-fa6f6a08f50b57de594f019bef4ac8acd276fc629b19eed1098a0d77c9b6833b?context=repo)

**8**: [8](https://hub.docker.com/layers/toni03/angular-cli/8/images/sha256-21b70dff1a2bf241b17ab372e527745b8fe7b5f025ea4aa7eae6bb958f542503?context=repo), 
[8.3](https://hub.docker.com/layers/toni03/angular-cli/8.3/images/sha256-21b70dff1a2bf241b17ab372e527745b8fe7b5f025ea4aa7eae6bb958f542503?context=repo), 
[8.3.29](https://hub.docker.com/layers/toni03/angular-cli/8.3.29/images/sha256-21b70dff1a2bf241b17ab372e527745b8fe7b5f025ea4aa7eae6bb958f542503?context=repo), 
[8-node-10](https://hub.docker.com/layers/toni03/angular-cli/8-node-10/images/sha256-21b70dff1a2bf241b17ab372e527745b8fe7b5f025ea4aa7eae6bb958f542503?context=repo)

**7**: [7](https://hub.docker.com/layers/toni03/angular-cli/7/images/sha256-72e168ac29d12f4e3698c6ae86b569e879f39d9681b12d718a391ce0095673d2?context=repo), 
[7.3](https://hub.docker.com/layers/toni03/angular-cli/7.3/images/sha256-72e168ac29d12f4e3698c6ae86b569e879f39d9681b12d718a391ce0095673d2?context=repo), 
[7.3.10](https://hub.docker.com/layers/toni03/angular-cli/7.3.10/images/sha256-72e168ac29d12f4e3698c6ae86b569e879f39d9681b12d718a391ce0095673d2?context=repo), 
[7-node-10](https://hub.docker.com/layers/toni03/angular-cli/7-node-10/images/sha256-72e168ac29d12f4e3698c6ae86b569e879f39d9681b12d718a391ce0095673d2?context=repo)

**6**: [6](https://hub.docker.com/layers/toni03/angular-cli/6/images/sha256-e5678fbe913d2874032eabc3964cff15977a7c1b6051a9ec62155076d1a023b7?context=repo), 
[6.2](https://hub.docker.com/layers/toni03/angular-cli/6.2/images/sha256-e5678fbe913d2874032eabc3964cff15977a7c1b6051a9ec62155076d1a023b7?context=repo), 
[6.2.9](https://hub.docker.com/layers/toni03/angular-cli/6.2.9/images/sha256-e5678fbe913d2874032eabc3964cff15977a7c1b6051a9ec62155076d1a023b7?context=repo), 
[6-node-10](https://hub.docker.com/layers/toni03/angular-cli/6-node-10/images/sha256-e5678fbe913d2874032eabc3964cff15977a7c1b6051a9ec62155076d1a023b7?context=repo)

## Launch commands

### Build and push Angular CLI 12 docker image

```sh
$> docker build --rm --no-cache -f Dockerfile -t toni03/angular-cli:12 .
$> docker tag toni03/angular-cli:12 toni03/angular-cli:latest
$> docker tag toni03/angular-cli:12 toni03/angular-cli:12-node-12
$> docker tag toni03/angular-cli:12 toni03/angular-cli:12.2
$> docker tag toni03/angular-cli:12 toni03/angular-cli:12.2.3
$> docker push toni03/angular-cli:latest
$> docker push toni03/angular-cli:12
$> docker push toni03/angular-cli:12-node-12
$> docker push toni03/angular-cli:12.2
$> docker push toni03/angular-cli:12.2.3
```

### Build and push Angular CLI 10 docker image

```sh
$> docker build --rm --no-cache -f Dockerfile -t toni03/angular-cli:10 .
$> docker tag toni03/angular-cli:10 toni03/angular-cli:latest
$> docker tag toni03/angular-cli:10 toni03/angular-cli:10-node-10
$> docker tag toni03/angular-cli:10 toni03/angular-cli:10.2
$> docker tag toni03/angular-cli:10 toni03/angular-cli:10.2.0
$> docker push toni03/angular-cli:latest
$> docker push toni03/angular-cli:10
$> docker push toni03/angular-cli:10-node-10
$> docker push toni03/angular-cli:10.2
$> docker push toni03/angular-cli:10.2.0
```

### Build and push Angular CLI 9 docker image

```sh
$> docker build --rm --no-cache -f Dockerfile.9 -t toni03/angular-cli:9 .
$> docker tag toni03/angular-cli:9 toni03/angular-cli:9-node-10
$> docker tag toni03/angular-cli:9 toni03/angular-cli:9.1
$> docker tag toni03/angular-cli:9 toni03/angular-cli:9.1.12
$> docker push toni03/angular-cli:9
$> docker push toni03/angular-cli:9-node-10
$> docker push toni03/angular-cli:9.1
$> docker push toni03/angular-cli:9.1.12
```

### Build and push Angular CLI 8 docker image

```sh
$> docker build --rm --no-cache -f Dockerfile.8 -t toni03/angular-cli:8 .
$> docker tag toni03/angular-cli:8 toni03/angular-cli:8-node-10
$> docker tag toni03/angular-cli:8 toni03/angular-cli:8.3
$> docker tag toni03/angular-cli:8 toni03/angular-cli:8.3.29
$> docker push toni03/angular-cli:8
$> docker push toni03/angular-cli:8-node-10
$> docker push toni03/angular-cli:8.3
$> docker push toni03/angular-cli:8.3.29
```

### Build and push Angular CLI 7 docker image

```sh
$> docker build --rm --no-cache -f Dockerfile.7 -t toni03/angular-cli:7 .
$> docker tag toni03/angular-cli:7 toni03/angular-cli:7-node-10
$> docker tag toni03/angular-cli:7 toni03/angular-cli:7.3
$> docker tag toni03/angular-cli:7 toni03/angular-cli:7.3.10
$> docker push toni03/angular-cli:7
$> docker push toni03/angular-cli:7-node-10
$> docker push toni03/angular-cli:7.3
$> docker push toni03/angular-cli:7.3.10
```

### Build and push Angular CLI 6 docker image

```sh
$> docker build --rm --no-cache -f Dockerfile.6 -t toni03/angular-cli:6 .
$> docker tag toni03/angular-cli:6 toni03/angular-cli:6-node-10
$> docker tag toni03/angular-cli:6 toni03/angular-cli:6.2
$> docker tag toni03/angular-cli:6 toni03/angular-cli:6.2.9
$> docker push toni03/angular-cli:6
$> docker push toni03/angular-cli:6-node-10
$> docker push toni03/angular-cli:6.2
$> docker push toni03/angular-cli:6.2.9
```
