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

## Frontend files:
* anggota
  *  AnggotaHomePanel : panel for user menu
  *  DetailUserPanel : panel for seeing user detail
  *  PembayaranPanel : panel to pay loan fine
  *  PeminjamanPanel : panel to loan books
  *  PengembalianPanel : panel to return books
* staf
  *  DaftarPeminjamPanel : panel to see the list of the borrower
  *  DetailAnggotaPanel : panel for seeing members detail
  *  HapusBukuPanel : panel to remove books
  *  PeringkatPanel : panel to see the users rank
  *  StafHomePanel : panel for staf menu
  *  TambahBukuPanel : panel to add books
  *  TambahDosenPanel : panel to add lecturer members
  *  TambahMahasiswaPanel : panel to add student members
  *  TambahKategoriPanel : panel to add book categories
* HomeGUI : panel change logic
* SistakaPanel
* WelcomePanel : SistakaNG home page
* LoginPanel : panel for user/staf login

## Main file
* SistakaNGUI : main program to execute the loan book system

## Features

* Main Panel : Welcome page
<img src="https://user-images.githubusercontent.com/88226713/174008673-e0663676-0bd5-44d5-9803-4d001908f826.png" width="300">

* Login Panel : Login with ID user/staff 
<img src="https://user-images.githubusercontent.com/88226713/174008736-081a6324-ea33-4520-a059-a991f7a773f7.png" width="300">

### Staff Panel
* Staff Menu : Consists of menu that staff can do
<img src="https://user-images.githubusercontent.com/88226713/174008894-a5edf6e7-d722-407f-9566-10f56d2ce020.png" width="300">

* Add Student : Add students data to system
<img src="https://user-images.githubusercontent.com/88226713/174009044-51bc2fe5-b480-4494-910e-db20e63be818.png" width="300">

* Add Lecturer : Add lecturer data to system
<img src="https://user-images.githubusercontent.com/88226713/174009136-e8938e49-0bb5-4f39-bef1-f27d050028b6.png" width="300">

* Add Category : Add book category to system
<img src="https://user-images.githubusercontent.com/88226713/174009207-fdd30827-691e-47f0-9616-1820b288a219.png" width="300">

* Add Book : Add book to system
<img src="https://user-images.githubusercontent.com/88226713/174009306-091362c1-92f4-4884-8b97-492fb128352a.png" width="300">

* Remove Book : Remove book from system
<img src="https://user-images.githubusercontent.com/88226713/174009397-e51991e9-6f52-4cc9-83dc-3b3e4f5a3e26.png" width="300">

* User rank : Check user rank (borrow the most books)
<img src="https://user-images.githubusercontent.com/88226713/174009771-2dfa4f87-9568-4baf-a189-27ae09794d27.png" width="300">

* User Detai : Check the user detail
<img src="https://user-images.githubusercontent.com/88226713/174009846-a7d1597d-7280-435a-849b-823199288624.png" width="300">

* Book Borrower List : Display book borrower lists
<img src="https://user-images.githubusercontent.com/88226713/174009975-3ca17999-331b-41cd-b0a5-c77fe9278a69.png" width="300">

### User Panel
* User Menu : Consists of menu that user can do
<img src="https://user-images.githubusercontent.com/88226713/174010685-8df5acd9-9b1f-4089-ab5c-bdd7cad3740b.png" width="300">

* Loan Book : Loan books from system
<img src="https://user-images.githubusercontent.com/88226713/174010162-09879add-608e-4ebd-8bb8-e743cfc80e1b.png" width="300">

* Return Book : Return books to system
<img src="https://user-images.githubusercontent.com/88226713/174010234-ec424d44-1b8f-4612-af77-94a0d4fca9e8.png" width="300">

* Pay Fine : Pay fines for late return
<img src="https://user-images.githubusercontent.com/88226713/174010304-53700196-ec0f-440d-b980-787853af7270.png" width="300">

* User Detail : Check the user detail
<img src="https://user-images.githubusercontent.com/88226713/174010377-122d666b-38f3-4e60-a2d9-8540bd496d37.png" width="300">


