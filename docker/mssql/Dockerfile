FROM mcr.microsoft.com/mssql/server:2022-latest

# user root to prevent permission denied error on apt-get
USER root
RUN apt-get update \
    && apt-get install unzip -y

# Configure external build arguments to allow configurability.
ARG DBNAME=devdb
ARG PASSWORD

# Configure the required environmental variables
ENV ACCEPT_EULA=Y
ENV MSSQL_SA_PASSWORD=
