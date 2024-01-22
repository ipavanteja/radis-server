# Radis-Server

To install Redis on an Ubuntu system, you can use the following commands:

1.  Update the package list:

    ```nginx
    sudo apt update
    ```

3.  Install Redis server:

    ```nginx
    sudo apt install redis-server
    ```

5.  Start the Redis service:

    ```nginx
    sudo service redis-server start
    ```

7.  Check the status of the Redis service:

    ```nginx
    sudo service redis-server status
    ```

Now, Redis should be installed and running on your system. You can also interact with Redis using the `redis-cli` command-line tool. For example:

-   To start the Redis command-line interface:

    ```nginx
    redis-cli
    ```

-   To check if Redis is working (in the Redis CLI):

    ```nginx
    ping
    ```
