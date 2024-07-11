# Warehouse Space Optimization

This project aims to optimize warehouse space by utilizing a Streamlit web application. Users can input warehouse dimensions, obstacles, product dimensions, demand, current supply, and fragility. The application creates a 3D matrix representing the warehouse layout and employs a genetic algorithm to determine the optimal placement of products based on various factors.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Input Warehouse Details**: Users can input dimensions of the warehouse, including length, width, and height, as well as specify entrances, obstacles, and pathways.
- **Product Information**: Users provide details of each product, including dimensions, demand, current supply, and fragility (boolean value).
- **3D Matrix Representation**: The application generates a 3D matrix representing the warehouse layout, considering obstacles and pathways.
- **Genetic Algorithm Optimization**: Based on product dimensions, demand, current supply, and fragility, the genetic algorithm determines the optimal placement of products within the warehouse to maximize space utilization and minimize retrieval times.

## Installation

### Prerequisites

- Python 3.7 or higher

### Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/warehouse-space-optimization.git
    cd warehouse-space-optimization
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the Streamlit application:
    ```sh
    streamlit run warehouse_app.py
    ```

## Usage

1. Open the Streamlit application in your web browser.
2. Input the warehouse dimensions, including length, width, and height.
3. Specify entrances, obstacles, and pathways within the warehouse.
4. Provide details for each product, including dimensions, demand, current supply, and fragility.
5. Click the button to generate the 3D matrix representing the warehouse layout.
6. Run the genetic algorithm to determine the optimal placement of products within the warehouse.


## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/my-feature`.
3. Commit your changes: `git commit -m 'Add my feature'`.
4. Push to the branch: `git push origin feature/my-feature`.
5. Open a pull request.
