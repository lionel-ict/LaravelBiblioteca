### Instalar las dependencias de PHP y JavaScript:
composer install
npm install

### Previsualizar la web en http://127.0.0.1:8000
php artisan serve

### Tras modificar 'resources/css/app.css' o 'resoucers/js/app.js' ejecutar:
npm install     # por si acaso
npm run dev     # compila el webpack a la carpeta public

### Instalar herramienta laravel/ui para añadir Bootstrap al proyecto
composer require laravel/ui     # instalamos herramienta
php artisan ui bootstrap        # instalamos Bootstrap

# NOTA: Con Bootstrap los estilos CSS hay que colocarlos
# en resources/sass/app.scss, deja de usarse resources/css/app.css
