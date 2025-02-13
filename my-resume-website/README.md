# My Resume Website

This project is a dynamic web application that displays a resume in an attractive format. The content of the resume changes as the user scrolls down the page, providing an engaging experience.

## Features

- Attractive layout and design for showcasing your resume.
- Dynamic content that updates as you scroll.
- Built using Flask, a lightweight web framework for Python.

## Project Structure

```
my-resume-website
├── app
│   ├── __init__.py
│   ├── routes.py
│   ├── static
│   │   ├── css
│   │   │   └── styles.css
│   │   └── js
│   │       └── scripts.js
│   ├── templates
│   │   └── index.html
│   └── models.py
├── requirements.txt
├── run.py
└── README.md
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd my-resume-website
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To run the application, execute the following command:
```
python run.py
```

The application will be available at `http://127.0.0.1:5000/`.

## License

This project is licensed under the MIT License.