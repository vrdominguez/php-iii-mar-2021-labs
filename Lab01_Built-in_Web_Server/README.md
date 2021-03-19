# Running this lab

1. Launch de docker with php built-in server with ```launchInDocker.sh```
2. In other console/terminal run ```docker inspect php-built-in | fgrep '"IPAddress":'```
3. Navigate to ```http://<ip_address>:9000``` and see logs in the console with the docker container.
4. Kill the container with Ctrl+C (I will be deleted).

## Logs example

```
[Fri Mar 19 15:34:08 2021] PHP 8.0.3 Development Server (http://0.0.0.0:9000) started
[Fri Mar 19 15:34:11 2021] 172.17.0.1:59188 Accepted
[Fri Mar 19 15:34:11 2021] 172.17.0.1:59190 Accepted
[Fri Mar 19 15:34:11 2021] 172.17.0.1:59188 [200]: GET /
[Fri Mar 19 15:34:11 2021] 172.17.0.1:59188 Closing
[Fri Mar 19 15:34:11 2021] 172.17.0.1:59194 Accepted
[Fri Mar 19 15:34:11 2021] 172.17.0.1:59190 [200]: GET /
[Fri Mar 19 15:34:11 2021] 172.17.0.1:59190 Closing
```