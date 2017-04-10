# bnnyDrop - najlepszy skrypt na drop ze stone?

## Funkcje
- wypadanie przedmiotów
  - włączanie/wyłączanie ich wypadania
  - między jakimi wysokościami może wypaść przedmiot
  - wybór kilofów (drewniany, kamienny, żelazny, złoty, diamentowy)
  - czy przedmiot ma wypadać także z rudy
    - jeżeli nie, zamienianie rudy na wybrany blok
- menu
  - spis dropu
  - statystyki
  - top10
- obsługa zaklęć
  - szczęście (fortune) 1-3
  - jedwabny dotyk (silktouch)
- turbo
  - drop
  - exp
- system punktów
  - pisanie na czacie od danej ilości punktów
- kamień
  - blokowanie wypadania kamienia/bruku
  - otrzymywanie expa po wykopaniu
- generatory kamienia
  - ustawianie szybkości regeneracji
  - ustawianie craftingu generatora
- pełna konfiguracja wiadomości i wyglądu GUI
- obsługa UUID
- dodatkowe punkty procentowe przy posiadaniu wybranego uprawnienia
- bardzo krótki kod jak na możliwości skryptu

## Komendy i uprawnienia
- komendy
  - drop:
    - komenda: `/bnnyDrop:drop`
    - aliasy: `/drop, /kamien, /kamień, /stone, /stown`
    - uprawnienie: `bnnyDrop.drop`
  - statystyki
    - komenda: `/bnnyDrop:statistics [gracz]`
    - aliasy: `/statistics, /stats, /statystyki, /staty`
    - uprawnienia:
	  - własne statystyki: `bnnyDrop.statistics`
	  - kogoś statystyki: `bnnyDrop.statistics.others`
  - top10
    - komenda: `/bnnyDrop:top10 [coal|iron|lapis|gold|diamond|redstone|emerald|stone|points]`
    - aliasy: `/top, top10, topka`
    - uprawnienie: `bnnyDrop.top10`
- uprawnienia
  - pełne uprawniena: `bnnyDrop.*`
  - super-drop: `bnnyDrop.super-drop`
  - włączanie/wyłączanie turbo dropu/expa
    - turbo drop: `bnnyDrop.turbo.drop`
    - turbo exp: `bnnyDrop.turbo.experience`
  - omijanie blokady pisania na czacie: `bnnyDrop.bypasschat`

## TODO i changelog
- todo: [klik](https://github.com/xNorbig/bnnyDrop/blob/master/TODO-CHANGELOG.md/#do-zrobienia) 
- changelog: [klik](https://github.com/xNorbig/bnnyDrop/blob/master/TODO-CHANGELOG.md/#lista-zmian) 

## Pobieranie i wymagania
Najnowsza wersja: [bnnyDrop [v1.0]](https://raw.githubusercontent.com/xNorbig/bnnyDrop/master/bnnyDrop.sk)

Wymagania:
- [Skript by bensku](https://github.com/bensku/Skript/releases) ([wersja dev26b](https://github.com/bensku/Skript/releases/download/dev26b/Skript.jar))
- [WildSkript](http://republicansensei.com/)
  - wersja minecraft [1.7-1.8](http://republicansensei.com/WildSkript%201.7-1.8.jar) lub [1.9-1.11](http://republicansensei.com/WildSkript%201.9-1.10-1.11.jar)
- [SkQuery](http://republicansensei.com/)
  - wersja minecraft [1.7-1.10](http://republicansensei.com/SkQuery%201.7-1.8-1.9-1.10.jar) lub [1.11](http://republicansensei.com/SkQuery_Lime%201.11.jar)

Serwer do testowania skryptu: [klik](https://github.com/xNorbig/bnnyDrop/raw/master/serwer.rar) ([skan](https://virustotal.com/pl/url/62eec33edfe112d4f35bce2acdeff7cbcea2c83e831fbfaf98033b61ab1cf02b/analysis/1491848796/)​​​​​​​)
## Informacje
Wszelkie błędy proszę zgłaszać w [zakładce "issues"](https://github.com/xNorbig/bnnyDrop/issues).

Ten skrypt jest przepisaną, z większą ilością funkcji, lepszą wersją [nDrop](https://github.com/xNorbig/bnnyDrop/issues)a od początku.