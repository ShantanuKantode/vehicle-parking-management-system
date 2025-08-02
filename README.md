# 🚗 Vehicle Parking Management System (VPMS)

A web-based vehicle parking management system built using **Streamlit** and **MySQL**. This app helps manage vehicle entries, exits, and current parking status efficiently with a simple user interface.

---

## 📌 Features

- ➕ **Add Vehicle** — Enter details like vehicle name, owner, contact, type, and auto-calculate charges.
- 🗑️ **Remove Vehicle** — Exit a vehicle from the parking lot.
- 🚗 **View Parked Vehicles** — See all currently parked vehicles in a tabular format.
- ⚙️ **Custom Parking Limit** — Set a default or custom parking limit via sidebar.
- 🖼️ **Responsive UI** — Built with Streamlit and Streamlit-Lottie for animations.

---

## 🛠️ Tech Stack

| Layer      | Technology       |
|------------|------------------|
| Frontend   | Streamlit        |
| Backend    | Python, MySQL    |
| Animations | streamlit-lottie |
| Data       | MySQL (XAMPP)    |
| Config     | dotenv           |

---

## 🗃️ Database Schema

Database: `vehicle_management`

### Table: `vehicles`

| Column          | Type         |
|-----------------|--------------|
| `id`            | INT (AUTO_INCREMENT) |
| `vehicle_name`  | VARCHAR(255) |
| `owner_name`    | VARCHAR(255) |
| `contact_number`| VARCHAR(20)  |
| `vehicle_type`  | VARCHAR(50)  |
| `charges`       | DECIMAL(10,2)|

---

## 🔧 Installation & Setup
    pip install -r requirements.txt
    
