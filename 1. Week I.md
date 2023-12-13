# Pengantar-DB## 📘 My Personal Notes

### 🗓️ Week 1: Introduction to Database (DB)

#### 📍 Definition and Purpose of Database
DB vs DBMS = Basis data (db) adalah kumpulan data terstruktur,
sedangkan sistem manajemen basis data (DBMS) adalah
perangkat lunak yang mengelola dan berinteraksi dengannya
data.

PURPOSE OF DBMS = Data Redundancy,Inconsistency,Difficulty in Accessing Data,Need for New Programs,Data Isolation,Integrity Problems,Challenges with Constraints,Atomicity of Updates,Concurrent Access Issues,Security Problems.

#### 📍 View of Data
-DATA MODELS = kumpulan alat untuk mendeskripsikan : Data, D. relationships , D. semantic , D. constraints

memiliki dua type = Relational dan Entity-Relationship

-DATA ABSTRACTION :
 
  a.Physical level = menjelaskan bagaimana catatan (misalnya, instruktur) disimpan.
  
  b.Logical level = menjelaskan data yang disimpan dalam database, dan hubungannya
                    di antara datanya.

ID : string;

name : string;

dept_name : string;

salary : integer;

end;
  
  c.View level = program aplikasi menyembunyikan rincian tipe data. Tampilan bisa
juga menyembunyikan informasi (seperti gaji karyawan) demi keamanan
tujuan.


#### 📍 DB Languages, Design, Architecture, and Users and Administrator

-Dalam perancangan database, ada
dua tahap utama yang harus dilalui: logis
desain dan desain fisik. Keduanya
tahapan memainkan peran penting dalam
proses pengembangan database
sistem.

Key components Logical Design:

a.Entity

b.Relationship

c.Attribute

Key components of Physical Design:

a.Tables and indexes

b.Storage

c.Security
