# EXP NO 1: ER DIAGRAM CREATION, RELATIONAL MODEL AND SCHEMA GENERATION  
### DATE
## AIM:
<div align="justify">
   To create a ER Diagram for Bank management system or College management system using ERD Plus tool and generate the relational model with schema. 
</div>

## Algorithm
1. Create a login with https://erdplus.com.
2. Create a new ER Diagram with name
3. Create a strong entity, relation and attributes.
4. Create a weak entity, relation and attributes.
5. Specify attributes unique, multivalued and composite attributes.

### ER Diagram 
![123](https://github.com/SubashiniSenniappan/DBMS/assets/119404951/5a58118b-038c-45fb-af47-4c013b23d6c2)


### Relational model
![124](https://github.com/SubashiniSenniappan/DBMS/assets/119404951/180f3d0f-072b-4e0c-85eb-aefc03a0b2ef)



### SQL DDL Schema 
```
CREATE TABLE Student
(
  Surname INT NOT NULL,
  GiveNames INT NOT NULL,
  Student_ID INT NOT NULL,
  Date_of_bIrth INT NOT NULL
);

CREATE TABLE Program
(
  Name INT NOT NULL,
  Program_ID INT NOT NULL,
  Creditpoints INT NOT NULL,
  Yearcommenced INT NOT NULL
);

CREATE TABLE Course
(
  Name INT NOT NULL,
  Course_ID INT NOT NULL,
  NewAttribute INT NOT NULL,
  Year_commenced INT NOT NULL
);
```

## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
