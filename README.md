# Web Application with Instant Dictionary

This repository contains a web application that provides an instant English dictionary. It allows users to quickly look up the definitions of English words as they type. The application is built using the JustPy framework and offers a user-friendly interface.

## Features

- **Instant Definitions:** Get the definition of any English word instantly as you type.
- **Multiple Pages:** The application consists of multiple pages - Home, Dictionary, and About.
- **Navigation:** Use the navigation menu to switch between different pages.

## Getting Started

Follow these steps to run the web application locally on your machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:

   ```bash
   python main.py
   ```

4. Open your web browser and visit [http://localhost:8001](http://localhost:8001) to access the web application.

## Pages

### Home Page

The Home page provides general information about the application and its features.

### Dictionary Page

The Dictionary page allows users to input English words and receive instant definitions as they type. Definitions are fetched from a pre-defined dataset.

### About Page

The About page provides additional information about the application and its purpose.

## Project Structure

- `main.py`: Main entry point for running the application.
- `definition.py`: Defines the `Definition` class responsible for fetching word definitions.
- `design/`: Contains design-related assets such as images and design.txt.
- `examples/`: Contains example HTML and Python code.
- `webapp/`: Main application folder containing different pages and layout components.
  - `about.py`: About page implementation.
  - `dictionary.py`: Dictionary page implementation.
  - `home.py`: Home page implementation.
  - `layout.py`: Layout components for navigation and styling.
  - `page.py`: Abstract base class for page implementations.
- `data.csv`: Dataset containing word definitions.

## Dependencies

- JustPy: Python web framework used for building the web application.
- Pandas: Data manipulation library used for reading the dataset.
- Requests: Library for making HTTP requests to fetch word definitions.

## Future Enhancements

- Improve the accuracy of word definitions by using more comprehensive datasets.
- Implement user authentication and personalization features.
- Enhance the layout and styling for a better user experience.
- Add more interactive features to engage users.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---
