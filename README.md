Clone the repository:

git clone https://github.com/Jgarette0/LaVue.git
Navigate to the project directory:

cd lavue
Install PHP dependencies:

composer install
Install Node.js dependencies:

npm install
Copy the example environment file and configure it:

cp .env.example .env
Generate an application key:

php artisan key:generate
Compile the assets:

npm run dev
Serve the application:

php artisan serve
