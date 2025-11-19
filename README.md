# City Library Digital Management System  
A Java-based console application for managing books, members, and library transactions using **File Handling** and the **Java Collections Framework**.

This project is created as part of **Java Programming – Assignment 4** (B.Tech / BCA / BSc, Semester 3).

---

Features
   Book Management
  - Add new books  
  - Auto-generate unique Book IDs  
  - Issue and return books  
  - Search books by:
    - ID
    - Title
    - Author
    - Category  
- Sort books:
  - By title (Comparable)
  - By author (Comparator)

### 🧑‍🤝‍🧑 Member Management
- Add new members  
- Auto-generate unique Member IDs  
- Track issued books  

### 💾 File Handling
- Persistent storage using:
  - `books.txt`
  - `members.txt`
- Uses:
  - `FileReader`, `FileWriter`
  - `BufferedReader`, `BufferedWriter`

### 🗂 Java Collections Used
- `Map<Integer, Book>` for books  
- `Map<Integer, Member>` for members  
- `List<Integer>` for issued books  
- `Set<String>` for unique categories  
- `Comparator` for custom sorting  

---

## 📂 Project Structure

