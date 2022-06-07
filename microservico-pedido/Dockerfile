from rrojano/jdk8
workdir /app
#CMD ["/app/script.sh"]
add app/tis-0.0.1-SNAPSHOT.jar /app/tis-0.0.1-SNAPSHOT.jar
#add script.sh /app/script.sh
#run chmod 755 /app/script.sh
CMD java -jar -Dserver.port=$PORT tis-0.0.1-SNAPSHOT.jar