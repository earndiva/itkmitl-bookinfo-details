# How to run details service

## Prerequisite

* Ruby 2.7

```bash
ruby details.rb 9080
```

## How to run with Docker

```bash
# Build Docker Image for datails 

docker build -t details . 

# Run Details.rb 

docker run -d --name details -p 8081:8081 details
```
* Test with path `/details/1` and `/health`