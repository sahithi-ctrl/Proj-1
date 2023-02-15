# Proj-1
The mysql.connector library is used to establish a connection to the UMLS database in the aforementioned code. After that, a cursor is created to run the queries. All circles with three or more nodes and fewer than forty different nodes will be chosen by the query itself. By connecting the MRCONSO and MRREL databases, screening them for nodes with the TTY of MSH, and ensuring that the nodes and CUIs are distinct and in alphabetical order, it achieves this. Additionally, it guarantees that the final node is of PT type and has CUI C0010054.

The results are kept in a set and then the first three are output using a loop. The cursor and connection are then shut off. Using this code, you can locate circles in

Output:-
Output is:-
Circle 1: Allergic rhinitis to Bronchitis to Asthma to Allergic rhinitis Circle 2: Asthma to Allergic rhinitis to Bronchitis to Asthma Circle 3: Bronchitis to Asthma to Allergic rhinitis to Bronchitis
