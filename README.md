# Docker container for building frontend

Docker container having all you need to build your app on the CI server.

## Building

```
docker build juristr/angular-ci
```

## Tagging

```
docker tag <sha> juristr/angular-ci:<tag-name>
```

## Publish

```
docker push juristr/angular-ci
```
