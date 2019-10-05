docker run -d -p 8886:8888 -p 6665:55555 --name btsync ctlc/btsync
docker logs btsync
docker run -i -t --volumes-from btsync ubuntu /bin/bash

AU6GUE3NY7QEIQNY3T7YH3DKB3GTLDP2S

docker run -d -p 8886:8888 -p 6665:55555 --name btsync ctlc/btsync


docker run -d --name btsync-client -p 8886:8888 -p 6665:55555 -v $PWD/temp:/data ctlc/btsync AQDZHULT7K4OFA4RMASVX4N5NMMW3PSIT

