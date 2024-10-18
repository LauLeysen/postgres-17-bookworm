
# PostgreSQL with Docker Compose

This project sets up a PostgreSQL database with preconfigured tables (modify init.sql).

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   ```

2. **Place your `init.sql`** with the table creation script.

3. **Run Docker Compose**:
   ```bash
   docker-compose up
   ```

4. **Access the database**:
Make sure to change the docker-compose.yaml file for the database configuration user etc
   ```bash
   psql -h localhost -U postgres -d mydatabase
   ```

5. **Stop the service**:
   ```bash
   docker-compose down
   ```

## License
Licensed under the MIT License.
