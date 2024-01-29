## E-Commerce Web Project "FlaskMarket"

Welcome to our e-commerce web project repository! This project aims to provide a learning platform for building web applications using Python and Flask while utilizing pseudo-real data from the FakeStoreAPI. Additionally, we'll set up a CI/CD pipeline using GitHub Actions to automate the testing and deployment process.

### Project Overview

The main goal of this project is to create a web application that displays e-commerce product data fetched from the [FakeStoreAPI](https://fakestoreapi.com/products/). By using Flask, a Python micro-framework, we'll build a simple yet functional web interface to showcase these products.

### Features

- Fetch product data from the FakeStoreAPI.
- Display product information including name, price, description, and image.
- Implement basic navigation and user interface for browsing products.
- Set up a CI/CD pipeline with GitHub Actions for automated testing and deployment.

### Technologies Used

- **Python**: The primary programming language for backend development.
- **Flask**: A micro web framework for Python to build web applications.
- **HTML/CSS**: For structuring and styling the web pages.
- **GitHub**: Hosting our repository and managing CI/CD pipelines.
- **FakeStoreAPI**: Providing pseudo-realistic product data for our application.

### Getting Started

1. **Clone the Repository**: Clone this repository to your local machine.

    ```bash
    git clone https://github.com/saitnyalcin/FlaskMarket.git
    ```

2. **Install Dependencies**: Make sure you have Python and Flask installed. You can install Flask using pip.

    ```bash
    pip install Flask
    ```

3. **Run the Application**: Start the Flask server to run the application locally.

    ```bash
    python app.py
    ```

4. **Access the Application**: Open your web browser and navigate to `http://localhost:5000` to view the application.

### Contributing

We welcome contributions from the community! If you have any ideas for improvements or new features, feel free to open an issue or submit a pull request

### CI/CD Pipeline

This repository is configured with a CI/CD pipeline using GitHub Actions. Upon pushing changes to the `main` branch, the pipeline will automatically run tests and deploy the application if all tests pass successfully.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

We would like to express our gratitude to the creators of the FakeStoreAPI for providing a valuable resource for educational purposes. Special thanks to all contributors and collaborators who help improve this project.
