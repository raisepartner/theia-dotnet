# theia-dotnet
theia with dotnet core


```bash
docker build -t raisepartner/theia-dotnet-22:0.1.0 --build-arg version=next -f dotnet-core-22/Dockerfile .
docker push raisepartner/theia-dotnet-22:0.1.0

docker run -it --rm -p 3000:3000 -v $PWD:/home/project raisepartner/theia-dotnet-22:0.1.0
```
