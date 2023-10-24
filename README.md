# Running Jupyter Notebook with Docker Compose

This project provides a simple way to run Jupyter Notebook with Docker Compose.

## Prerequisites

- Docker
- Docker Compose

## Usage

1. Clone this repository:

    ```sh
    git clone https://github.com/your-username/your-repo.git
    ```

2. Navigate to the cloned repository:

    ```sh
    cd your-repo
    ```

3. Run the following command to start the Jupyter Notebook server:

    ```sh
    docker-compose up -d
    ```

4. Open your web browser and navigate to `http://localhost:8888`.

5. When prompted for a password, enter `admin`.

6. You should now be able to create and run Jupyter notebooks.

7. In VScode select the kernel jupyter notebook to run the code.

## Additional Information

- The `docker-compose.yml` file specifies the configuration for the Docker containers.



