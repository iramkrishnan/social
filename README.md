# Social - A social networking platform

## Clone the repository
- Clone the project
`git clone https://github.com/ramkrishnan6/social.git`

## Setting up the development environment
- Go into the root project directory:
`cd social`

- Create a .env file(by copying the existing example-env file):
`cp .env.example .env`

- Install composer:
`composer install`

- Generate and store the application key:
`php artisan key:generate`
`php artisan storage:link`

- Install packages for rendering CSS and JS files:
`npm install`
`npm run dev`

- Run the migrations:
`php artisan migrate`
