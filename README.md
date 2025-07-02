# TravelGo – Your All-in-One Travel Booking Companion

TravelGo is a full-stack travel booking web application developed with **Flask**, **MongoDB**, and integrated AWS services including **DynamoDB**, **SNS**, **IAM Roles**, and **EC2**. It allows users to search, filter, and book **buses**, **trains**, **flights**, **cabs**, and **hotels** with real-time seat selection, sorting, booking confirmation, and account management.

> 🚀 **Live Demo**: \[Coming Soon]


> 📂 **AWS DynamoDB Tables**: `travelgo_users`, `trains`, `bookings`

---

## 🌍 Features

* 🚌 **Bus Booking**: Filter by city, date, class, women-only seats, real-time seat selection
* ✈️ **Flight Booking**: Search by destination, date, time, and seat selection
* 🚕 **Cab Booking**: Search, display available cabs, and confirm booking
* 🏨 **Hotel Booking**: Sort/filter by price and rating, view and book hotels
* 👤 **User Dashboard**: View current and past bookings in a sidebar
* 🚀 **Technologies Used**:

  * Frontend: HTML, CSS, JavaScript, Bootstrap, AJAX
  * Backend: Flask, Python
  * Database:  AWS DynamoDB
  * Hosting: AWS EC2
  * Notifications: AWS SNS
  * Security: IAM roles for service access

---

## 🔄 Architecture & AWS Integration

* 🧰 **DynamoDB** for train and bookings data storage
* ✉️ **SNS (Simple Notification Service)** for booking notifications
* ⚖️ **IAM Roles** securely grant permissions to EC2 for accessing SNS and DynamoDB
* 💻 **EC2** hosts the Flask application for public access

---

## 📚 How to Run Locally

```bash
# Clone the repo
$ git clone https://github.com/yourusername/TravelGo
$ cd TravelGo

# Setup environment
$ python -m venv venv
$ source venv/bin/activate  # or venv\Scripts\activate on Windows
$ pip install -r requirements.txt

# Configure .env with MongoDB and AWS credentials
MONGO_URI=your_mongodb_connection
AWS_ACCESS_KEY=your_aws_access_key
AWS_SECRET_KEY=your_secret_key
REGION=your_region

# Run Flask server
$ flask run
```

---

## 📷 Screenshots (To be uploaded)

> *These will visually showcase the user experience.*

* [ ] Home Page with Search Forms
* [ ] Bus Results with Filters
* [ ] Flight Booking Confirmation
* [ ] Seat Selection Interface
* [ ] User Dashboard with Booking History

---

## 🚀 Future Improvements

* 🤖 Add Chatbot for trip planning
* 📅 Calendar-based flexible date search
* ⭐ User ratings and reviews for hotels/cabs
* 📆 Admin panel for managing listings

---

## 🎉 Author

Built by Veeranjaneyulu.Vipparla — Passionate about building user-focused travel platforms.

> For questions or collaboration: [veeranjaneyuluvipparla.2109@gmail.com](mailto:veeranjaneyuluvipparla.2109@gmail.com)
