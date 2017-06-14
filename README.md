# Yelp-Dataset-Cassandra

In this homework you will learn how to use Cassandra. Please use the

“Apache_Cassandra_1.2.pdf” for reference and help.

Cassandra 2.05 has been installed and you can access it through cs6360.utdallas.edu. It has four

nodes: csac0, csac1, csac2, and csac3. The path is /usr/local/apache-cassandra-2.0.5

**You are going to create a keyspace with your net ID (i.e., abc112233) and do all work in this

keyspace. Replication factor should be 1.

Q5: Cassandra CQL3

{cs6360:~} /usr/local/apache-cassandra-2.0.5/bin/cqlsh csac0

Requirements:

Using Cassandra CQL3, write commands to do the following:

1- Create a table for business.csv dataset. Use (business_id) as the Primary Key.

2- Load all records in the dataset to this table.

3- Select the tuple which has business id &#39;HPWmjuivv3xJ279qSVfNaQ&#39;

4- Delete all rows in the table.

5- Drop the table.

Q6:

Using Cassandra CQL3, write commands to do the following:

1. Create a table for review.csv dataset using the user_id,business_id as the primary key and the stars as

the sorting key.

2. Create index on column stars.

3. Select any row where the rating is 4.0 limit display result to 10.

4. Delete all rows in the table

5. Drop the table.



Q7: Cassandra Administration

1) Run nodetool command and determine how much unbalanced the cluster is.
