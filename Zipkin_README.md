# Download by browing https://search.maven.org/remote_content?g=io.zipkin&a=zipkin-server&v=LATEST&c=exec for window to get executable zipkin latest jar file

#NOTE: To store the zipkin logs in ES, need to pass the below parameter at time of zipkin server start, other storage MySql, Cassandra
java -DSTORAGE_TYPE=elasticsearch -DES_HOSTS=http://127.0.0.1:9200 -jar zipkin-server-2.23.16-exec.jar
--if in memory then use simply
#java -jar zipkin-server-2.23.16-exec.jar
