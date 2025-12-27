# random-password-generator
🔐 Random Password Generator (Python)

A simple Python program that generates a random password based on the length provided by the user.
This project is ideal for beginners to understand the use of the random module and basic string manipulation.

📌 Features

🔢 User-defined password length

🎲 Random character selection

🧵 Uses string joining for password creation

⚡ Lightweight & fast

🧑‍🎓 Beginner-friendly code

🛠️ Technologies Used

Python 3

Built-in random module

Basic string operations

📂 Project Structure
Random-Password-Generator/
│
├── password_generator.py   # Main Python file
└── README.md               # Project documentation

▶️ How to Run the Program
1️⃣ Clone the Repository
git clone https://github.com/your-username/Random-Password-Generator.git

2️⃣ Navigate to the Folder
cd Random-Password-Generator

3️⃣ Run the Program
python password_generator.py

🧪 Example Usage
Enter the length of the password: 8
Generated password: y3a1m4sy

📄 Source Code
import random as r

password_length = int(input("Enter the length of the password: "))
characters = "syam143"
password = ''.join(r.choice(characters) for _ in range(password_length))
print("Generated password:", password)

⚠️ Limitations

Uses a fixed set of characters

Not suitable for high-security applications

No validation for password length

🚀 Future Enhancements

Add uppercase and lowercase letters

Include special characters

Create a strong password mode

Add GUI using Tkinter

Save passwords to a file

📚 Learning Outcomes

This project helps you learn:

Python random module

String manipulation

User input handling

Looping with range()

👨‍💻 Author

Syam Sundar
📍 India
💡 Python | Java | Beginner Developer

📄 License

This project is open-source and free to use for learning and educational purposes.

⭐ If you like this project, please star the repository on GitHub!
