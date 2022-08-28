<p>
    <a href="https://laravel.com" target="_blank">
        <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="laravel">
    </a>
</p>

## Latar Belakang Tugas

Framework Laravel menyediakan banyak fitur untuk developer yang bertujuan untuk memudahkan dalam membangun suatu aplikasi atau website salah satunya sebuah engine bawaan dari Laravel yaitu Blade Template. Dengan menggunakan engine ini, developer dapat dengan mudah membuat tampilan dinamis. Dengan menggunakan Blade Template kita juga dapat memanggil halaman view lain ke halaman utama dengan mudah. Laravel juga menyediakan service API untuk membantu dalam menghubungkan program dengan database yang ada di Investree 

## Instalation

### Prepare dependencies
    - composer install
    - cp .env.example .env
    - cp .env.testing.example .env.testing

### Change Database Config
    Change Database configuration in .env and .env.testing 

### Generate and Migration
    - php artisan key:generate
    - php artisan migrate --seed
    - php artisan passport:install

### Prepare FrontEnd
    - npm install
    - npm run dev

### Run Test and Development Server
    - php artisan test
    - php artisan serve
