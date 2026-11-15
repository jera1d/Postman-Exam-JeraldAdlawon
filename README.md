Restful-Booker API Testing (Postman)

This is my Postman test suite for the Restful-Booker API exam. It tests creating, updating, checking, and deleting a booking in order, using environment variables to pass the token and booking ID between requests.

Files Included
Restful-Booker Automated Suite.postman_collection.json - Contains the 5 API requests and test scripts.
Restful-Booker.postman_environment.json - Contains the baseUrl, token, and bookingid variables.

Requests in the Collection
1. Auth - Logs in as admin and saves the generated token.
2. Create Booking - Creates a new booking and saves the bookingid.
3. Update Booking - Updates the booking details using the saved token and booking ID.
4. Verify Booking - Checks the booking to make sure the updates were saved properly.
5. Delete Booking - Deletes the booking and checks for a 201 Created response.

How to Run
1. Import both .json files into Postman.
2. Select the Restful-Booker environment in the top right.
3. Make sure baseUrl is set to https://restful-booker.herokuapp.com.
4. Run the collection using the Postman Collection Runner.
