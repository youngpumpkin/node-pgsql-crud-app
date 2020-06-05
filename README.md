"# node-pgsql-crud-app" 


##### psql query for creating table
CREATE TABLE IF NOT EXISTS players (
  id bigserial NOT NULL,
  first_name varchar(255) NOT NULL,
  last_name varchar(255) NOT NULL,
  position varchar(255) NOT NULL,
  number bigint NOT NULL,
  image varchar(255) NOT NULL,
  user_name varchar(20) NOT NULL,
  PRIMARY KEY (id)
);


##### password are needed for successful db connection
ALTER USER postgres PASSWORD 'newPassword';
