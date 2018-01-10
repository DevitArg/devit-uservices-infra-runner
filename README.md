These files concentrates the run configuration for uServices Infra's docker images locally.
Just need to run `./start_infra` script to run all containers: eureka, config, etc.

## Files you need to add
### .configuration-server-env
Add a new file .configuration-server-env with this data within the project root folder
```
# replace the values for yours
spring.cloud.config.server.git.username=<repo-username>
spring.cloud.config.server.git.password=<repo-password>
security.user.name=<config-server-username>
security.user.password=<config-server-password>
```