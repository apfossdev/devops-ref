## Manual installation
  - Install nodejs locally 
  - Clone the repo
  - Install the dependencies (npm install)
  - Start the DB locally
    - docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5432:5432 postgres
    - Go to neon.tech and get yourself a new db
  - Change the .env file and update your DB credentials
  - npx prisma migrate
  - npx prisma generate
  - npm run build
  - nom run start

## Docker installation


## Docker Compose installation steps