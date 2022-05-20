## Introduction to SQL

SQL:

1. Data-definition-language(DDL) : provides commands for *defining relation schemas, deleting relations, and modifying relation schemas*

   SQL Data Definition

   The SQL DDL allows specification of not only set of relationsl, but also information about each relation including:

   - The schema for each relation
   - The types of value associated with each attribute
   - The integrity constrains 
   - The set of indices to be maintained for each relation
   - The security and authorization information for each relation
   - The physical storage structure of each relation on disk

   Basic Types

   The SQL standard supports a variety of built-in types, including:

   - char(n)
   - varchar
   - int
   - smallint
   - numeric(p,d) : A fixed-point number with user-specified precision. The number consists of p digits (plus a sign), and of the p digits are to the right of the decimal point.
   - real, double precision
   - float(n)

   Each type may include a special value called the NULL, indicates an absent value that may exist but be unknown or that may not exist at all.

2. Data-manipulation-language(DML): provides the ability to query information from database and to insert tuples into, delete and modify

   