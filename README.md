# Info

Mapa przemienników pod adresem: https://mapy73.pl/przemienniki

Jeśli ktoś chciałby robić Pull Request do bazy danych i tymczasowo tak dokonwyać zmian w przemiennikach niech da znać na Discordzie to wrzucę tutaj opis obiektów 

## Obiekty

Dla przykładu dla przemiennika [SR2GT](https://github.com/Krusz-Beton/przemienniki-mapy73pl/blob/main/db/!dziedzictwo-narodowe/SR2GT.yaml)

```yaml
x:
  70cm:
    - rx:
        f: 431.425
        t:
          - c: "94.8"
      tx:
        f: 439.025
        t:
          - c: "94.8"
      h: "54471018895"
      t: i
      s: "5"
      p: 0
      u:
        - https://www.lewczuk.pl/sr2gt-70cm-gdynia
        - http://fm-link.pl
      d: |-
        Połączony na stałe z przemiennikami sieci FM-LINK.
        Pracuje z wąską dewiacją (NARROW FM) +/- 2,5 kHz.
        Otwarcie po 1 sekundzie nośnej z CTCSS.
        Radiolatarnia - znamiennik nadawany co 15 minut.
        Antena Radmor 3284/3
        Emitel RTCN Chwaszczyno
h:
  "54471018895":
    x:
      - 70cm: 0
    p: Chwaszczyno EMITEL
    e: 349
    g: 161
    a: 54.452753
    o: 18.435949
o:
  - SP2XDM
page: https://mapy73.pl/repeater/SR2GT
```

Gdzie `page:` to link do strony, `o:` lista opiekunów przemiennika.. 