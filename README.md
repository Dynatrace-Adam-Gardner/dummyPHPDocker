https://hub.docker.com/r/adamgardnerdt/waiter

# Tag Explanation
- v1 = Zero seconds wait.
- v2 = 4 seconds wait.

# Installation
```
docker pull adamgardnerdt/waiter:v1
or
docker pull adamgardnerdt/waiter:v2
```

# Running
```
docker run -d -p 80:80 --name waiterV1 adamgardnerdt/waiter:v1
or
docker run -d -p 80:80 --name waiterV2 adamgardnerdt/waiter:v2
```

# Stopping
```
docker stop waiterV1
or
docker stop waiterV2
```
