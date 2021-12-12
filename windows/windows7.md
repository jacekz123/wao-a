# Aktywacja Windows 7
## Serwery
Zapoznaj się z [listą serwerów](/servers.md), aby w razie niedziałania poniżej podanego go podmienić.
## Klucze
Wybierz z poniższej listy klucz do swojej wersji systemu.
<details><summary>Wyświetl klucze</summary>

Wersja | Klucz
------ | -----
**Windows 7 Professional** | FJ82H-XT6CR-J8D7P-XQJJ2-GPDD4
**Windows 7 Professional N** | MRPKT-YTG23-K7D7T-X2JMM-QY7MG
**Windows 7 Professional E** | W82YF-2Q76Y-63HXB-FGJG9-GF7QX
**Windows 7 Enterprise** | 33PXH-7Y6KF-2VJC9-XBBR8-HVTHH
**Windows 7 Enterprise N** | YDRBP-3D83W-TY26F-D46B2-XCKRJ
**Windows 7 Enterprise E** | C29WB-22CC8-VJ326-GHFJW-H9DH4

  </details>
## Komendy
```
slmgr /ipk klucz
slmgr /skms kms10.msguides.com
slmgr /ato
```
W pierwszej komendzie podmień `klucz` na odpowiedni dla swojej wersji systemu;
Jeśli aktywacja się nie powiedzie, powtórz proces podmieniając serwer na jeden z [listy serwerów](/servers.md) (podmień `kms10.msguides.com`).
