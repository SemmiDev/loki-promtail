```shell
# 1. run all containers
make up
```

```shell
# 2. open grafana dashboard
http://localhost:3000
```

```shell
# 3. open "Add new connection" in the sidebar and choose "Loki"
# 4. Configure loki connection "http://loki:3100"
# 5. open "Explore" menu and select "Loki" datasource and apply the label filter "job" and "varlogs"
```

![1](./assets/1.png)
![2](./assets/2.png)
![3](./assets/3.png)
![4](./assets/4.png)
![5](./assets/5.png)
![6](./assets/6.png)
