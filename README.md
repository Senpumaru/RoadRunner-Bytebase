# RoadRunner-Bytebase
Bytebase deployment for DB migrations

helm -n bytebase \
--set "bytebase.version"=1.7.0 \
install bytebase-release bytebase-repo/bytebase