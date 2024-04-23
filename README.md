# Procvic.to - Flashcards pro procvičování učiva
 
## Popis stránky
Procvic.to je webová stránka, která uživatelům umožňuje vytvářet balíčky karet různých kategorií k procvičování učiva. 

## Přihlášení
- Index.html obsahuje přihlašovací formulář, skrze který uživatel přihlašuje do svého účtu. Jakmile se příhlásí dostane se na stránku komunitních balíčků.
![prihlaseni](https://github.com/pslib-cz/2023-l4-web-mockupapp-DominikLazna/blob/main/pohledy/prihlaseni.png)

## Komunitní balíčky
- Zde je již možné vidět vytvořené balíčky karet od všech uživatelů.
- V navigaci se nachází vyhledávač, který lze použít k vyhledávání balíčků karet dle jejich názvu.
- V pravém horním rohu se nachází přihlašovací jméno uživatele
- Pod navigací se nachází různé kategorií balíčků. Pokud na jakoukoli kategorii klikneme, v seznamu balíčků se nám začnou zobrazovat jen balíčky příslušné kategorie.
- Samotné okna jednotlivých balíčku obsahují název balíčku, jméno autora, počet liků, disliků a počtu karet.
- Název balíčku se použije input napsaný v editoru balíčku.
- Like a dislike je možné přidat po kliknutí na příslušnou ikonu.
- Počet karet se vygeneruje po vytvoření balíčku.
- Po kliknutí na tlačítko "Procvičit" se uživatel přesune na stránku procvičování, kde již může procvičovat zvolený balíček karet.
![komunitni balicky](https://github.com/pslib-cz/2023-l4-web-mockupapp-DominikLazna/blob/main/pohledy/komunitniBalicky.png)

## Moje balíčky
- Zde je možné vidět balíčky vytvořené přihlášeným uživatelem.
- Tlačítko vytvořit balíček uživatele přesměřuje na editor balíčků.
![moje balicky](https://github.com/pslib-cz/2023-l4-web-mockupapp-DominikLazna/blob/main/pohledy/mojeBalicky.png)

## Editor balíčků
- Zde je možné vytvořit balíček karet pomocí několika vstupových oken.
- Název balíčku se zobrazí v seznamu balíčků a je možné jej vyhledat vyhledávačem.
- Kategorie umožňuje zařadit balíček do specifické kategorie, které je v seznamu balíčků pak možné dohledat dle filtrů.
- Pod názvem a kategorií se nachází již editor jednotlivých karet. Text v inputových oknech se zobrazí na jednotlivých stránkách karty.
- Po kliknutí na tlačítko "Vytvořit další kartu" se vytvoří další komponenta k vytvoření karty identická té první.
- Komponenty k vytváření karet se automaticky číslují.
- Po kliknutí na tlačítko "Vytvořit balíček" se balíček zařadí do seznamu "Komunitní balíčky" a "Moje balíčky".
![editor balicku](https://github.com/pslib-cz/2023-l4-web-mockupapp-DominikLazna/blob/main/pohledy/editorBalicku.png)

## Procvičování
- Zde je možné si procvičit zvolený balíček karet.
- První karta je zvolena náhodně z vytvořeného seznamu karet.
- Tlačítko "Otočit kartu" kartu otočí na druhou stranu a odhalí tedy správnou odpověď.
- Tlačítko "Další karta" náhodně zvolí další kartu ze seznamu.
![procvicovani](https://github.com/pslib-cz/2023-l4-web-mockupapp-DominikLazna/blob/main/pohledy/procvicovani.png)
