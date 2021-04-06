# Hospital_appointment_system
This is a website project that will allow patients to book appointments in a hospital. 


Hospitals have a fixed number of slots every day, for example a hospital could have 30 mins slots for each patient. Considering breaks and lunch etc, a hospital can decide what are the timings for the slots every day. An example of the available slots for a day would be

10:00 AM - 10:30 AM
10:30 AM - 11:00 AM
---- 30 mins Break ----
11:30 AM - 12:00 PM
12:00 PM - 12:30 PM
And so on…

Now only one patient can book a particular slot for a particular day. So if a patient has already booked the 10:00 AM - 10:30 AM slot, then that slot is not available for another patient.
...................................................................................................


## TO RUN PROJECT

### BACKEND:
	```
	cd api
	npm install
	npm start
	```
#### endpoint : [localhost:3000/appointments](https://localhost:3000/appointments)
   
### FRONTEND
	```
	cd app
	ng build
	ng s
	```
	
### To book an appointment: [localhost:4200](https://localhost:4200)
	
	
### to see all bookings: [localhost:4200/appointment-list](https://localhost:4200/appointment-list)
	
	
	
	
## Tech stack
* Database: Mongodb
* Server: Nodejs (Express)
* frontend: angular, material

     
      
