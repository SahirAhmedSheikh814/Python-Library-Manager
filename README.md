# Personal Library Manager

## 📌 Overview
The **Personal Library Manager** is a command-line program that allows users to manage their book collection efficiently. Users can add, remove, search, and display books, as well as track their reading progress. The program also includes optional file handling to save and load the library.

## 🚀 Features
- **Add a Book**: Add a book to the library with details like title, author, year, genre, and read status.
- **Remove a Book**: Remove a book from the library by title.
- **Search for a Book**: Search books by title or author and display the results.
- **Display All Books**: View the complete list of books in a formatted way.
- **Display Statistics**:
  - Total number of books
  - Percentage of books read
- **File Handling (Optional)**:
  - Save the library to `library.txt` on exit.
  - Load the library from `library.txt` on startup.

## 🛠 Installation
To run this program, follow these steps:

1. Ensure you have **Python 3** installed on your system.
2. Clone this repository or download the `library_manager.py` file.
3. Open a terminal or command prompt and navigate to the project folder.
4. Run the script using:
   ```bash
   python library_manager.py
   ```

## 📖 Usage
When you run the script, you will see the main menu:
```bash
Welcome to your Personal Library Manager!
1. Add a book  
2. Remove a book  
3. Search for a book  
4. Display all books  
5. Display statistics  
6. Exit  
Enter your choice:
```
### 📝 Adding a Book
```bash
Enter the book title: The Great Gatsby
Enter the author: F. Scott Fitzgerald
Enter the publication year: 1925
Enter the genre: Fiction
Have you read this book? (yes/no): yes
Book added successfully!
```

### 🗑 Removing a Book
```bash
Enter the title of the book to remove: The Great Gatsby
Book removed successfully!
```

### 🔍 Searching for a Book
```bash
Search by:  
1. Title  
2. Author  
Enter your choice: 1  
Enter the title: The Great Gatsby  
Matching Books:  
1. The Great Gatsby by F. Scott Fitzgerald (1925) - Fiction - Read
```

### 📚 Displaying All Books
```bash
Your Library:  
1. The Great Gatsby by F. Scott Fitzgerald (1925) - Fiction - Read  
2. 1984 by George Orwell (1949) - Dystopian - Unread
```

### 📊 Viewing Statistics
```bash
Total books: 2
Percentage read: 50.0%
```

## 📂 File Handling (Optional)
- **Saving the Library**: When you exit, the program saves your book collection to `library.txt`.
- **Loading the Library**: When you restart the program, it loads the books from `library.txt`.

```bash
Library saved to file. Goodbye!
```

## 🎯 Submission
Once you've completed the project, submit your work using the provided Google Form:
[Submit Here](https://forms.gle/tS7C3sr55tUZ36GY8)

## 💡 Tips
- Test each feature individually before moving to the next.
- Use comments in your code to explain complex logic.
- Experiment with adding more features like sorting books or filtering by genre.

---
✅ **Happy Coding! 🚀**
