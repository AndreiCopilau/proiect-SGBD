# Proiect SGBD - Gestionarea rezervărilor bilete cinema

Acest proiect este o extensie a celui realizat la materia **Baze de Date**, având ca scop dezvoltarea și implementarea unei baze de date relaționale complexe pentru gestionarea rezervărilor bilete la cinema.

### Descrierea proiectului

Modelul de date creat permite gestionarea eficientă a următoarelor aspecte:  
- Clienții care doresc să rezerve bilete pentru un anumit film, într-o sală specifică și la o oră anume.  
- Angajații responsabili cu preluarea rezervărilor.  
- Departamentele în care activează angajații.  

Baza de date conține în total 8 tabele, dintre care unul este tabel asociativ, realizând legătura între clienți, bilete și filme. Fiecare tabel are un rol esențial în stocarea organizată și eficientă a datelor.

Un client poate achiziționa mai multe bilete care includ locuri multiple, pentru un film proiectat într-o sală la o dată specifică. Rezervarea este gestionată de un angajat care lucrează într-un anumit departament.

---

## Cuprinsul proiectului

1. **Prezentarea bazei de date și a utilității acesteia** – pag. 3  
2. **Diagrama Entitate-Relatie (ERD)** – pag. 4  
3. **Diagrama conceptuală** – pag. 5  
4. **Definirea tabelelor și a constrângerilor** – pag. 6  
5. **Inserare de date în tabele** – pag. 11  
6. **Subprogram stocat independent care utilizează toate cele 3 tipuri de colecții studiate** – pag. 19  
7. **Subprogram stocat independent cu 2 tipuri diferite de cursoare, unul parametrizat, dependent de celălalt** – pag. 22  
8. **Subprogram stocat independent de tip funcție care utilizează într-o singură comandă SQL 3 dintre tabele, cu tratarea excepțiilor NO_DATA_FOUND și TOO_MANY_ROWS** – pag. 25  
9. **Subprogram stocat independent de tip procedură cu minim 2 parametri, folosind într-o singură comandă SQL 5 tabele și definirea a minim 2 excepții proprii** – pag. 29  
10. **Definirea și declanșarea unui trigger de tip LMD la nivel de comandă** – pag. 35  
11. **Definirea și declanșarea unui trigger de tip LMD la nivel de linie** – pag. 37  
12. **Definirea și declanșarea unui trigger de tip LDD** – pag. 39  

---

## Tehnologii folosite

- Oracle Database 19c  
- Proceduri stocate, funcții, trigger-e  

---
