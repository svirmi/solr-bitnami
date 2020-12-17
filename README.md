To run solr console command inside docker:
```bash
docker exec -it bitnami-1_solr_1 ./opt/bitnami/solr/bin/solr status
docker exec -it bitnami-1_solr_1 bash

##### to post data folder to core run
```bash
docker exec -it bitnami-1_solr_1 ./opt/bitnami/solr/bin/post -c mycore ./opt/solr/server/solr/mycore/example/exampledocs/

##### installtion video
https://youtu.be/2-VwlzpX0qY

##### installation manual
https://computingforgeeks.com/install-latest-apache-solr-on-ubuntu-debian


##### how to download
wget https://downloads.apache.org/lucene/solr/8.7.0/solr-8.7.0-src.tgz


docker ps
CONTAINER ID        IMAGE                      COMMAND                  CREATED             STATUS              PORTS                    NAMES
0feb77f8dedd        bitnami/solr:8-debian-10   "/app-entrypoint.sh …"   About an hour ago   Up About an hour    0.0.0.0:8983->8983/tcp   bitnami-1_solr_1 <---