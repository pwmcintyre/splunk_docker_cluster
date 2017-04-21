# Splurnk

Dear future me, please run this:

> docker run -p 8000:8000 -v `pwd`/my_app:/opt/splunk/etc/apps/my_app --env SPLUNK_START_ARGS="--accept-license" splunk/splunk
