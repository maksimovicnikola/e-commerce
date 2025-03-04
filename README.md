# Angular 19 E-Commerce Application

## Overview
This project is an **Angular 19** application that features a **list of products with detailed views and a shopping cart functionality**. It is built with modern web technologies to ensure a **responsive, scalable, and maintainable** architecture.

## Features
- **Product Listing** – Browse a list of available products.
- **Product Details** – View detailed information about each product.
- **Shopping Cart** – Add, remove, and manage products in the cart.
- **Reactive State Management** – Utilizes **Angular Signals** combined with **RxJS** for efficient and reactive data handling.
- **Modern Styling** – Styled with **Tailwind CSS** for a sleek and responsive UI.
- **Containerized Deployment** – Easily deployable using **Docker**.

## Technologies Used
- **Angular 19** – Frontend framework.
- **Tailwind CSS** – Utility-first CSS framework.
- **Angular Signals & RxJS** – Reactive state management.
- **Docker** – Containerized deployment.

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/) (Latest LTS recommended)
- [Angular CLI](https://angular.io/cli)
- [Docker](https://www.docker.com/)

### Steps to Run Locally
1. **Clone the repository**:
   ```sh
   git clone <repository-url>
   cd <project-folder>
   ```
2. **Install dependencies**:
   ```sh
   npm install
   ```
3. **Run the development server**:
   ```sh
   ng serve
   ```
   The app will be available at `http://localhost:4200/`

### Docker Deployment
1. **Build the Docker image**:
   ```sh
   docker build -t angular-app .
   ```
2. **Run the container**:
   ```sh
   docker run -p 8080:80 angular-app
   ```
   The app will be accessible at `http://localhost:8080/`

## Contributing
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License
This project is licensed under the [MIT License](LICENSE).

