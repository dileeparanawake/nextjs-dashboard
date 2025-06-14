## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

---

## Running with Docker Compose

This project includes a `docker-compose.yml` for easy local development.

### Start the app and database
```sh
docker-compose up --build
```
- App: http://localhost:3000
- Database: localhost:5432 (user: postgres, password: postgres)

### Reset the database (wipe all data)
```sh
docker-compose down -v && docker-compose up --build
```
This will remove all data and start fresh.

