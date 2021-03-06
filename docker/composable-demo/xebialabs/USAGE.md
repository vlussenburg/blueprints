# Composable Demo Usage

This blueprint comprises 3 other blueprints:

1. Docker compose file to run XL Deploy
2. Local Docker environment
3. Application to run on the environment


## Launch XL Deploy

In a separate terminal, run:

```plain
cd docker
docker-compose up
```


## How to use

To apply the file generated by this blueprint, execute the following command:

```plain
xl apply -f xebialabs.yaml
```

Now follow the instructions in `xebialabs/USAGE-docker-application.md` to deploy the container.


## The `USAGE` files

There will be 3 `USAGE` files in the `xebialabs` directory for you to read:

1. `USAGE-docker-compose.md`
This tells you about running Docker containers for XL Deploy, Xl Release and the Docker proxy.

2. `USAGE-docker-environment.md`
This tells you about the basic Environment in XL Deploy where the Docker application will be deployed.

3. `USAGE-docker-application.md`
This tells you how to deploy and test the application in XL Deploy.
