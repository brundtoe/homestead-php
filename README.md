# Homested php projekter

Denne Homestead definition af en vagrant instans, anvendes af mine PHP projekter, der ikke anvender Laravel.

## Etablering
Denne defintion er oprettet som en lokal instans ved med composer at installere **laravel/homestead** 

```
    composer require laravel/homestead --dev
    php vendor/bin/homestead make
```

Instansen opdateres ved at opdatere versionsnummeret i **composer.json**

Projektet forudsætter at vagrant boxen **laravel/homstead er installaret.

## Homestead.yaml

Følgende PHP projekter er aktiveret i filen:

- websites
- doctrine26/bookstore og customers
- symfony4

Yderligere projekter kan tilføjes i Homestead.yaml.
