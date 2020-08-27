# FANDANGO CLONE

### MVP
- Able tickets with an app
- List movies currently showing at a theater
- User is able to buy tickets
- Establishes connection with a database
- Display showings based on location


### USER STORY
- Who is going to use it?
- How will they use it?
1. Opens app
2. Searches movie information/ search for theater and what it's showing
3. Selects location based on movie/ select movie based on locatio
4. Select time of showing
5. Select number of tickets. Potentially which seats to reserve
6. Makes ticket purchase

### API
Search Movies API
- keyword (string)
- date of showing (string/int)
- location (string)
- genre (string)

- cast
- release date

### SCHEMA
- User:
  - id, name, email, credit card, pwd
- Theater:
- Showings:
- Bookings/tickets:
- Movies: 

User has many Bookings/Tickets
Booking has one showing
Theaters has many movies
Showing has one movie
Showing has multiple Booking
Movies has many users
