# 👤 And Me

[![Test](https://github.com/alcere/and_me/actions/workflows/main.yml/badge.svg)](https://github.com/alcere/and_me/actions/workflows/main.yml)
[![Ruby](https://img.shields.io/badge/ruby-3.0%2B-red.svg)](https://www.ruby-lang.org/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> A simple yet elegant Ruby project showcasing user representation and object-oriented design.

## ✨ Features

- 🧑‍💼 **User Management**: Clean and simple user representation
- 📧 **Contact Information**: Easy access to user details
- 🚀 **Lightweight**: Minimal dependencies, maximum efficiency
- 🧪 **Test-Ready**: Includes GitHub Actions for continuous integration

## 🚀 Quick Start

### Prerequisites

- Ruby 3.0 or higher
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/alcere/and_me.git

# Navigate to the project directory
cd and_me

# You're ready to go! No additional dependencies needed.
```

## 💡 Usage

### Basic User Creation

```ruby
require_relative 'user'

# Create a new user instance
user = User.new

# Access user information
puts user.name    # => "Harry"
puts user.email   # => "harry@example.com"
```

### Example Output

```
Name: Harry
Email: harry@example.com
```

## 🏗️ Project Structure

```
and_me/
├── user.rb              # Main User class implementation
├── README.md            # This awesome documentation
└── .github/
    └── workflows/
        └── main.yml     # GitHub Actions CI/CD pipeline
```

## 🧪 Testing

Run the included test workflow:

```bash
# Test the User class manually
ruby -e "
require_relative 'user'
user = User.new
puts 'Name: ' + user.name
puts 'Email: ' + user.email
"
```

The project includes automated testing via GitHub Actions. Every pull request and manual trigger runs our test suite.

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add some amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Code Style

- Follow Ruby best practices
- Keep methods simple and focused
- Add comments for complex logic
- Test your changes

## 📋 Roadmap

- [ ] Add more user attributes (age, location, etc.)
- [ ] Implement user validation
- [ ] Add serialization support (JSON/YAML)
- [ ] Create a simple CLI interface
- [ ] Add comprehensive test suite

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with ❤️ using Ruby
- Inspired by clean, simple object-oriented design
- Thanks to the Ruby community for best practices

## 📞 Contact

- **Project Link**: [https://github.com/alcere/and_me](https://github.com/alcere/and_me)
- **Issues**: [Report a bug or request a feature](https://github.com/alcere/and_me/issues)

---

<div align="center">
  <strong>Made with 💻 and ☕</strong>
</div>
