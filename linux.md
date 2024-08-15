# Proyecto Symfony en Linux
Pasos necesario para ejecutar una proyecto symfony en windows

## Instalar PHP

Instale PHP 8.2 o superior y estas extensiones de PHP (que están instaladas y habilitadas por defecto en la mayoría de las instalaciones de PHP 8): Ctype, iconv, PCRE, Session, SimpleXML y Tokenizer;
[Descargar php)](https://php.watch/articles/php-8.3-install-upgrade-on-debian-ubuntu#php83-debian-quick)

## Descargar Composer 

Instalar el gestor de paquetes para PHP
[Descargar Composer para Windows](https://www.transip.eu/knowledgebase/entry/3300-installing-composer-in-linux/)

## Instalar Symfony CLI

 instalar el CLI de symfony

   ```curl -sS https://get.symfony.com/cli/installer | bash```

## Crear Proyecto

  ```symfony new my_project_directory --version="7.1.*" --webapp```

## 