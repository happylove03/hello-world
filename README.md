Dockerfile shell script

WORKDIR /root/
ENTRYPOINT ["bash", "t.sh"]


.sh

while true;
  do echo "still live";
  sleep 600;
done

container stopped delete
docker rm $(docker ps -a -q)
