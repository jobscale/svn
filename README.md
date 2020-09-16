# svn

## example

```
docker build . -t local/svn
docker run --rm --name svn -v $(pwd):/home/svn --workdir /home/svn -it local/svn
```

## image

```
docker pull jobscale/svn
docker run --name svn -v $(pwd):/home/svn --workdir /home/svn -it jobscale/svn
```
