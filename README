# Docker template for Kong project

This is a docker-compose template to run a basic vesion of the docker project.

## How to use

### 1. Clone repository

Clone this repository to your local machine. `git clone git@github.com:gilderlan/kong-compose.git my_project_name`.

### 2. Create kong database

1. In the root folder of the project, run the command `docker-compose up -d db` to up the database container.
2. Wait for database container to be ready and run the command `docker-compose exec db psql -U postgres -c "CREATE DATABASE kong;"` to create kong database.
3. Run the command `docker-compose run kong kong migrations bootstrap` to create database schema.

### 3. Start Kong

Run the command `docker-compose up -d`.

## Contributing

If you would like to contribute to this project, please open an issue or submit a pull request.

## License

This project is licensed under the MIT license. See the [LICENSE](LICENSE) file for more details.
