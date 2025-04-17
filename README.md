# redis-workshop-20250417

## Setup
Go to https://redis.io/docs/latest/operate/oss_and_stack/install/install-stack/homebrew/ for more information

Added the following to my `zshrc` file: 
```
export PATH=$(brew --prefix)/bin:$PATH
```

## Start Redis as a service 
Use the following command to run Redis as a service: 
```bash
redis-server /usr/local/etc/redis.conf
```

## Test service is running
Once connected to the service, verify it is running with:
```
ping
```
The service should return `Pong`

## Stop Redis as a service
Use the following command to stop the service: 
```bash
redis-cli shutdown
```

# Notes

## Streams vs Pub/Sub

Streams are more like texting now a days. Whereas Pub/Sub would function like publishing/subscribing.

## Index

A collection of docs are an Index. Documents have an ID. Documents have multiple fields. Not all docs have to have the same fields, and not all fields are relevent to be searched, so those have to be indexed.

Indexes appear to be a way to group multiple attributes to later then be searched.

## 