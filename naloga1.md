1. Ustvari datoteko z imenom `form_fields.py`.

2. V njej napisi razred `FormField`, ki vsebuje stiri metode (zaenkrat naj ne naredijo nicesar): konstruktor brez argumentov, `is_empty`, `is_valid` in `render` (vse metode brez argumentov).

3. Metodi `is_valid` in `render` naj v primeru klica vrzete napako `NotImplementedError` (napaka je del standardne Python knjiznice, torej je ni potrebno importati, potrebno pa je vreci novo instanco napake).

4. Vsakic, ko se ustvari nova instanca tega razreda, naj se v konzolo izpise `Konstruktor razreda FormField`.

5. Ustvari novo instanco razreda `FormField`. Kaj se izpise?

6. Po tem, ko je instanca ustvarjena poizkusi izpisati atribut `value` na tej instanci. Kaj pricakujes, da se bo zgodilo?

7. Sedaj popravi konstruktor tako, da bo vsaka nova instanca razreda vsebovala atribut z imenom `value`, ki na zacetku vsebuje vrednost `None`. Ko je konstruktor popravljen, ponovno pozeni kodo iz koraka 6. Kaj se zgodi tokrat? Po tem koraku zakomentiraj izpis atributa `value`.

8. Implementiraj metodo `is_empty`. Ob klicu metode naj se v konzolo izpise `Metoda is_empty razreda FormField`, vrne pa naj vrednost `True`, ce je atribut `value` nastavljen, v nasprotnem primeru pa vrne `False`.

9. Na instanci poklici metodo `is_empty` in izpisi vrnjeno vrednost. Kaj se izpise? Pred naslednjim korakom zakomentiraj v tem koraku dodane vrstice.

10. Na instanci poklici metodo `is_valid`. Kaj se zgodi? Pred naslednjim korakom zakomentiraj v tem koraku dodane vrstice.

11. Po tem, ko je instanca ze kreirana, ji nastavi atribut `value` z vrednostjo `7`. Za tem se enkrat poklici metodo `is_empty` in izpisi vrnjeno vrednost. Kaj se izpise sedaj? Pred naslednjim korakom zakomentiraj v tem koraku dodane vrstice.

12. V tem koraku bomo nadgradili konstruktor. Ta naj sedaj sprejme en argument z imenom `val`. Ko se poklice konstruktor, naj se atribut `value` nove instance nastavi na vrednost `val`. Pomembno je, da se tvoja prva instanca se vedno ustvari brez napake. Konstruktor mora torej delovati v primeru, ko se poklice z vrednostjo `val` in pa tudi v primeru, ko se klice brez vrednosti.

13. Sedaj kreiraj novo instanco in poskrbi, da bo atribut `value` na tej instanci ze na zacetku nastavljen na vrednost `7`. Za to zadostuje ena vrstica. Za tem, ko ustvaris novo instanco se prepricaj, da je atribut res nastavljen na zeleno vrednost (najboljse, da ga kar izpises :). Kaj se izpise v konzolo?

14. Na pravkar dodani instanci znova poklici metodo `is_empty` in izpisi vrnjeno vrednost. Kaj se izpise tokrat?
