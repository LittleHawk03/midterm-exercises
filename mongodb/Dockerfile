# FROM mongo:5.0

# WORKDIR /usr/src/data

# COPY data.json .

# RUN "mongoimport --host localhost --db list_candidate_VDT --collection candidate --type json --file ./data.json --jsonArray"


FROM mongo:5.0

COPY init.json /init.json

CMD mongoimport --host mongodb --db list_candidate_VDT --collection candidate --type json --file /init.json --jsonArray