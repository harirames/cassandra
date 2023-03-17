
Students detail in cassandra


Cassandra is a free and open-source, distributed, wide-column store, NoSQL database management system designed to handle large amounts of data across many commodity servers, providing high availability with no single point of failure. Cassandra offers support for clusters spanning multiple datacenters, with asynchronous masterless replication allowing low latency operations for all clients. Cassandra was designed to implement a combination of Amazon's Dynamo distributed storage and replication techniques combined with Google's Bigtable data and storage engine model.

This Student schema includes two tables:

     1)Student detail
     2)extadetail

The Student detail table stores information about each student

      register number,
      name, 
      class, 
      email, 
      phone,
      department,
      year of studying 

The extadetail table stores information about dayscholar or hostel

      register number,
      name,  
      department,
      room number or address,
      type(dayscholar or hostel),
