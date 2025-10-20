tailwind :
https://tailwind-converter.netlify.app/
para enlazar con css:
href="{{ asset('css/style.css') }}"

instalar paquetes:
composer require ibex/crud-generator --dev

publicar configuraciones:
php artisan vendor:publish --tag=crud

generar crud:
php artisan make:crud {nombre de la tabla}


se llama el controlador y se crea una ruta tipo resource


