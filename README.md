# SistakaNG
Book loan system program.

## Description
SistakaNG is the final project of OOP programming foundations course in University of Indonesia. The purpose of the program is to maintain book loan system in the library.

## Backend files
* buku
  * Buku : represents a book object with certain book data
  * Kategori : represents each category from the book collection in the library
  * Peminjaman : represents each of loaned books by members
* pengguna
  * CanBorrow : interface to be implemented for the class that can borrow
  * Pengguna : abstract class that represents the users of SistakaNG
  * Staf : representation of staff who are users of SistakaNG
  * Anggota : abstract class which is a subclass of Pengguna
  * Mahasiswa : representation of students who are users of SistakaNG
  * Dosen : representation of lecturers who are users of SistakaNG
  * IdGenerator : class to create students ID 
* SistakaNG : main method to run the program that has been created 

