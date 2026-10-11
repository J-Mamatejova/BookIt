# BookIt – Rezervačný systém služieb

Janka Mamatejová

5ZYI32


## Stručný opis projektu
BookIt je webová aplikácia na vyhľadávanie poskytovateľov služieb a rezerváciu termínov. Je určená napríklad pre kaderníctva, nechtové štúdiá, lekárov a ich klientov.

Poskytovatelia si môžu vytvoriť profil, spravovať ponuku služieb a dostupné termíny. Klienti si môžu prezerať profily poskytovateľov a rezervovať si termín s registráciou alebo bez nej.

## Role v projekte

Návštevník: Vyhľadáva poskytovateľov, prezerá služby a rezervuje termíny bez registrácie.

Registrovaný klient: Vytvára a spravuje svoje rezervácie.

Poskytovateľ služby: Spravuje svoj profil, služby, dostupné termíny a rezervácie.

Administrátor: Spravuje používateľov a kontroluje obsah aplikácie.

## Prípady použitia podľa rolí

Návštevník: Vyhľadá poskytovateľa, prezrie si jeho služby a rezervuje termín.

Registrovaný klient: Prihlási sa, zobrazí si svoje rezervácie a môže ich zrušiť.

Poskytovateľ: Upraví profil, spravuje služby a termíny a zobrazuje rezervácie.

Administrátor: Zobrazí používateľov a spravuje profily poskytovateľov.

## Plánované entity

Používateľ: Údaje o účte a používateľská rola.

Profil poskytovateľa: Názov prevádzky, adresa, kontakt a popis.

Služba: Názov, popis, cena a dĺžka trvania.

Termín: Dátum, čas a dostupnosť.

Rezervácia: Vybraný termín, údaje o klientovi a stav rezervácie.

Fotografia: Súbory priradené k profilu poskytovateľa.

## Vzťahy medzi entitami

Jeden používateľ môže mať jeden profil poskytovateľa. Profil môže obsahovať viacero služieb, termínov a fotografií. Každý termín patrí ku konkrétnemu poskytovateľovi a službe a môže mať jednu aktívnu rezerváciu. Registrovaný klient môže mať viacero rezervácií.

## Hlavné stránky aplikácie

Domovská stránka: Vyhľadávanie poskytovateľov.

Výsledky vyhľadávania: Zoznam poskytovateľov a filtrovanie.

Profil poskytovateľa: Informácie, služby a dostupné termíny.

Rezervácia: Výber termínu a zadanie údajov.

Prihlásenie a registrácia: Správa používateľského účtu.

Moje rezervácie: Prehľad rezervácií klienta.

Dashboard poskytovateľa: Správa profilu, služieb a termínov.

Administrácia: Správa používateľov a profilov.

## Rozdelenie funkcionality

Základné funkcie

- Registrácia, prihlasovanie a používateľské role.

- Správa profilov a služieb.

- Vytváranie a správa dostupných termínov.

- Rezervovanie a rušenie termínov.

- Prehľad rezervácií.

- Vyhľadávanie a filtrovanie poskytovateľov.

- Validácia vstupov a kontrola oprávnení.

- Nahrávanie a správa fotografií.

Rozširujúce funkcie

- Automatické generovanie termínov podľa otváracích hodín.

- mailové potvrdenia a pripomienky.

Kalendárové zobrazenie rezervácií.

Hodnotenia a recenzie poskytovateľov.

Zobrazenie prevádzok na mape.
