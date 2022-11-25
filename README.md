# ns01144 Match And Fly Landing Page

## Instalacja

1. Sklonuj repozytorium
2. Uruchom `composer install`
3. Skopiuj `config/local-config.php.dist` to `config/local-config.php` i uzupełnij
4. Wgraj bazę danych z data/dump.sql.gz wykorzystując skrypt `./bin/load_db.sh`
5. Skonfiguruj Vhost (sample: `config/docker/httpd/vhost.conf`)
6. Zaloguj się i zmień hasło na admina (default: `C#cijlaa2h5998tZf(`)

## Ustawienie projektu

1. Z menu wybrać Apperance / Customize
2. W zakładce Site title/tagline/logo Wybrać upload your logo i wybrać ostatnie zdjęcię MF_logo RGB.png. Zatwierdzić poprzez kliknięcie Publish
3. Header area/Header type dla "Front page header type" oraz "Site header type" ustawić "No header (only menu)"
4. W zakładce "Blog options" ustawić full width oraz zaznaczyć checkobx "Full width single post"
5. W zakładce "Menus" kliknąć w Menu 1 i w następnym oknie zaznaczyć checkbox "Primary menu"

## Praca z projektem

### Edycja skryptów

Źródła skryptów znajdują się w katalogu `public/wp-content/themes/sydney-child/scripts_sources`. 
Finalne skrypty znajdują się w `public/wp-content/themes/sydney-child/js`.

Pliki źródłowe są transpilowane za pomocą babela.  

W celu pracy ze skryptami w katalogu `public/wp-content/themes/sydney-child` należy wykonać polecenie `npm install`. Następnie po zakończonej edycji należy wykonać polecenie `npm run compile:js`, który przetranspiluje kod tak by był odpowiednie interpretowany przez najnowsze przeglądarki oraz IE11.


