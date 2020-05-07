### PySpark docker image 


```
docker pull alext234/pyspark
```

Versions:

* APACHE_SPARK_VERSION=3.0.0-preview
* HADOOP_VERSION=3.2


### Example usage

```
docker run -p 8887:8888  -p 4040:4040 -p 8080:8080 -v $PWD:/work  -e GRANT_SUDO=yes --user root  -it alext234/pyspark:latest bash
```

```
jupyter notebook --allow-root
```
