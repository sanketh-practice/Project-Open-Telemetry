# Copyright The OpenTelemetry Authors
# SPDX-License-Identifier: Apache-2.0
#this is the docker file for postgres
FROM postgres:17.6

COPY ./src/postgres/init.sql /docker-entrypoint-initdb.d/init.sql

EXPOSE ${POSTGRES_PORT}
