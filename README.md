_From the product series "Magicodelogy"_

# Oculus Restaurant Management System

> **Note:** This project is **archived** and represents my **first-ever completed group project**. It is a backend server designed for restaurant management, preserved here as a milestone in my development journey.

## 📖 About
**Oculus Restaurant** (formerly Koala Restaurant) is a comprehensive backend system designed to streamline restaurant operations. It provides a RESTful API to handle:
* **Employee Management:** Staff roles and accounts.
* **Menu & Dishes:** Categories, pricing, and details.
* **Order Processing:** Managing customer orders and receipts.

## 🛠️ Tech Stack
* **Runtime:** Node.js
* **Framework:** Express.js
* **Database:** MySQL
* **Cloud Storage:** AWS S3 (for images/assets)
* **Authentication:** JWT (JSON Web Tokens) & Bcrypt

## ⚙️ Prerequisites
To run this server locally, you will need:
1. **MySQL Database:** Local or remote instance.
2. **AWS S3 Bucket:** For storing uploaded assets (with IAM keys).
3. **Node.js:** Installed on your machine.

## 🚀 Setup & Installation

### 1. Database Setup
Import the provided SQL schema into your MySQL database to create the necessary tables.
* Run the script located at: `./database.sql`

### 2. Environment Configuration
Create a `.env` file in the root directory with the following variables:

```env
# Database Configuration
DB_ENDPOINT=your-db-host
DB_USER=your-username
DB_PASSWORD=your-password
DB_NAME=your-schema-name
CONNECTION_LIMIT=10

# Security
JWT_TOKEN=your-secret-token

# AWS S3 Configuration
ACCESS_KEY_AWS=your-access-key
SECRET_KEY_AWS=your-secret-key
DEFAULT_REGION_AWS=your-region
S3_BUCKET_NAME=your-bucket-name
````

### 3\. Install Dependencies

```bash
npm install
```

### 4\. Running the Server

**Development Mode:**

```bash
npm run dev
```

## 🧪 API Testing

API endpoints can be tested using the configuration provided in the `.insomnia` folder. You can import this folder into [Insomnia](https://insomnia.rest/) to see all available requests.

## 📄 License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License**.

  * **Attribution:** You must give appropriate credit.
  * **NonCommercial:** You may not use this material for commercial purposes.

See the [LICENSE](https://www.google.com/search?q=./License) file for more details.

-----

*Maintained by the EHC Team (Legacy)*
