Opis projekta:

Moj frižider, recepti

Cilj projekta je da se kreira web aplikacija-sajt za dobijanje predloženih recepata na osnovu namirnicakoje se nalaze u frižideru korisnika. Aplikacija razlikuje tri nivoa pristupa: gost, registrovan/prijavljen korisnik i administrator.

Gost
može da pogleda ponuđene informacije na sajtu
može da pregleda sve recepte na sajtu prema kategorijama recepata
može da izvrši registraciju na sajtu Registrovan/prijavljen korisnik
može da doda recept (naziv, namirnice, slika, opis, okvirna cena recepta)
može da pregleda recepte po kategorijama
može da pretraži recepte preko opcije Pretraga
može da pretraži recepte preko opcije Moj frižider
može da promeni svoje profilne podatke (lozinka, ime, prezime, broj telefona)
može da izmeni, pregleda i obriše svoje omiljene recepte
može da oceni sve recepte na sajtu kao i da napiše svoj komentar
može da kreira jelovnik po danima (bitni su naziv jelovnika, dan u nedelji kao i recepti)
može da zahteva promenu lozinke (zaboravljena lozinka)

Administrator
može da unosi, menja i briše kategorije recepata
može da unosi, menja i briše namirnice (naziv i jedinica mere)
može da unosi, menja i briše podatke o receptima (naziv, namirnice, slika, opis, okvirna cena recepta)
može da odobri/odbije recept koji je poslao korisnik
može da odobri/odbije komentar koji je poslao korisnik
može da zabrani/odobri korisniku pravo prijavljivanja na sistem

Registraciju korisnika mora biti urađena na bezbedan način i obaveznim slanjem aktivacionog linka putem e-maila. Slanje linka koristiti i kod zahteva za promenu lozinke. Ne sme se dozvoliti registracija više korisničkih naloga sa istom e-mail adresom. E-mail adresa mora biti jedinstvena i ona predstavlja korisničko ime.
Prijavljeni korisnik može da doda svoj recept. Svaka namirnica se dodaje posebno, poželjno bi bilo da se prilikom unosa namirnice predlažu već postojeće namirnice. Ako neka namirnica ne postoji u bazi podataka obavezno je dodati. Nakon dodavanja recepta, administrator treba da odobri/odbije dodati recept. Ukoliko je recept odbijen, administrator treba da pošaljem e-mail datom korisniku sa razlozima odbijanja recepta.

Korisnik odabirom kategorija ili preko pretrage pronalazi željeni recept koji može dodati u listu omiljenih recepata. Iz liste omiljenih recepata može da kreira jelovnik za određene dane u nedelji.
Opcija Moj frižider treba da omogući korisniku pronalaženje recepata na osnovu unosa namirnicakoje korisnik ima u frižideru. U ovoj opciji svakako ponuditi namirnice prilikom kucanja imena namernica. Rezultati pretrage iz opcije Moj frižider treba da sadrže recepte kojima nedostaju najviše 2 namirnice iz frižidera. Vizuelno istaći nedostajuće namirnice. U opciji Moj frižider moglo bi se koristiti i neko drag and drop rešenje za dodavanje i/ili uklanjanje namernica.
Korisnik može svaki recept da oceni i da unese svoj komentar. To može uraditi samo jednom za svaki recept. Da bi komentar bio aktivan, mora ga odobriti administrator. Ukoliko je komentar odbijen, administrator treba da pošaljem e-mail datom korisniku sa razlozima odbijanja komentara.
Administrator treba da ima opciju preko koje će moći da pogleda sve blokirane naloge i ukoliko je to potrebno da ih odblokira.
Administratorski deo zaštiti upotrebom sesija (PHP). Sve korisničke lozinke „hešovati“ bcrypt
algoritmom.
Kreirati bazu podataka pod imenom recipe i unutar nje tabele koje će zadovoljiti sve funkcionalnosti projekta.

Zahtevi i smernice


Pored navedenih obaveznih funkcionalnosti studenti mogu dodati i neku svoju funkcionalnost koja će po njihovom mišljenju unaprediti projekat.

Upotreba spoljašnjeg fajla sa JavaScript kodom je obavezna. Programski kod (promenljive, funkcije, objekte…) pisati na engleskom jeziku, koristiti komentare u kodu, držati se uputstva koje je dato u posebnom fajlu coding_style_guide_sr.pdf

Obavezna upotreba spoljašnjeg fajla sa CSS kodom.

Pristupne parametre za povezivanje sa MySQL serverom definisati u spoljašnjem fajlu db_config.php. Za rad sa MySQL bazom koristiti PDO ekstenziju unutar PHP jezika. Deo PHP programskog koda mora biti objektno orijentisan.

Projekat treba da bude multiplatformski (Responsive) i da bude prilagođen računarima i mobilnim uređajima.

U okviru projekta obavezno treba koristiti sledeće tehnike i tehnologije: HTML, CSS, JavaScript, AJAX ili Fetch API, JSON, Bootstrap, PHP i MySQL. . Za slanje mailova koristiti PHPMailer klasu (https://github.com/PHPMailer/PHPMailer).

Programski deo koji koristi AJAX ili Fetch API tehniku mora da manipuliše sa podacima iz baze podataka. Preporuka za korišćenje AJAX ili Fetch API tehnika: provera validnosti podataka, nabavljanje podataka iz baze podataka, registracija i

provere kod registracije.

Na stranicama gde se radi validacija podataka obavezno uraditi validaciju na klijentskoj i serverskoj strani.

Projekat je potrebno postaviti na školski web server. Svaki pojedinac ili tim će dobiti svoje pristupne parametre putem e-maila.

Upotreba ostalih tehnologija, biblioteka i API-a je opciona.

Koristiti Trello sistem unutar tima i dodeliti pristup predmetnom nastavniku (prowebing@gmail.com i helenatmanojlovic@gmail.com). Tokom rada na projektu definisati zadatke i dodeliti ih članovima tima. Potrebne liste u Trello sistemu: Additional Documents (Info), Brainstorming, To do, Doing, Testing, Done, To be Archived. Opise zadataka možete pisati na srpskom jeziku.

Svaki tim ili pojedinac treba da koristi Git VCS sistem (Version Control System) i zajedno sa njim neko hosting rešenje (GitHub, BitBucket, GitLab…). Dodeliti pristup predmetnom nastavniku (chole@vts.su.ac.rs, helena@vts.su.ac.rs). Tokom rada na projektu potrebno je postavljati programski kod na svoj Git repozitorijum.

Projekat se predaje u elektronskom obliku (programski kod, .sql fajlovi, i projektna dokumentacija). Dokumentacija se izrađuje prema datom šablonu. Sve je potrebno postaviti na svoj Git repozitorijum.

Tokom realizacije projekta veliki naglasak treba da bude na sigurnosti i proveri unetih podataka.

Mogu se koristiti BESPLATNI šabloni za Bootstrap 5, koji SE MORAJU MODIFIKOVATI ZA POTREBE PROJEKTA, ne možete koristi u potpunosti isti šablon. Ukoliko je korišćen šablon, navesti kao informaciju u dokumentaciji! Na web server se mogu postavljati samo besplatni materijali! Možete koristiti samo BESPLATNE fotografije (sopstvene ili preuzete sa sajtova poput www.freeimages.com i/ili www.unsplash.com ).

Subotica, 24.02.2024.
