# Boris
A project for an App visioning to hire bikes parked in docks

# Boris
A project for an App visioning of hiring of bikes parked in docks

# Approach

Using Domain Modeling in order to extract information and create a functional representation of a ' user story':

```
As a user,
So I can find customers,
I want to search for my customers by their surnames.

As a person,
So that I can use a bike,
I'd like a docking station to release a bike.

As a person,
So that I can use a good bike,
I'd like to see if a bike is working
```

From the user stories information above I have split it in to two columns: nouns and verbs, as to apply the functional representation.

Nouns           |  Verbs

user            |  find                      
person          |  use
bike            |  working   
docking station |  release


Objects         | Messages

User            | 
Costumer        | find_by_surname
Person          |
Bike            | working?
Docking Station | release_bike


Bike <-- working? --> boolean
DockStation <-- release_bike --> Bike
