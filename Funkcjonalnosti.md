# Načrt funkcionalnosti za spletno trgovino ManaVault
---

## 1. Baza podatkov in katalog (Temelj sistema)
* **Povezava z API-ji:** Uporaba obstoječih baz podatkov (npr. *Scryfall API* za MTG, *Pokémon TCG API*, *YGOPRODeck* za Yu-Gi-Oh!) namesto ročnega vnosa kart.
* **Pametni iskalnik:** Iskanje po imenu (tudi z zatipki), besedilu na karti (*Oracle text*), vrsti karte, ceni mane, barvi, ediciji in redkosti.
* **Prikaz vseh različic (*Printings*):** Združevanje vseh izdaj iste karte na enem mestu (navadna, *Foil*, *Etched Foil*, *Borderless*, *Showcase*, promocijske verzije) s hitrim preklopom.
* **Podpora za jezike:** Jasne oznake/zastavice ob ponudbah za različne jezike (angleščina, nemščina, japonščina itd.).

## 2. Hibridni poslovni model (Trgovina + Tržnica)
* **ManaVault Direct (kot Card Kingdom):** Lastna zaloga trgovine – kupci kupujejo neposredno od vas, prejmejo vse v enem paketu z garancijo kakovosti.
* **ManaVault Marketplace (kot Cardmarket/TCGplayer):** Zunanji prodajalci (trgovine in posamezniki) lahko odprejo svoj profil in prodajajo svoje karte prek platforme proti proviziji.
* **Buylist (Odkup kart):** Sistem, kjer igralci izberejo karte, ki jih želijo prodati vam za gotovino ali dobropis v trgovini (*Store Credit*, npr. z dodatnim bonusom).

## 3. Orodja za nakupovanje (Uporabniška izkušnja)
* **Decklist / Mass Entry (Množični vnos):** Uporabnik prilepi celoten seznam kart (npr. iz orodij Moxfield ali Archidekt), sistem pa poišče vse razpoložljive karte in ponudi najcenejše različice.
* **Optimizator košarice (*Cart Optimizer*):** Algoritem, ki pri nakupu pri več prodajalcih izračuna najcenejšo kombinacijo (karte + poštnina) za celoten seznam želja.
* **Standardizirano stanje kart (*Grading*):** Jasen slikovni vodič za stopnje ohranjenosti (*Near Mint, Excellent, Good, Light Played, Played, Poor*) za preprečevanje reklamacij.

## 4. Cenovni algoritem in analitika
* **Avtomatska sinhronizacija cen:** Povezava z evropskimi (Cardmarket) in ameriškimi (TCGplayer) cenovnimi trendi za sprotno posodabljanje cen.
* **Grafi gibanja cen (*Price History*):** Prikaz zgodovine cen na strani vsake karte.
* **Obvestila o zalogi in cenah:** Možnost prijave na obvestila (*"Obvesti me, ko bo na zalogi"* ali *"Obvesti me, ko cena pade pod X €"*).

## 5. Upravljanje zaloge (Admin / Seller Dashboard)
* **Hitro dodajanje zaloge (*Bulk Inventory Tool*):** Vmesnik za hiter vnos količine in stanja kart po posameznih edicijah brez osveževanja strani.
* **Uvoz/Izvoz preko CSV:** Podpora za nalaganje zaloge iz aplikacij za skeniranje kart (npr. *ManaBox*, *Delver Lens*).
* **Dinamično prilagajanje cen (*Repricer*):** Orodje za samodejno prilagajanje cen glede na trenutne tržne ponudbe.

## 6. Logistika, varnost in plačila
* **Pametni izračun poštnine:** Samodejni izračun stroškov pošiljanja glede na težo/število kart in vrednost naročila (navadna pošta za manjše vrednosti, sledena pošiljka za dražja naročila).
* **ManaVault Wallet (*Store Credit*):** Denarnica za dobroimetje iz prodaje kart ali *Buylista*, ki omogoča nakupe brez dodatnih bančnih provizij.
* **Escrow zaščita:** Zadržanje plačila kupca pri dražjih naročilih zunanjih prodajalcev, dokler kupec ne potrdi prejema pošiljke v opisanem stanju.

---

