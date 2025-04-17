# redis-workshop-20250417

Added the following to my `zshrc` file: 
```
export PATH=$(brew --prefix)/bin:$PATH
```
 
Use the following command to run Redis as a service: ```redis-server /usr/local/etc/redis.conf```

Use the following command to stop the service: ```redis-cli shutdown```