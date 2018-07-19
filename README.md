# Coding-Conventions

## Databases

### Table names should be snake case with capital letters, e.g.: Foo_Bar

Table naming conventions:
- they should be singular
- they should not include the word "table"

### Column names should be snake case with lowercase letters, e.g.: baz_bar

### Id columns

Id columns should be named "id". If they are a foreign key, they should be preceded by the table name, e.g.: id_baz_bar
