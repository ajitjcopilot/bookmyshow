```bash
sandeep@Namans-Scaler-MacbookM1Pro-16 ~ % psql
psql (14.1)
Type "help" for help.

sandeep=# create database DBNAME;
CREATE DATABASE
sandeep=# create user USERNAME;
CREATE ROLE
sandeep=# grant all privileges on database DBNAME to USERNAME;
GRANTgit config --global user.email “ajitjaiswal@gmail.com”
sandeep=#
```


// A (B) -> B will be taken from a DB
// A (Database)
// A has B
// A(B b)
// 


Agenda:
1. Implement Transaction Isolation in Spring Boot for BMS

Feature:
- Person wants to book a ticket for a show
- TicketController {
  - bookTicket(
    - show_id
    - list<show_seat_id>
    - user_id
  - )
- }


- TicketService {
  - bookTicket(
    - show_id
    - list<show_seat_id>
    - user_id
  - ) 
- }

- How will bookTicket() in TicketService work?
  - update show_seats
  - set status = LOCKED
  - where show_seat_id in ()



// City
// Theatre
// Auditorium
// Seat
// Show

git config --global user.email "ajitjaiswal@gmail.com"

git remote add origin "https://github.com/ajitjcopilot/bookmyshow.git"

git remote add origin https://github.com/ajitjcopilot/bookmyshow.git
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


git remote set-url origin "https://ajitjcopilot@github.com/ajitjcopilot/bookmyshow.git"