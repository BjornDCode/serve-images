## Updating a tag

CD into the tag folder

```
cd serve-images/laravel/<tag>
```

### Building

```
docker build -t bjornlindholm/<image>:<tag> -f Dockerfile .
```

### Push

```
docker push bjornlindholm/<image>
```
