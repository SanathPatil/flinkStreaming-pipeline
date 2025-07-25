### docker compose up
- sets up the images

#####  docker exec -it flink-jobmanager python /opt/src/producers/producer.py

- executes producer.py


##### docker compose exec jobmanager ./bin/flink run -py /opt/src/job/start_job.py --pyFiles /opt/src -d


- runs start_job.py flink job to enter data to postgres



##### Note:
read on tumbling, sliding, session windows