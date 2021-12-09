# Experiment with debug node app with container using VSCode

## Setup Instruction

- https://code.visualstudio.com/docs/containers/quickstart-node

## Debug
### Using docker-compose
```
docker-compose -f docker-compose.debug.yml
VSCode|Run and Debug|Docker: Attach to compose container
```

### Using docker
```
VSCode|Run and Debug|Docker Node.js Launch
```