## Project

TechStack : 
1) React
2) Bootstrap
3) SCSS
4) Redux
5) Node.js(Nest.js)
6) Unit tests(Jest)
7) AWS Lambda and Cloud Formation
8) MongoDB
9) DynamoDM
10) PostgreSQL
11) APIGateway
12) Docker


# Frontend

1) Authorization
  - header with company title
  - input of password
2) Game 
  - header with company title
  - input of level with button 
  - body of game(image(S3) and text)
  - helpers with timer
3) EndScreen 
  - header with company title
  - body with good words

# API 
1) Passwords in MongoDB
 - all 
 - one 
2) Levels in PostgreSQL
 - all 
 - one by id
3) Helpers in PostgreSQL
 - all 
 - one by id
 - one by levelID

# Data base 
Passwords:
1) id
2) password

Levels: 
1) id
2) imageSrc
3) body of level
4) createdAt
5) updatedAt


Helpers: 
1) id
2) imageSrc
3) body of helper
4) levelId
5) timeForOpen
6) createdAt
7) updatedAt
