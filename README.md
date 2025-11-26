# 📸 Social-Media

A modern, Python-based platform designed to connect users, facilitate content sharing, and build a community.

## ✨ Key Features

This project aims to implement core social media functionalities:

* **🔐 User Authentication:** Secure sign-up and login for users.
* **👤 User Profiles:** Dedicated pages for users to view and manage their posts and information.
* **📝 Post Creation:** Ability to create and share text-based posts.
* **❤️ Interaction:** Features like liking/reacting to posts.
* **📰 Feed Generation:** Displaying a personalized feed of posts from all users.

---

## 🛠️ Technology Stack

The application is primarily built using **Python** and leverages the following key components:

| Component | Detail |
| :--- | :--- |
| **Language** | Python 3.x |
| **Dependencies** | Managed via `requirements.txt` |
| **Database** | Local relational database (SQLite, indicated by `test.db`) |
| **Web Framework** | *[]* |

---

## 🚀 Getting Started

Follow these instructions to set up and run the project locally.

### Prerequisites

You need to have the following installed on your system:

* [**Python 3.x**](https://www.python.org/downloads/)
* **`pip`** (Python package installer)

### 1. Installation

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/oxyraptor/Social-Media.git](https://github.com/oxyraptor/Social-Media.git)
    cd Social-Media
    ```

2.  **Create a Virtual Environment**
    It is highly recommended to use a virtual environment to manage dependencies:
    ```bash
    python -m venv venv
    # Activate on Linux/macOS
    source venv/bin/activate
    # Activate on Windows
    .\venv\Scripts\activate
    ```

3.  **Install Dependencies**
    Install all necessary packages listed in `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure Environment Variables**
    Create a copy of the provided `.env` file and fill in your configuration details (Secret Keys, etc.):
    ```bash
    cp .env.example .env # (Use if you provide an example file)
    ```

    > **Note:** If you used a database framework, you may need to run initial database migrations here before starting.

### 2. Running the Application

Start the social media application using the main entry point:

```bash
python main.py

### 2. Running the Application

Start the social media application using the main entry point:





