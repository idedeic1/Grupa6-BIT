# Grupa6-BIT

Naziv projekta: Mob-Shop

Tim : Bernes Hodžić, Tarik Kulosmanović, Ibrahim Dedeić
- Opis projekta : Mob-Shop je kompanija koja se bavi prodajom i servisiranjem mobitela i mobitelske opreme. Njihovo poslovanje je bilo ograničeno na samo jednu regiju, međutim izvršni direktor kompanije je uvidio priliku proširenja poslovanja na ostale regije/gradove. Zajedno s tim proširenjem došlo je do potrebe razvijanja novog informacionog sistema koji će u budućnosti na adekvatan način pratiti poslovanje ove kompanije. Aplikacija će omugućiti korisniku da na jednostavan i pristupačan način odabere željeni proizvod na licu mjesta ili preko online servisa Mob-Shopa koji sadrži katalog svih dostupnih proizvoda ili da prijavi kvar na svom računaru u servis Mob-Shopa.



- Proceduure : Komukaciju sa korisnikom obavlja prodavač pružajući korisniku sve potrebne informacije o uslugama koje nudi Mob-Shop. Ukoliko korisnik želi da kupi nov proizvod, prodavač omugućuje uvid u dostupne proizvode. Nakon izbora korisnika izvršava se provjera je li proizvod u bazi(tj. na stanju). Ukoliko je proizvod na stanju, prodavač provjerava je li uračunat popust na dati proizvod i prodavač obavlja kupovinu izdajući račun i smanjuje stanje datog proizvoda u bazi. Ukoliko proizvod nije na stanju prodavač informiše korisnika o vremenu čekanja na proizvod i poziva supervizora koji je zadužen za nabavku proizvoda. Korisniku je također omogućen zahtjev za odgođeno plaćanje koji se podnosi ispunjavanjem obrasca koji može tražiti kod prodavača. Prodavač taj zahtjev šalje supervizoru koji može odobriti taj zahtjev ili ne. Korisniku je u okviru cijene proizvoda omogućena dostava i instaliranje(montiranje) proizvoda po potrebi, kojeg obavlja monter Mob-Shopa.
Ukoliko je zahtjev korisnika vezan za servisiranje računara prodavač prilikom preuzimanja proizvoda uzima podatke o korisniku(ime, prezime, broj telefona), obavještava ga o standardnom vremenskom razdoblju koje je potrebno da bi se proizvod servisirao i proslijeđuje proizvod u servis. Servis procjenjuje cijenu popravke i tačno vrijeme čekanja na završetak i javlja prodavaču koji te informacije prenosi korisniku. Korisnik bira da li želi nastaviti sa servisom ili povući svoj proizvod sa servisa. Ukoliko korisnik odluči da nastavi, servis javlja supervizoru koji su dijelovi potrebni da bi se rad nastavio. Nakon što je proizvod servisiran servis šalje informaciju prodavaču koji poziva korisnika i obavještava ga da može doći da preuzme svoj proizvod.   
 Na čelu Mob-Shopa se nalazi direktor koji koordinira čitavim procesom preko supervizora, koji je dužan da ga informiše o bitnim stvarima, i preko finansijskih izvještaja. Direktor prati trendove i nove granice u branši i usaglašava poslovanje shopa u skladu sa tim saznanjima. Direktor također donosi bitnije finansijske odluke i sklapa veće poslovne projekte za koje supervizor shopa nema ovlasti. 


- Akteri : 
Direktor: Odgovoran za poslovanje i koordinaciju čitavog Mob-Shopa
Supervizor: Predstavlja vezu između prodavača i servisa. Zadužen za nabavku i izvještaj direktoru
Servis: Zadužen za servisiranje proizvoda i komunikaciju sa supervizorom
Prodavač: Zadužen za komunikaciju sa korisnicima
Monter: Osoba/e zadužena/e za dostavu i montiranje kupljenog proizvoda
Korisnik: Osobe koje su upotrebljavaju usluge Mob-Shopa

- Funkcionalni zahtjevi :

Korisnik:
⦁	Pregled ponude 
⦁	Mogućnost narudžbe nedostupnog proizvoda 
⦁	Zahtjev za palaćanje na rate 
⦁	Servisiranje proizvoda 

Prodavač:
⦁	Pregled dostupnih proizvoda 
⦁	Pristup bazi podataka proizvoda
⦁	Ažuriranje baze podataka proizvoda

Supervizor:
⦁	Pristup bazi podataka proizvoda
⦁	Pristup servisu
⦁	Pristup sistemu za narudžbe
⦁	Pregled dokumentacije podnesene od strane korisnika

Serviser:
⦁	Pristup bazi podataka proizvoda
⦁	Pristup bazi podataka kvarova

Direktor:
⦁	Pristup svih dijelovima sistema
⦁	Pregled statistike vezane za prodaju/narudžbu
⦁	Pregled informacija o kompaniji i izmjena istih



