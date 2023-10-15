AIRBNB CLONE PROJECT
Software Development Lifecycle - SDLC

1.Planning
2.Analysis| Requirement Analysis
3.Design ( DDR- Design document requirement) -Wireframing
4.Implementation stage - building Software
5.Testing
6.Deployment | Maintenance


Web App -> FrontEnd
        -> Backend -> OOP concepts
        -> Database (File storage) -> (json module)
        -> Testing-> unittest module
Analysis -> Airbnb
User account -> fields: name, email, unique_id, created_date, updated date
Reviews -> unique_id, update_time, created_date
place
Amenity -> classes (attribute and method that says what can b e done)

CRUD : things that can be done in a database when you are creating database application,
C- Create
R - Read
U - Update
D - Delete

Class BaseModel will be created 

Class BaseModel ():
#define attributes that are common to all the classes
#define methods that are common to the classes


Class User(BaseModel):
#Inherit all the base class attributes
#all the base class method
#dclare the unique attributes
declare the unique methods of the class
 
class Amenity(Basemodel):
# attributes

Everything in python is an OBJECT
prepare this object for storage -> Serialization
				   Deserialization

ClassFileStorage():
#attributes related to file
#methods related file

