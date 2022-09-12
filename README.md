# Backend Engineer Test

This assignment to implement an **API (REST)** to support a Car-sharing booking application that allows users to book a car in following context. <br />

The car movement is going to be in 2D grid. The location of the car will be based on XY axis (example: CarA locates 3,5 location). 
There are 5 cars in the system with unique car name like CarA, CarB, etc. The cars will be deployed to different locations (home-lot). Car can be booked only if it is within 2 units of XY axis (delta of X + Y). For an example, let’s say user’s location is (1,2) and nearest Car (CarA) location is (3,2), then the CarA is available to book.  If nearest Car (CarA) location is (2,4), then the system cannot consider CarA to book [delta is ((2-1) + (4-2)) > 2 units]. <br />

For assignment purpose, when user book a car, the API should automatically assign **nearby** car based on user’s location instead of the application allows user to choose a car based on their preference normally. Note that car's location (home-lot) will not changed once the booking is completed; Will remain the same home-lot.<br />

You are required to implement API endpoints for following functionality:<br />
1.	Get all cars with details <br />
2.	Search car <br />
3.	Book a car <br />
4.	Reach Car's home-lot <br />

[Feel free to decide the payload of each endpoint]

Note that data should be stored into persistent storage. Feel free to choose the persistence storage. 

**System Requirements:** <br />
Your implementation, <br />
*	Should use proper data structures and algorithms <br />
*	Should have the basic business rule validations and error handlings <br />
*	Should have unit testing <br />
*	Should be of production quality <br />
*	Prefer container based solution <br />

**Assignment considerations and evaluation:**  <br />
*	API design <br />
*	Code quality <br />
*	Best design and coding practices <br />
*	Test coverage <br />
*	Extensibility <br />

**Technology stack:** <br />
.Net Core
