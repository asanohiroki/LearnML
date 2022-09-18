# LearnML


<!-- ## Dependency -->
## setup

### For M1 Mac
- prepare docker container for M1 Mac
```
$docker pull jupyter/scipy-notebook
$docker create --name learnML --platform linux/x86_64 jupyter/scipy-notebook:latest
```

- start docker container
```
docker run -p 8888:8888 -v /Users/$USER/LearnML/scripts/:/home/jovyan/work/ --platform linux/x86_64 jupyter/scipy-notebook:latest
```

<!--
## Usage
## Authors
## References
-->