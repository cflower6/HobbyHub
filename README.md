# 📱 HobbyHub

HobbyHub is a modern Kotlin Android app built with Jetpack Compose for tracking your hobbies — shows/movies you're watching, games you're playing, and Pokémon cards you're collecting.

---

## ✨ Features

- 🧠 Track show progress (title, episodes watched)
- 🎮 View and manage games (platforms, playtime, status)
- 🃏 Organize your Pokémon TCG collection (cards, sets, ownership)
- 🔄 Tab-based layout with contextual FABs
- ⚡ Built with Jetpack Compose & Material 3
- 📱 Designed to work on both phones and tablets
- ☁️ (Optional) Sync with a Ktor backend

---

## 📸 Screenshots (Coming Soon)

| Home Screen | Tv show Tab | Game Tab | Pokémon Tab |
|-------------|-----------|----------|-------------|
| ![home](screenshots/home.png) | ![Tv-shows](https://github.com/user-attachments/assets/7c242d3c-b0f1-422e-afed-97b1009426ca)| ![Game](https://github.com/user-attachments/assets/4611a789-42df-4937-8491-3422804dbe91)| ![Card](https://github.com/user-attachments/assets/8f086022-0f4a-4f11-b9b9-88f959cd53a8) |

---

## 🛠️ Tech Stack

| Layer       | Tools                                         |
|-------------|-----------------------------------------------|
| Language    | Kotlin                                        |
| UI          | Jetpack Compose, Material 3                   |
| State       | ViewModel + StateFlow                         |
| Navigation  | Compose TabRow (can use Navigation later)     |
| Backend (Optional) | Ktor API w/ PostgreSQL (Fly.io/Render) |
| Dependency Injection | Hilt (optional)                      |
| Testing     | JUnit, Espresso (planned)                     |

---

## 🧩 Project Structure

![image](https://github.com/user-attachments/assets/dced9700-0689-429c-ba20-a5085109bbbf)

---

🗺️ Roadmap
 
 Add Room or SQLDelight for offline storage

 Connect to Ktor backend (Fly.io or Render)

 Add user authentication

 Enable dark mode & theming

 Add unit & UI tests

---
🤝 Contributions

Pull requests welcome! For major changes, please open an issue first to discuss what you’d like to change.

---
📜 License
MIT

---
🙏 Acknowledgements

RAWG.io for game data

Pokémon TCG API for card info

Jetpack Compose team for changing Android UI forever 💙
