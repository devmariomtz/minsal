# Proyecto Symfony en Windows
Pasos necesario para ejecutar una proyecto symfony en windows

## Instalar PHP

Instale PHP 8.2 o superior y estas extensiones de PHP (que están instaladas y habilitadas por defecto en la mayoría de las instalaciones de PHP 8): Ctype, iconv, PCRE, Session, SimpleXML y Tokenizer;
[Descargar ZIP VS16 x64 Non Thread Safe (2024-Jul-30 15:35:46)](https://windows.php.net/downloads/releases/php-8.3.10-nts-Win32-vs16-x64.zip)

## Descargar Composer 

Instalar el gestor de paquetes para PHP
[Descargar Composer para Windows](https://getcomposer.org/Composer-Setup.exe)

## Instalar Symfony CLI

Para ello debemos primero instalar scoop para instalarlos en la PowerShell
	
### Instalar scoop
Abra un terminal PowerShell (versión 5.1 o posterior) y desde el prompt PS C:\>, ejecute:

```Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser```

```
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
Luego de instalar scoop podemos instalar el CLI de symfony

   ```scoop install symfony-cli```

## Crear Proyecto

  ```symfony new my_project_directory --version="7.1.*" --webapp```
