# spring-hibernate-1toN_way1

This is the spring hibernate application demonstrating one to many mapping of hibernate 

STUDENT and PHONE have one to many relation, one student can have many phone numbers,so we are creating STUDENT_PHONE table to store the mappings using hibernate

Here we are using @JoinTable annotation to create 3rd table(mapping table)
using joinColumns we define the primary key column of the table and using inverseJoinColumns we define the primary key column of table which is at other end of relation
