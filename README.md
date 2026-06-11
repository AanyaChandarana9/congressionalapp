# My App

## Idea

My idea is an app that hosts sporting events and allows a certain amount of people to sign up and join. This is tailored towards older users that want to stay in touch with sports and socialize. This will benefit them by helping with loneliness and becoming more active. Ideas of sporting events could include pickleball, walking clubs...etc. 

Hypothetical ideas:
- Mobility level and competitiveness scales 
- Google map using your location and the distance to the sporting event. 

## Tech

- Java
- Java FX (GUI)
  
## Data

### User
  
- name - String
- interests - String[]
- age - int
- events hosted - Event[]
- events attending - Event[]
- level of mobility - String

### Location

- general location - String
- latitude - double
- longitude - double
- N/S - boolean
- W/E - boolean

### Event

- location - Location
- Capacity - int
- Number of people going - int
- Meeting spot details - String
- Message from the host of the event - String
- Date and time - String
- Host - User
- type of event - String
- participants - User[]
- level of activity - String 


### Log-in information
 
- username - String
- password - String
- user - User


### Utility

- saveData()
- loadData()




