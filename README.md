# strapi sandbox

## Access

- [Strapi](http://localhost:1337/admin)
- [Web](http://localhost:3000)

## Installation

1. Clone the repository
2. Copy the `.env.example` file to `.env`
   ```shell
   cp .env.example .env
   cp ./admin/.env.example ./admin/.env
   ```
3. Install the dependencies
   ```shell
    docker compose run --rm strapi npm install
    docker compose run --rm web npm install
    ```
4. Run the application
    ```shell
    docker compose up -d
    ```
5. Open the browser at Strapi and Web
