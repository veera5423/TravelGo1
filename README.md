![Screenshot 2025-07-02 155340](https://github.com/user-attachments/assets/ac2b435b-ea13-4f2e-90f1-3aa4974570bf)# TravelGo – Your All-in-One Travel Booking Companion

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

## 📷 Screenshots 

> *These will visually showcase the user experience.*

* [Welcome pages](https://github.com/user-attachments/assets/a2b789de-000e-4ac5-8125-0c92e58ffd1d)
 ] [2](https://github.com/user-attachments/assets/d54f4358-4047-4992-a166-5237278d7bd4)
![3](https://github.com/user-attachments/assets/146abdbe-bafc-4c0d-a4ef-440b1deacd20)

 Home Page with Search Forms
 *[Login Page](https://github.com/user-attachments/assets/27709bca-65be-4cb6-91c7-1810823b69b1)
 *[Register Page](https://github.com/user-attachments/assets/5077e5c4-f811-4538-aea3-caf13bf3fbcf)
 *[dashboard](https://github.com/user-attachments/assets/73ac7900-06a4-4516-81e7-524bace70672)
 *![bus booking](https://github.com/user-attachments/assets/8dcec84e-f2c3-45e2-b0ca-f26f6519fff8)
 *![train booking](https://github.com/user-attachments/assets/e87bafe9-d2dc-4cec-9d5f-e2472f485128)
 *![confirmation page](https://github.com/user-attachments/assets/a11d6307-f4fb-449a-accd-4b309932f989)
 ![flight page](https://github.com/user-attachments/assets/830b3c73-8130-4917-b6f6-629639b604f2)
 ![hotel booking](https://github.com/user-attachments/assets/7470c7a7-14d3-4d0b-8364-4ea8a6d924ea)
 ![Booking History](https://github.com/user-attachments/assets/edad84be-bb0a-4452-b13b-ab3d90f5b68f)







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
