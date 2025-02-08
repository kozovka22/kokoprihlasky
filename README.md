# ADMINISTRACE PŘIHLÁŠKOVÉHO SYSTÉMU

## Login
Pro login do Admin rozhraní využijte odkaz https://pratelebabinaplacku.cz/admin

Zobrazí se login stránka. do kolonek vyplňte předem nasdílené přihlašovací údaje. Po úspěšném přihlášení budete přesměrování do rozhraní Sonata admin.

## Sonata admin
### Dashboard
První stránkou sonata admin je **Dashboard**. V hlavním okně se nachází karta Admin s položkou Přihláška a modrým textem list, skrze kterou se dostanete k výpisu všech odeslaných přihlášek.

### List přihlášek
V seznamu se nachází nejzákladnější data. Pro zobrazení všech dat klikněte na tlačítko 'Show' v posledním sloupci 'Akce'.

Chcete-li zapsat zaplacenou částku, nebo nastane problém s přihláškou (například rodič zapomene zaškrtnout sourozeneckou slevu, nebo dítě odhlásí) použijte tlačítko 'Edit' nacházející se vedle tlačítka 'Show'.

### Editace přihlášek
Na stránce 'Edit' se nachází 5 vstupů. 

Vstup **'Zaplacená částka'** slouží pouze pro zjednodušení života, pokud se rodič bude dotazovat, kolik zbývá zaplatit. Rodič k němu během přihlašování nemá přístup.

Vstup **'Zaplaceno'** slouží také jen pro zjednodušený přístup k informaci zaplatil/nezaplatil, jen na seznamu svítí buď výrazně zeleně, nebo výrazně červeně. Rodič k němu během přihlašování nemá přístup.

Vstup **'Sourozenecká sleva'** slouží pro jednoduchou opravu přehlédnutí kolonky rodičem. Rodičovi NENÍ automaticky zaslán e-mail, MUSÍ se tedy kontaktovat ručně!

Vstup **'Poznámky'** je během přihlašování vyplněn rodičem. Vy do tohoto vstupu můžete připisovat vlastní poznámky, rodič je stejně jako zbytek těchto změn neuvidí.

Vstup **'Odhlášen'** můžete využít pro jednoduché označení odhlášeného dítěte. Odhlášené a neodhlášené děti můžete v listu **vyfiltrovat**.

Spodní dvě tlačítka přihlášku opšt uloží. Kdyby byly jiné problémy s daty, mohu vám buď připsat možnost editace do tohoto formuláře, nebo je mohu upravit natvrdo v databázi.
### Filtrování výsledků v listu
Chcete-li vyfiltrovat přihlášky dle některého z parametrů, využijte tlačítko Filters v pravém horním rohu v liště nad seznamem přihlášek.

Po rozkliknutí se vám zobrazí spousta možností, dle kterých se dají přihlášky filtrovat. Nejvíce používanou bude nejspíše 'Odhlášen' a 'Přijmení'. Jako příklad použiji kolonku 'Odhlášen'.

Po zakliknutí možnosti odhlášen se lišta rozšíří o select vstup s popiskem 'Odhlášen'. Kliknutím na tento vstup se rozbalí možnosti "yes" a "no". Na to, jak to přeložit, jsem se ani nepokoušela přijít, pardon.

Chcete-li tedy zobrazit pouze neodhlášené, zakliknete zde "no" a **!!kliknete na 'Filter'!!**

Pokud si přejete filtr zrušit, klikněte na tlačítko 'Reset' vedle tlačítka 'Filter'.
