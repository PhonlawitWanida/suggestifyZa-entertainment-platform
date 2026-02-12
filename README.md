<img width="1051" height="473" alt="image" src="https://github.com/user-attachments/assets/2d996e29-3311-42ff-886d-e7193b5d8990" /># suggestifyZa-entertainment-platform
# 🎬 SuggestifyZa: Anime & K-Drama Review Platform

**SuggestifyZa** is a community-driven web platform designed to solve the "Paradox of Choice" for Asian entertainment fans. It provides a centralized hub to discover, rate, and manage watchlists for both Anime and Korean Dramas.

<img width="1067" height="499" alt="image" src="https://github.com/user-attachments/assets/d4a67ccb-c017-4a0f-a909-c2701255ce04" />
<img width="1051" height="473" alt="image" src="https://github.com/user-attachments/assets/28dfc8f6-a3e5-4643-8ac3-723c6c3144ab" />
<img width="1051" height="494" alt="image" src="https://github.com/user-attachments/assets/dcb45b23-d5e8-4f9b-bc21-f9ce44ced715" />
<img width="1053" height="455" alt="image" src="https://github.com/user-attachments/assets/301f37ce-36d9-42e8-85af-3e84e11121aa" />
<img width="1059" height="494" alt="image" src="https://github.com/user-attachments/assets/0e0b1234-db63-4453-b940-6badd452b36b" />
<img width="1055" height="576" alt="image" src="https://github.com/user-attachments/assets/ddc3a6a9-7dd7-446d-9bb2-fad5f601ab07" />
<img width="1065" height="571" alt="image" src="https://github.com/user-attachments/assets/cacd8486-f007-464e-84c0-431f8b5ffb44" />
<img width="978" height="784" alt="image" src="https://github.com/user-attachments/assets/4c48b1de-bdd2-4ce7-bb7c-4bace54305e8" />


---

### 📖 About The Project
Developed as part of the **Web Programming (DE251)** course, this project aims to help users decide *"What to watch next?"* in the world of Asian entertainment.

## 🚀 Key Features

* **🌟 Content Discovery:** Curated lists of trending titles (e.g., Start-Up, Demon Slayer) with category filtering.
* **✍️ Community & Reviews:** Users can post comments and rate shows. The system dynamically calculates average scores.
* **👤 Personalization:** Customize profiles with **Avatar Uploads** and manage a private **Watchlist**.
* **🔐 Security:** Secure Login/Register system with PHP session management.

* ## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Grid System), JavaScript (DOM Manipulation).
* **Backend:** PHP (Native) for server-side logic and session handling.
* **Database:** MySQL (Relational Database).
* **Architecture:** MVC-inspired structure (Separating Logic, View, and Database).

* ## 💾 Database Structure

| Table | Description |
| :--- | :--- |
| `users` | Stores user credentials, email, and profile image paths. |
| `content` | Metadata for Anime & K-Dramas (Title, Genre, Description). |
| `reviews` | Stores user comments and ratings (Linked to users and content). |
| `watchlist` | Many-to-Many relationship table for user's saved items. |

## ⚙️ Installation Guide (Localhost)

1. Clone the repository
   git clone [https://github.com/YOUR_USERNAME/suggestifyZa.git](https://github.com/YOUR_USERNAME/suggestifyZa.git)

2. Setup Web Server
   - Use XAMPP or WAMP.
   - Move the project folder to htdocs (XAMPP) or www (WAMP).

3. Import Database
   - Open phpMyAdmin (http://localhost/phpmyadmin).
   - Create a new database named "suggestify_db".
   - Import the "SQL_WEB.sql" file provided in this repository.

4. Configure Connection
   - Open "db_connection.php" and verify that the database credentials match your local MySQL settings.

5. Run the Project
   - Open your browser and navigate to: http://localhost/suggestifyZa/index.php

### 6. ทีมพัฒนา (Team)
```markdown
## 👥 Development Team
* **Phonrawat Limfaguang** - Fullstack Developer & Database Design
* **Pannathorn** - Frontend & UX/UI
* **Phonlawit** - Content Management & Testing

