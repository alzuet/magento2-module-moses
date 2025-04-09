# Módulo de traducciones al español
Traducciones cuidadas.

1. Para instalar el módulo 

```bash 
composer require atelier/moses
```

2. Habilitar el módulo: 

```bash 
bin/magento module:enable Atelier_LenguaEs 
```

3. Para que se aplique la traducción

```bash 
bin/magento setup:upgrade
```

Y asegurar que Magento está configurada para ES_ES.
Ej.
    "default_country": "ES",
    "locale": "es_ES",