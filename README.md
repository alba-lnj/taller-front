# Cómo superar los obstáculos del theming de Drupal y no morir en el intento

## Requerimientos taller:
Instalación de un Drupal 10 limpio, un ejemplo para hacerlo es el siguiente (con DDEV):

- mkdir my-drupal-site && cd my-drupal-site
- ddev config --project-type=drupal10 --php-version=8.3 --docroot=web
- ddev start
- ddev composer create drupal/recommended-project:^10
- ddev composer require drush/drush
- ddev drush site:install --account-name=admin --account-pass=admin -y
- ddev launch

## Instalación de los siguientes módulos y activación de estos (seguir este orden):

- Gin Toolbar
- Admin Toolbar (Instalar Admin Toolbar y Admin Extra Tools)
- Gin
- Gin LB
- Gin Login
- Layout builder styles
- Layout builder restrictions
- Bootstrap Barrio 5 Theme**
