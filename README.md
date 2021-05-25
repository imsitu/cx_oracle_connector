One fucntion to handle all CRUD operations using CX_Oracle and python

1. Fucntion can handle both tcp and tcps protocols
2. If protocol is tcps, we need to install oracle insta client and edit the location of oracle client location in "cx_Oracle.init_oracle_client"
3. After installation of oracle insta client , we need to add wallet in ~/instantclient_19_8/network/admin/ or configure sqlnet.ora and tnsnames.ora w.r.t the version of oracle and connection details.



