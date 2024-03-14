FROM mongo:5.0

COPY docker-entrypoint.sh /usr/local/bin/

EXPOSE 27017
ENTRYPOINT ["docker-entrypoint.sh"]
CMD [ "mongod" ]