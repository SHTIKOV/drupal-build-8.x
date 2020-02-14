# Drupal build 8.x
Custom build for drupal 8.x (current version: 8.8.2)

## Modules:
- Admin toolbar

## Themes:
- Adminimal theme
- Custom Theme (clean)

## Deploy:
In current version we have `backups` folder for create backups with this template: "**Version`${current timestamp}`.sql**". Deployment through migration will be implemented in the future.

## How to run?
- Clone repository
- Run the following **composer** command: `composer install`
- Import last backup
- Change base connection settings
- CLear **all cache** and **cache for js and css**
- Run the following **php** command: `php -S localhost:8888`

#### SHTIKOV's project
