1a. 
    Create one nginx container named `digia`, 
    Port 80 -> 100
    Rename container to `foo`.
1b. 
    Delete `foo` container by name.

2a.
    Create one MySQL container name `database`, 
    Run in background, 
    Give `MYSQL_RANDOM_ROOT_PASSWORD` as `true`, 
    Port `8081->8082`.

2b. Delete `database` container by its hash name instead of its name

2c. Show logs on `database` to make sure password was set.

3a. Create `node:13-alpine`, `node:11`, `node:10-slim` container in background.

3b. Delete all containers using 1 command.