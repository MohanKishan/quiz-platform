# Quiz Platform

A modern, interactive quiz platform for creating, managing, and taking quizzes.

## Features

- Create and manage quizzes
- User authentication and profiles
- Real-time quiz taking experience
- Score tracking and analytics
- Multiple question types support

## Getting Started

### Prerequisites

- Python 3.8+
- pip (Python package installer)
- Virtual environment (recommended)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/MohanKishan/quiz-platform.git
   cd quiz-platform
   ```

2. Create and activate virtual environment
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```

4. Configure environment variables
   ```bash
   cp .env.example .env
   cp config.example.py config.py
   # Edit .env and config.py with your settings
   ```

5. Run the application
   ```bash
   python app.py
   ```

## Project Structure

```
quiz-platform/
├── app.py                 # Main application entry point
├── config.py              # Application configuration
├── requirements.txt       # Python dependencies
├── README.md             # Project documentation
├── .gitignore            # Git ignore rules
├── .env.example          # Environment variables template
├── config.example.py     # Configuration template
├── src/                  # Source code directory
│   ├── models/          # Database models
│   ├── routes/          # API/Web routes
│   ├── services/        # Business logic
│   └── utils/           # Utility functions
├── static/              # Static files (CSS, JS, images)
├── templates/           # HTML templates
├── tests/               # Test files
└── docs/                # Documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

For support, please open an issue on the GitHub repository.
