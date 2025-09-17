The ERD represents the International Airport database system. It includes entities such as Airport, Airline, Flight, Passenger, Booking, Boarding_pass, Baggage, Baggage_check, and Security_check.
The relationships are mainly One-to-Many (1:N), for example:
One Airline can have many Flights.
One Flight can have many Bookings.
One Passenger can have many Bookings.
One Booking can have many Boarding_pass and Baggage records.
There is also One-to-One (1:1) relationship:
One Baggage is connected to exactly one Baggage_check.
This ERD was normalized to 3NF, ensuring no redundant data and clear integrity of relationships.
