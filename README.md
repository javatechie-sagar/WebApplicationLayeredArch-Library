# WebApplicationLayeredArch-Library

Hi All

This Web Application is to perform Library operations using Layered Arachitecture.

The application performs CRUD operations on Book table on Oracle database.

TODOs

1.Download the project and extract.

2. Import this project from eclipse. Ensure that JRE System Library is set to 1.8 (BuildPath -> Configure Build Path->  Libraries->JRE System Library)

3. Add the following jar files in 'WebContent/WEB-INF/lib' folder and run it.

       servlet-api.jar,  jsp-api.jar,  ojdbc6.jar


** Book table has the following structure.

SQL> desc book;
 Name                                      Null?    Type
 ----------------------------------------- -------- --------------------

 ID                                                 NUMBER(4)
 BNAME                                              VARCHAR2(20)
 AUTHOR                                             VARCHAR2(20)
 PRICE                                              NUMBER(7,2)
 
 Refer this project for further reference.
 
 
