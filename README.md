# seriousCustomTemplate
Custom template service provider for evo 2.0

## Install

1) `php artisan package:installrequire ser1ous/serious-custom-template '*'` in you **core/** folder
2) `php artisan sct:install` 

##Explanations

To make this package work right you must follow some rules:
- Your controllers must be named following PSR standards (example ```TemplateNameController.php```)
- Directories after your namespace must be named avoiding '_' symbol (example ```EvolutionCMS\Example\Controllers\Some_dir``` is bad idea will be changed like ```EvolutionCMS\Example\Controllers\SomeDir```)
---

## Установка  

1) `php artisan package:installrequire ser1ous/serious-custom-template '*'` в папке **core/**
2) `php artisan sct:install`

## Пояснения

Для того, чтобы заставить пакет работать правильно следует соблюдать некоторые правила:
- Ваши контроллеры должны именоватся согласно psr стандартам (пример ```TemplateNameController.php```)
- Директории после Вашего ```namespace``` должны именоватся избегая символа '_' (пример ```EvolutionCMS\Example\Controllers\Some_dir``` плохая идея, будет изменено так ```EvolutionCMS\Example\Controllers\SomeDir```)


