# Project Title

Explore Bikeshare Data

## Description

This project explores data related to bike sharing in three major cities in the United States: Chicago, New York City, and Washington, D.C. The purpose of this project is to understand bike usage patterns, identify peak usage times, and provide insights into the user demographics.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

To run this project, you need to have Docker and Docker Compose installed on your system. Follow the instructions below to set up and run the project using Docker Compose:

1. **Install Docker**: Download and install Docker from the official website: [Docker](https://www.docker.com/get-started).

2. **Install Docker Compose**: Docker Compose is included in Docker Desktop for Windows and Mac. For Linux, follow the installation instructions: [Docker Compose Installation](https://docs.docker.com/compose/install/).

3. **Clone the Repository**: Clone this repository to your local machine.

    ```sh
    git clone https://github.com/fedevita/r-post-your-work-on-github
    ```

4. **Run Docker Compose**: Use Docker Compose to build and start the containers.

    ```sh
    docker-compose up --build
    ```

   This command will build the Docker image and start the Jupyter Notebook server.

5. **Access the Jupyter Notebook**: Once the containers are up and running, you can access the Jupyter Notebook by navigating to `http://localhost:8888` in your web browser. Use the token provided in the terminal output to log in.

## Usage

To use this notebook, open the `Explore_bikeshare_data.ipynb` file in the Jupyter Notebook interface and run the cells sequentially. The notebook will guide you through the analysis process, including loading the data, cleaning the data, and performing various analyses.

## Data

The data used in this project comes from three sources:
1. **Chicago**: `chicago.csv`
2. **New York City**: `new_york_city.csv`
3. **Washington, D.C.**: `washington.csv`

The data includes information on the start and end times of trips, the duration of trips, the start and end stations, and user information such as user type, gender, and birth year.

## Contributing

If you want to contribute to this project, you can fork the repository and create a pull request. Please make sure to follow the guidelines below:

- Write clear and concise commit messages.
- Ensure that your code follows the PEP 8 style guide.
- Include comments and docstrings in your code.
- Write unit tests for any new functionality.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact

If you have any questions or feedback, feel free to reach out:

- **Email**: federico.vita1997@gmail.com
- **GitHub**: [fedevita](https://github.com/fedevita)