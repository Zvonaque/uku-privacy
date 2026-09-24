---
title: Pravila privatnosti — UKU
---

[English](./)

# Pravila privatnosti — UKU

_Na snazi od: 23. rujna 2026. · Odnosi se na aplikaciju UKU („Učiti kako učiti") tijekom zatvorene beta faze._

UKU je aplikacija za učenje radnih navika namijenjena djeci školske dobi i
njihovim roditeljima, a izradio ju je Zvonimir Jukić. Pomaže djetetu
isplanirati školske aktivnosti, svakodnevno potvrditi što je odrađeno i
podijeliti taj napredak s povezanim roditeljem. Ova pravila jednostavnim
jezikom objašnjavaju koje podatke aplikacija obrađuje i što s njima radimo.
Namjerno su kratka — aplikacija prikuplja vrlo malo podataka.

## Što prikupljamo

**Podaci o računu.** Adresa e-pošte, odabrana uloga (dijete ili roditelj) i
ime koje sami odaberete (dovoljno je ime ili nadimak, a možete ga promijeniti u
postavkama). E-pošta služi za prijavu i za slanje poruka vezanih uz račun
(primjerice potvrde registracije) i nikada se ne prikazuje drugim korisnicima.
Ime vide samo članovi obitelji povezani s vašim računom te druga osoba u
obiteljskoj pozivnici dok ta pozivnica čeka odgovor, kako bi obje strane znale
s kim se povezuju. Ne tražimo puna imena i prezimena, datume rođenja,
fotografije ni brojeve telefona.

**Sadržaj koji stvarate u aplikaciji.** Kalendari, grupe aktivnosti,
aktivnosti, zakazani termini, dnevne potvrde i njihov status pregleda,
događaji (poput zadaće ili ispita) te kratke bilješke između djeteta i
povezanog roditelja. Taj je sadržaj vidljiv samo djetetu koje ga je stvorilo i
roditeljima koje je obitelj izričito povezala pozivnicom — nikada drugim
korisnicima ni javnosti.

**Podaci o obavijestima.** Ako su obavijesti uključene, aplikacija pohranjuje
token uređaja (identifikator koji dodjeljuje Googleova usluga Firebase Cloud
Messaging kako bismo obavijest mogli dostaviti na taj uređaj) i evidenciju o
tome koje su obavijesti poslane.

**Podaci o rušenju aplikacije.** Ako se aplikacija sruši, tehnički izvještaj
(pogreška, dijagnostički zapis, model uređaja, verzija operativnog sustava,
verzija aplikacije i nasumični identifikator instalacije) šalje se Googleovoj
usluzi Firebase Crashlytics kako bismo problem pronašli i ispravili. Izvještaji
o rušenju ne sadrže podatke o računu ni sadržaj koji ste stvorili — podesili
smo ih tako da ne nose nikakve identifikatore korisnika.

## Što NE prikupljamo

- Nema oglasa, oglasnih mreža ni personaliziranih oglasa — aplikacija uopće ne sadrži oglase.
- Nema analitike ponašanja ni praćenja.
- Nema podataka o lokaciji, kontaktima, fotografijama, mikrofonu ni kameri.
- Podatke nikada ne prodajemo niti iznajmljujemo.
- Ne izrađujemo profile djece.

## Gdje se podaci nalaze

Podaci aplikacije pohranjeni su kod pružatelja usluge **Supabase**, na
poslužiteljima u **Europskoj uniji**. Dostavu obavijesti i izvještaje o rušenju
omogućuje **Google Firebase** (Cloud Messaging i Crashlytics). E-poruke vezane
uz račun (potvrda registracije i kodovi za oporavak lozinke) šalju se putem
Googleove usluge **Gmail**. Ti pružatelji obrađuju podatke isključivo u naše
ime, radi rada usluge. Svi se podaci prenose šifrirano.

## Zašto ih obrađujemo (pravna osnova)

Podatke o računu i sadržaj aplikacije obrađujemo kako bismo pružili uslugu na
koju se obitelj prijavila; podatke o obavijestima kako bismo dostavili
podsjetnike koje je obitelj postavila (roditeljske se obavijesti uključuju
dobrovoljno); a podatke o rušenju na temelju našeg legitimnog interesa da
aplikacija ispravno radi. Podatke ne koristimo ni u koju drugu svrhu.

## Podaci djece i privola roditelja

UKU je namijenjen djeci i u skladu s tim postupa s njihovim podacima. Prema
hrvatskom zakonu dijete mlađe od 16 godina ne može samo dati privolu za obradu
podataka — **za otvaranje dječjeg računa potrebna je privola roditelja ili
zakonskog skrbnika**. Tijekom zatvorene bete računi se otvaraju unutar poznatog
kruga obitelji i učitelja koji sudjeluju u razvoju, uz sudjelovanje roditelja
pri postavljanju. Ako smatrate da dijete koristi UKU bez privole roditelja,
javite nam se i račun ćemo ukloniti.

## Koliko dugo čuvamo podatke

Podatke čuvamo dok je račun aktivan.

<a id="delete-account"></a>

## Brisanje računa

**U aplikaciji.** Dok ste prijavljeni, otvorite **Postavke** (zupčanik na vrhu
početnog zaslona) → **Račun** → **Obriši račun** i upišite prikazanu frazu za
potvrdu. Time se odmah brišu vaš račun i svi podaci koje sadrži — kalendar,
grupe aktivnosti, aktivnosti, dnevne potvrde, događaji, bilješke te povezanost s
roditeljem ili djetetom. Brisanje se ne može poništiti i nema razdoblja
oporavka.

**E-poštom.** U svakom trenutku možete zatražiti i **brisanje računa i svih
pripadajućih podataka** ili **izvoz njihove kopije**, slanjem poruke na
**zvonimir.jukic.dev@gmail.com** s adrese e-pošte tog računa (za dječji račun,
s adrese roditelja koji je dao privolu). Navedite adresu e-pošte računa koji
želite obrisati. Zahtjeve za brisanje ispunjavamo u roku od 30 dana i potvrđujemo
odgovorom. Roditelj koji traži brisanje dječjeg računa koristi ovaj kanal:
brisanje u aplikaciji uklanja samo račun koji je prijavljen.

## Vaša prava

Na temelju Opće uredbe o zaštiti podataka (GDPR) možete zatražiti pristup,
ispravak, izvoz ili brisanje svojih podataka (ili podataka svojeg djeteta) te
uložiti prigovor na obradu ili zatražiti njezino ograničenje — sve na
zvonimir.jukic.dev@gmail.com. Također imate pravo podnijeti pritužbu nadzornom
tijelu; u Hrvatskoj je to AZOP (Agencija za zaštitu osobnih podataka, azop.hr).

## Izmjene

Ako se ova pravila promijene, važeća će verzija uvijek biti na ovoj adresi, s
gore navedenim datumom stupanja na snagu. Tijekom bete o svakoj važnoj promjeni
obavijestit ćemo testere izravno.

## Kontakt

Zvonimir Jukić — zvonimir.jukic.dev@gmail.com
