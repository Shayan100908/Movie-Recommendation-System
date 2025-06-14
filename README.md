# Movie-Recommendation-System
# 🎬 Movie Recommendation System in C

This is a simple console-based **Movie Recommendation System** written in **C language**. The program loads movie data from a `movies.txt` file and recommends movies based on the user's **age**, **preferred genres**, and **language**. It is beginner-friendly and designed for quick filtering and structured output using a clean console interface.

---

## 🚀 Features

- 📂 Loads movie data from a text file
- 🎯 Filters movies based on:
  - Age Limit
  - Genre Preferences (up to 3)
  - Language Preference
- 📋 Displays matching movie details neatly in console
- 📊 Supports up to 100 movies and 3 genres per movie
- 🔍 Simple menu-based genre and language selection

---

## 📁 movies.txt Format

Each movie must be listed in the `movies.txt` file using the following format:

Title|Genre1,Genre2,Genre3|Language|AgeLimit|Rating


### ✅ Example:

Inception|Action,SciFi,Thriller|English|13|8.8
Coco|Animation,Adventure,Family|English|7|8.4
Dangal|Drama,Sports,Biography|Hindi|10|8.5


> Make sure there are **no extra spaces** and every field is separated by `|`. Genres must be separated by commas.

---

## 📦 How to Compile and Run

1. **Create** a file named `movies.txt` in the same directory as your code.
2. **Paste** at least 10–30 movies using the format above.
3. Compile the program:

```bash
gcc -o recommender main.c
./recommender

Or on Windows:

gcc -o recommender main.c
recommender.exe

🧑‍💻 User Input Flow

    Enter your age

    Choose your top 3 genres from a displayed list

    Choose your preferred language

    See movie recommendations!

💡 Example Output

Enter your age: 15

Choose a genre:
1. Action
2. Comedy
3. Drama
...
Genre 1: 2
Genre 2: 3
Genre 3: 5

Choose a language:
1. English
2. Hindi
3. Urdu
Language: 1

Recommended Movies:

Title: Dangal
Genres: Drama, Sports, Biography
Language: Hindi
Age Limit: 10+
Rating: 8.5

📚 Requirements

    GCC Compiler (Linux/Windows)

    Basic knowledge of C

📌 Author

Developed by Shayan Muhammad
📧 Email: [your-email@example.com]
🌐 GitHub: [github.com/yourusername]
📜 License

This project is open-source and free to use for educational and personal use. No warranties or guarantees.


---

Let me know if you want this tailored with your GitHub profile link, personal info, or extra    🎬 Movie Recommendation System in C — A console-based C program that recommends movies based on user’s age, language, and genre preferences. It reads movie data from a file, uses structured filtering, and provides a simple menu-driven UI.
