# B-Plus-Tree-Database

## Demo Video :

https://github.com/user-attachments/assets/4741a210-6dff-45b4-a273-a0acfa86974f

## Summary : 

This project is small version of database system where I have efficiently implement the B+ Tree in C++ language for fast and efficient access
of files. Database tuples will be stores as a .txt file in DBFiles folder corresponding FILE* will be saved in the leaf node.

## Assumptions in creating the Tree :

1. It is a right biased tree. By this it means , if maxLimits tree will be split in such a way that right sibling has one element greater.

2. Insertion is based on the primary key. Hence all the properties of the primary key has to be followed. No dublicate insertion has to be done with same primary key!

## Default DataBase Schema :

This DataBase Schema looks like this -

