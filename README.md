# Splurnk

Dear future me, please run this:

> docker run -p 8000:8000 -v `pwd`/my_app:/opt/splunk/etc/apps/my_app --env SPLUNK_START_ARGS="--accept-license" splunk/splunk


> docker rm `docker ps --no-trunc -aq`

> docker-compose rm -f && docker-compose up splunk_master splunk_indexer_1

> docker stop splunk_fwd

To rebuild the images
> docker-compose build


docker (the hypervisor thing which does stuff)
images (these are templates for pre-made stuff)
containers (which are an instance of an image)

docker 1--* images 1--* containers


## Git stuff

Clean (be careful, you will lose any unsaved work)

> git clean -fdx && git reset --hard

