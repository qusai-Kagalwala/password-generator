# 🔐 Password Generator

![Python](https://img.shields.io/badge/Python-3.6+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)
![Course](https://img.shields.io/badge/Course-Angela%20Yu%20100%20Days-orange.svg)

A customizable Python password generator that creates secure passwords with user-specified numbers of letters, symbols, and numbers, with options for ordered or shuffled character arrangement.

## ✨ Features

🔤 **Customizable Character Types**: Choose exactly how many letters, symbols, and numbers you want  
🎲 **Randomization Options**: Generate passwords in order or completely shuffled  
🛡️ **Security Focused**: Creates strong, unpredictable passwords  
💻 **Easy to Use**: Simple command-line interface  
⚡ **Fast Generation**: Instant password creation  

## 🚀 Getting Started

### Prerequisites

- 🐍 Python 3.6 or higher

### Installation

1. Clone the repository:
```bash
git clone https://github.com/qusai-Kagalwala/password-generator.git
```

2. Navigate to the project directory:
```bash
cd password-generator
```

3. Run the program:
```bash
python main.py
```

## 📖 How to Use

1. **Run the program** 🏃‍♂️
2. **Choose password type**: Type 'easy' for ordered or 'hard' for shuffled 🎯
3. **Enter the number of letters** you want (e.g., 8) 📝
4. **Enter the number of symbols** you want (e.g., 4) 🔣
5. **Enter the number of numbers** you want (e.g., 2) 🔢

### Example Usage

```bash
Choose password type: Type 'easy' for ordered or 'hard' for shuffled: hard
How many letters would you like in your password? 8
How many symbols would you like? 4
How many numbers would you like? 2

Your password is: a2!bK#c$dF1efgh
```

**Easy Mode**: Letters → Symbols → Numbers (e.g., `abcdefgh!#$%12`)  
**Hard Mode**: Completely shuffled characters (e.g., `2a!bK#$d1F`)  

## 🎯 Password Strength

The generator uses:
- **Letters**: a-z, A-Z (52 characters total)
- **Symbols**: ! # $ % & ( ) * + (9 special characters)
- **Numbers**: 0-9 (10 digits)

**Easy Mode**: Creates predictable pattern - letters first, then symbols, then numbers  
**Hard Mode**: Randomly shuffles all characters for maximum security 🔒

## 🛠️ Technical Details

- **Language**: Python 🐍
- **Libraries Used**: `random`, `string` (built-in modules)
- **Key Features**:
  - List comprehensions for efficient character generation
  - `random.choice()` for secure character selection
  - `random.shuffle()` for hard mode randomization
  - User input validation with `.lower()` for mode selection
- **Character Pools**: ASCII letters, selected symbols, and digits

## 📁 Project Structure

```
password-generator/
│
├── main.py          # Main application file
├── README.md        # Project documentation
└── LICENSE          # License file
```

## 🎓 Learning Journey

This project was created as part of Angela Yu's "100 Days of Code: The Complete Python Pro Bootcamp" course. It demonstrates:

- Working with Python lists and the `string` module
- Random character selection using `random.choice()`
- List comprehensions for clean, efficient code
- User input handling and string manipulation
- Conditional logic (easy vs hard mode)
- String joining and list shuffling techniques

## 🤝 Contributing

![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)

Contributions are welcome! Feel free to:

1. 🍴 Fork the project
2. 🌟 Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. 💾 Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. 📤 Push to the branch (`git push origin feature/AmazingFeature`)
5. 🎉 Open a Pull Request

## 💡 Ideas for Enhancement

- 🎨 Add GUI interface
- 💾 Save passwords to file
- 📊 Password strength meter
- 🔄 Batch password generation
- 📋 Copy to clipboard functionality
- 🚫 Exclude similar characters option

## 📄 License

![MIT License](https://img.shields.io/badge/License-MIT-yellow.svg)

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Qusai Kagalwala**
- GitHub: [@qusai-Kagalwala](https://github.com/qusai-Kagalwala)
- ![Profile Views](https://komarev.com/ghpvc/?username=qusai-Kagalwala&color=blue)

## 🙏 Acknowledgments

- 👩‍🏫 Angela Yu for the amazing Python course
- 💡 The Python community for inspiration
- 🔐 Security best practices from OWASP

---

![GitHub stars](https://img.shields.io/github/stars/qusai-Kagalwala/password-generator?style=social)
![GitHub forks](https://img.shields.io/github/forks/qusai-Kagalwala/password-generator?style=social)
![GitHub watchers](https://img.shields.io/github/watchers/qusai-Kagalwala/password-generator?style=social)

⭐ **Star this repository if you found it helpful!** ⭐

**Made with ❤️ and Python** 🐍
