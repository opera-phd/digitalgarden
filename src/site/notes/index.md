---
{"dg-publish":true,"permalink":"/index/","title":"platforma OPeRA","tags":["gardenEntry"],"created":"2024-12-28T15:33:12.249+02:00","updated":"2025-01-17T18:41:07.959+02:00"}
---

> [!abstract]- antet  
> context:: __fără context__, pagină de pornire   
> data:: 2024.11.10  
> ora:: 14:13  
> conexiuni::  
> DDC::  
> ZettelkastenCode::  
> sursa::  
> tags::  


---

# componente externe
- această pagină, spre deosebire de altele, nu are *context* *(de obicei declarat în proprietatea omonimă din **antet**, vezi mai sus)* și, deocamdată, nici alte componente externe, cu excepția...
	- ... modulului complementar pe care îl reprezintă website-ul proiectului **[OPeRA](https://opera-phd.org/)**

---

# sistem personal de gestiune a cunoștințelor - PKMS
*realizat în cadrul proiectului [**OPeRA**](https://opera-phd.org/)*
![OPeRA-logo-350.png|200](/img/user/media/OPeRA-logo-350.png)
## introducere
Această pagină este punctul de **pornire** în structura acestui **modul al platformei digitale [OPeRA](https://opera-phd.org/),** versiunea 0.2[^1].
Titlul site-ului, din partea stângă a paginii, **„OPeRA Digital Garden”**, este și **link** către pagina aceasta de pornire care conține cuprinsul modulului *(vezi mai jos, [[index#cuprins\|#cuprins]])*.
Fiecare notă (pagină) a acestui modul conține în **„antet”** (click în câmpul lui deschide conținutul antetului) informații de tip *metadata*, inclusiv **contextul** respectivei pagini sub formă de link.
**Graficul** *microuniversului* notelor, din partea dreaptă a pagini, în partea de sus:
- are trei niveluri de adâncime care pot fi setate prin glisarea butonului rotund pe bara de setare, de la 1 la 3 niveluri de profunzime a conexiunilor
- se poate comuta între **graficul local** (centrat pe nota curentă) și **graficul general** (cuprinzând toate notele conectate), deschis într-o fereastră nouă, din butonul în formă de glob, din partea dreaptă, sus, al componentei paginii
- poate fi mărit în fereastră nouă din butonul (sub forma celor patru săgeți în diagonală, de tip *„full screen”*) din partea dreaptă, sus, al componentei paginii, iar din același buton al ferestrei noi se poate întoarce la starea inițială

Administrarea acestui modul este comună cu cea a website-ului **[OPeRA](https://opera-phd.org/)** *(altă componentă a platformei noastre digitale)* și ne puteți scrie pe aceeași adresă: research@opera-phd.org.

## cuprins
Principalele **componente** ale acestui modul sunt:
- **structura generală a platformei digitale a proiectului**, cuprinzând componente și *conexiuni* generale - [[notes/structura platformei OPeRA\|structura platformei OPeRA]]
- **documentația și mediateca**, în sistem DDC - [[notes/o500 DDC\|o500 DDC]][^2]
- **sistemele PKM**
	- documentare generală despre sistemele PKM - [[notes/001.450 PKM\|001.450 PKM]]
		- observație: toate notele cu prefix DDC (zecimal) dereprezintă componente ale **documentației** (bibliotecii), iar celelalte note reprezintă contribuții proprii la această platformă digitală
	- o selecție restrânsă de [[notes/sisteme PKM\|sisteme PKM]] recomandate de noi, pe trei niveluri de complexitate
- **modulul dinamic al platformei digitale**[^3] de managementul cunoștințelor în cadrul proiectului [OPeRA](https://opera-phd.org/) 
	- componente ale **documentației** (bibliotecii), clasate în sistemul zecimal Dewey (DDC), cu prefix de tipul `###.###` (note de tip „Literature Review”) (LZ, *LiteraturZettel* în sistem [[Zettelkasten\|Zettelkasten]])
	- note reprezentând **propriile contribuții** (idei, comentarii) ale membrilor proiectului (FZ, *FolgeZettel* în sistem [[Zettelkasten\|Zettelkasten]])
	- în particular, clasarea tematică în cadrul sistemului **TUA_IDEM** de clasare a informațiilor din cadrul proiectului - [[notes/OPeRA TUAIDEM\|OPeRA TUAIDEM]] urmărind, din nou:
		- **documentații** (clasate DDC) în cadrul studiului tematic
		- **contribuții proprii** în cadrul acestui studiu

|    (teorie)    |    (practică)    | (materialitate) |
|:--------------:|:----------------:|:---------------:|
|                |  [[notes/OPeRA U\|U]]  |                 |
| [[notes/OPeRA T\|T]] | [[notes/OPeRA AI\|AI]] | [[notes/OPeRA M\|M]]  |
|                | [[notes/OPeRA DE\|DE]] |                 |


---
# subsolul notei
---
## referințe și resurse


---
## note de subsol
---
[^1]: reprezintă încă o versiune *alpha-testing*
[^2]: [Dewey Decimal Classification System](https://en.wikipedia.org/wiki/Dewey_Decimal_Classification)
[^3]: noțiunea de „dinamic” este relativă; acesta este generat cu ajutorul unui sistem **[SSG](https://medium.com/codex/web-design-patterns-ssr-ssg-and-spa-fadad7673dfe)** *(Static Site Generator)*, dar procesul este foarte flexibil și rapid, orice actualizare (dinamică) a conținutului în platforma offline **Obsidian** fiind publicată în mai puțin de un minut