# Dormigo 🏠

**Dormigo** is a no-brokerage accommodation booking platform designed for students and working professionals. It offers easy access to PGs, flats, hostels, and hotels in major cities of Tamil Nadu. The platform features secure booking, rental agreement management, and dashboards for both users and property owners.

---

## 🌐 Website Features

### 👤 User Dashboard
- Browse and filter properties (by location, type, amenities, etc.)
- Book PGs, hostels, flats, and hotels
- Secure online payments
- Generate and download rental agreements
- View booking history
- Notifications and alerts
- Profile setup and management
- Chatbot assistance

### 🏢 Owner Dashboard
- Add, view, and remove properties
- Upload ownership documents (mandatory)
- Manage and approve booking requests
- Notifications for booking activity
- Set a 3-month minimum notice period for property removal
- Profile and account management

---

## 🔐 Security Highlights
- Government ID verification for users (Aadhar/PAN)
- Ownership proof required for property listings
- Fraud prevention through document validation
- Notification system for property removal

---

## 🛠️ Tech Stack

| Frontend       | Backend      | Database    | Authentication  |
|----------------|--------------|-------------|------------------|
| HTML, CSS, JS  | Django       | Firebase    | Google, FB, Apple Login |

---

## 🏁 Getting Started

### Prerequisites
- Python 3.8+
- Node.js (if required for frontend build tools)
- Firebase account
- Django installed (`pip install django`)
- Firebase SDK and dependencies

### Installation
1. Clone the repository:

   git clone https://github.com/your-username/dormigo.git
   cd dormigo


2. Set up virtual environment:

  
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
  

3. Install dependencies:

  
   pip install -r requirements.txt
  

4. Configure Firebase and environment variables:

   * Add your Firebase config in the designated `firebase_config.js` or backend settings.
   * Setup `.env` file if needed for secret keys.

5. Run migrations and start server:

   
   python manage.py migrate
   python manage.py runserver
  

---

## 📂 Folder Structure

dormigo/
├── frontend/
│   └── templates/
├── backend/
│   └── django project files
├── static/
├── firebase/
│   └── firestore and auth configs
├── README.md
├── requirements.txt
└── .env (ignored)


---

## ✨ Future Enhancements

* Mobile app using Flutter
* AI-based property recommendation
* Advanced admin dashboard
* Integration with government databases for ID verification

---

## 🤝 Contributing

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📧 Contact

Created with ❤️ by **Team Dormigo**
Email: \[[your-email@example.com](mailto:your-email@example.com)]
LinkedIn: \[Your LinkedIn]

---

## 📝 License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

Would you like me to also generate a `LICENSE` file or add badges (build, license, etc.) for the README?

