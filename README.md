# Sistemet Shperndara

**Intro:**  
This project is a Laravel-based distribution system for managing inventory, orders, and user roles across multiple warehouses. It provides a RESTful API, a Vue.js frontend (pending), and robust seeders to generate sample data for testing.

🚀 Instalimi dhe Konfigurimi
Për të instaluar dhe konfiguruar këtë projekt, ndiqni këto hapa:

Klononi projektin nga GitHub me komandën: git clone https://github.com/leonita-01/SistemetShperndara-Project.git cd SistemetShperndara-Project

Instaloni varësitë e PHP duke përdorur Composer: composer install

Instaloni varësitë e JavaScript me npm: npm install

Kopjoni skedarin .env.example si .env: cp .env.example .env

(ose krijoni manualisht një skedar të ri .env dhe kopjoni përmbajtjen nga .env.example)

Gjeneroni çelësin e aplikacionit Laravel: php artisan key:generate

Plotësoni të dhënat e databazës dhe konfigurimet e tjera në skedarin .env sipas ambientit tuaj.

Ekzekutoni migrimet dhe seeders për bazën e të dhënave:php artisan migrate --seed

Nisni serverin lokal të zhvillimit:php artisan serve

Tani, projekti do të jetë i qasshëm në shfletues në adresën: http://localhost:8000
