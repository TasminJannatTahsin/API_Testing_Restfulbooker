🧪 Restful Booker API Testing:

A Postman API testing project created to practice REST API testing, CRUD operations, authentication, environment variables, JavaScript assertions, and Newman reporting using the Restful Booker API.

🔗 API Documentation:

📚 Restful Booker API Documentation:

https://restful-booker.herokuapp.com/apidoc/

🎯 Project Objective

The objective of this project is to validate the main Restful Booker API workflows using Postman and Newman.

The collection covers:
1. 🔎 Get all Booking IDs
2. ➕ Create a Booking
3. 🔍 Get a Specific Booking
4. 🔐 Create Authentication Token
5. ✏️ Update Booking using PUT
6. 🛠️ Update Booking using PATCH
7. 🗑️ Delete Booking
8. ✅ Response validation and assertions
9. 📊 Newman HTML reporting

🛠️ Tools & Technologies:
1. 🧪 Postman
2. 🚀 Newman
3. 📊 Newman HTML Extra Reporter
4. 🌐 REST API
5. 📄 JSON
6. 💻 JavaScript

📂 Postman Collection:

The collection shown in the project contains these requests:

CollectionforAPI

│

├── GET  GetBookingIds

├── POST CreateBooking

├── GET  GetSpecificBookingId

├── POST CreateToken

├── PUT  UpdateBooking

├── PATCH UpdateBooking

├── DEL  DeleteBooking

└── GET  GetSpecificBookingId

🔐 Environment Variables:

The project uses a Postman environment to manage reusable values such as: base_url,booking_id,token,fname,lname,tprice,dpaid,checkin,checkout,additionalneeds

✅ Testing & Assertions:

The collection contains assertions to validate important API behavior, such as:

1. ✔️ Status code
2. ✔️ Response time
3. ✔️ Response body
4. ✔️ Required properties
5. ✔️ Data types
6. ✔️ Booking ID
7. ✔️ Authentication token
8. ✔️ Expected response values

📊 Newman Test Report:

The report shown above contains:

1. Total requests
2. Total assertions
3. Failed tests
4. Skipped tests
5. Total iterations
6. Total run duration
7. Average response time
8. Request/test execution summary

▶️ How to Run with Postman

1. Import the Collection

Open Postman.

Click Import.

Select:CollectionFORAPI.postman_collection.json

Click Import.

2. Import the Environment

Click Import.

Select:EnvironmentForAPI.postman_environment.json

Click Import.

Select the imported environment from the environment dropdown.

🚀 Run with Newman:

First, install Newman globally if it is not already installed:
npm install -g newman

Check the Newman installation:

newman -v
Run the collection:

newman run CollectionforAPI.postman_collection.json -e EnvironmentforAPI.postman_environment.json

📊 Generate an HTML Extra Report:

If the HTML Extra reporter is installed:

npm install -g newman-reporter-htmlextra

Then run:

newman run CollectionforAPI.postman_collection.json -e EnvironmentforAPI.postman_environment.json -r htmlextra --reporter-htmlextra-export API_Report_newman.html

⭐ Project Purpose:

This project was created for API testing practice and portfolio demonstration, using the Restful Booker API as a testing playground.

👨‍💻 Author:

Tasmin Jannat Tahsin
