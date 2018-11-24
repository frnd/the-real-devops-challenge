FROM mongo

COPY ./restaurant.json /init.json
CMD mongoimport --host mongo --db restaurants --collection restaurant --type json --file /init.json --jsonArray