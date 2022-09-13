#!/bin/bash
set -a
[ -f ".env.dynamic" ] && source <(cat .env.dynamic | sed -e '/^#/d;/^\s*$/d')
set +a
# echo $MSSQL_ROOT_PASSWORD
# docker-compose config
docker-compose "$@"