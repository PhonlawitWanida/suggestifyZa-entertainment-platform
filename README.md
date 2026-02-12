# suggestifyZa-entertainment-platform
# 🎬 SuggestifyZa: Anime & K-Drama Review Platform

**SuggestifyZa** is a community-driven web platform designed to solve the "Paradox of Choice" for Asian entertainment fans. It provides a centralized hub to discover, rate, and manage watchlists for both Anime and Korean Dramas.

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

```text
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


---

### 6. ทีมพัฒนา (Team)
```markdown
## 👥 Development Team
* **Phonrawat Limfaguang** - Fullstack Developer & Database Design
* **Pannathorn** - Frontend & UX/UI
* **Phonlawit** - Content Management & Testing
