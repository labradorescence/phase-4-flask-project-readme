# PROJECT PITCH
### Owner/s: 

### Phase and Cohort:  Phase 4



## One sentence app description:
Coffee Order Tracking App 


## Domain Model: 
![domainmodel](https://i.imgur.com/f5isEXU.png)


## MVP:
C
R
U
D


## BACKEND (API)
### MODELS
* many-to-many relationship
* A `Customer` has many `Coffee`s through `Order`s
* A `Coffee` has many `Customer`s through `Order`s 
* A `Order` belongs to a `Customer` and belongs to a `Coffee`


### validations 
* Add validations to the `Customer` model:
* - must have a `name`
* Add validations to the `Coffee` model:
* - must have a 'name' 
  - must have a `price` between 1 and 20


## CONTROLLERS
​​API routes 
RESTful conventions 
```
GET /coffees/
GET /coffees/<int:id>
POST /coffees/
PATCH /coffees/<int:id>
DELETE /coffees/<int:id>
```
```
GET /customers/
GET /customers/<int:id>
POST /customers/
PATCH /customers/<int:id>
DELETE /customers/<int:id>
```
```
GET /orders/
GET /orders/<int:id>
POST /orders/
PATCH /orders/<int:id>
DELETE /orders/<int:id>
```


### Serialize rules 
* 


FRONTEND (REACT)
Which components will make requests to your API? What route will the competent send fetch requests too? (i.e: ArtistForm, send a POST requests to /artists) 
-
-
-


EXTRA!
Stretch goals:
-
-
-
-

Timeline:

Friday: (example below)
Layout API Schema
Layout Frontend Wireframe
Fillout Project Pitch
Start building API (backend)
Recommend to code the API FIRST, to ensure your data structure will work! 😉


Monday: 
Info
Info
Info
Tuesday: 
Info
Info
Info
Wednesday: 
Info
Info






Friday: Project Presentation
STUDENT NAME / I will speak about
Info
Info
Info
STUDENT NAME will speak about
Info
Info
Info








