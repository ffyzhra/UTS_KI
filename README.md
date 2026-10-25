# Scholarship App (Midterm Version)

Midterm project (UTS) for the Information Security (*Keamanan Informasi*) course at Esa Unggul University: the first version of a student scholarship system, built with **Laravel** and a **Filament** admin panel and run in **Docker**.

The finished version, with document upload, a selection workflow, role-based access and OWASP ZAP security testing, is in **[ffyzhra/UAS_KI](https://github.com/ffyzhra/UAS_KI)**.

## What's here

- Laravel app with a Filament admin panel and student (`Mahasiswa`) data management
- Docker setup: `Dockerfile`, `docker-compose.yml` (app + MySQL), `nginx.conf`, `php.ini`
- `Essay/`: the written security essay submitted with the project

## Repository layout

```
beasiswa-app/        # the Laravel application (Filament admin, Mahasiswa model)
Dockerfile           # PHP 8.2 image that runs `php artisan serve` on port 8000
docker-compose.yml   # laravel_app + laravel_db (MySQL)
nginx.conf, php.ini
Essay/               # security essay
```

> This is an early snapshot kept for reference. To run the project, use the final version in [UAS_KI](https://github.com/ffyzhra/UAS_KI).

## Tech stack

PHP 8.2 · Laravel · Filament · MySQL · Docker · Nginx

## Author

**Fayza Azzahra** · [GitHub](https://github.com/ffyzhra) · [LinkedIn](https://www.linkedin.com/in/ffyzhra)
