## Astro running on AWS App Runner

1. Build image using ECR repo as tag
```
docker build -t xxxxx.dkr.ecr.us-east-1.amazonaws.com/[namespace]/[repo]:[version] .
```

2. Push image to ECR repo
```
docker push xxxxx.dkr.ecr.us-east-1.amazonaws.com/[namespace]/[repo]:[version]
```

3. App runner service will be auto-deployed