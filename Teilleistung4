# Teilleistung4

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Onlineshop</title>
<script>

//Basisklasse//
class medienartikel {

    #artikelnummer;
    #versandart;
    #bezahlmethode;
    #altersfreigabe;
    #preis;
    #condition;
    #dateofrelease;
    #datenträger;
    #titel;
    #sprache;

    constructor(artikelnummer,versandart,bezahlmethode,altersfreigabe,preis,condition,dateofrelease,datenträger,titel,sprache){
    this.#artikelnummer= artikelnummer;
    this.#versandart = versandart;
    this.#bezahlmethode = bezahlmethode;
    this.#altersfreigabe = altersfreigabe;
    this.#preis = preis;
    this.#condition = condition;
    this.#dateofrelease = dateofrelease;
    this.#datenträger = datenträger;
    this.#titel = titel;
    this.#sprache = sprache;
}
setartikelnummer(artikelnummer){
    this.#artikelnummer=artikelnummer;
        }
getartikelnummer(){
    return this.#artikelnummer;
        }
setversandart(versandart){
    this.#versandart=versandart;
        }
getversandart(){
    return this.#versandart;
        }
setbezahlmethode(bezahlmethode){
    this.#bezahlmethode = bezahlmethode;
}
getbezahlmethode(){
    return this.#bezahlmethode;
}
setaltersfreigabe(altersfreigabe){
    this.#altersfreigabe  = altersfreigabe;
}
getaltersfreigabe(){
    return this.#altersfreigabe ;
}
setpreis (preis) {
    this.#preis = preis;
}
getpreis() {
    return this.#preis;
}
setcondition (condition) {
    this.#condition = condition;
}
getcondition() {
    return this.#condition;
}
getdateofrelease(){
    return this.#dateofrelease ;
}
setdateofrelease(dateofrelease) {
    this.#dateofrelease = dateofrelease;
}
getofrelease(){
    return this.#dateofrelease;
}
setdatenträger(datenträger) {
    this.#datenträger = datenträger;
}
getdatenträger(){
    return this.#datenträger;
}
settitel(titel){
    this.#titel = titel;
}
gettitel(){
    return this.#titel;
}
setsprache(sprache) {
    this.#sprache = sprache;
}
getsprache(){
    return this.#sprache;
}

Medienartikelausgeben(){
        document.write("<tr><td>"+ this.getartikelnummer()+"</td>");
        document.write("<td>" + this.getversandart()+"</td>");
        document.write("<td>" + this.getbezahlmethode()+"</td>");
        document.write("<td>" + this.getaltersfreigabe()+"</td>");
        document.write("<td>" + Math.round(this.getpreis())+"</td>");
        document.write("<td>" + this.getcondition()+"</td>");
        document.write("<td>" + this.getdateofrelease()+"</td>");
        document.write("<td>" + this.getdatenträger()+"</td>");
        document.write("<td>" + this.gettitel()+"</td>");
        document.write("<td>" + this.getsprache()+"</td>");
}

retoure(condition, preis){
	  this.setcondition("B");
      this.setpreis((((this.getpreis()+ Number.EPSILON)*10)/10)*0.90)}}

//Unterklasse 1
class movie extends medienartikel{

#seitenverhältnis;
#verpackungsabmessungen;
#herstellerreferenz;
#regisseur;
#medienformat;
#laufzeit;
#untertitel;
#studio;
#ASIN;
#sonstiges;

constructor(artikelnummer,versandart,bezahlmethode,altersfreigabe,preis,condition,dateofrelease,datenträger,titel,sprache,seitenverhältnis,verpackungsabmessungen,herstellerreferenz,regisseur,medienformat,laufzeit,untertitel,studio,ASIN,sonstiges){
super(artikelnummer,versandart,bezahlmethode,altersfreigabe,preis,condition,dateofrelease,datenträger,titel,sprache);
this.#seitenverhältnis = seitenverhältnis;
this.#verpackungsabmessungen = verpackungsabmessungen;
this.#herstellerreferenz = herstellerreferenz;
this.#regisseur = regisseur;
this.#medienformat = medienformat;
this.#laufzeit = laufzeit;
this.#untertitel = untertitel;
this.#studio = studio;
this.#ASIN = ASIN;
this.#sonstiges = sonstiges;}

setseitenverhältnis(seitenverhältnis) {
this.#seitenverhältnis =seitenverhältnis;
    }
getseitenverhältnis(){
return this.#seitenverhältnis;
}
setverpackungsabmessungen(verpackungsabmessungen) {
this.#verpackungsabmessungen =verpackungsabmessungen;
    }
getverpackungsabmessungen(){
return this.#verpackungsabmessungen;
}
setherstellerreferenz(herstellerreferenz) {
this.#herstellerreferenz =herstellerreferenz;
    }
getherstellerreferenz(){
return this.#herstellerreferenz;
}
setregisseur(regisseur) {
this.#regisseur =regisseur;
    }
getregisseur(){
return this.#regisseur;
}
setmedienformat(medienformat) {
this.#medienformat =medienformat;
    }
getmedienformat(){
return this.#medienformat;
}
setlaufzeit(laufzeit) {
this.#laufzeit =laufzeit;
    }
getlaufzeit(){
return this.#laufzeit;
}
setuntertitel(untertitel) {
this.#untertitel =untertitel;
    }
getuntertitel(){
return this.#untertitel;
}
setstudio(studio) {
this.#studio =studio;
    }
getstudio(){
return this.#studio;
}
setASIN(ASIN) {
this.#ASIN =ASIN;
    }
getASIN(){
return this.#ASIN;
}
setsonstiges(sonstiges) {
this.#sonstiges =sonstiges;
    }
getsonstiges(){
return this.#sonstiges;
}
Movieausgabe(){
     this.Medienartikelausgeben();
     document.write("<td>"+this.getseitenverhältnis()+"<td>");
     document.write("<td>"+this.getverpackungsabmessungen()+"<td>");
     document.write("<td>"+ this.getherstellerreferenz()+"<td>");
     document.write("<td>"+ this.getregisseur()+"<td>");
     document.write("<td>"+ this.getmedienformat()+"<td>");
     document.write("<td>"+ this.getlaufzeit()+"<td>");
     document.write("<td>"+ this.getuntertitel()+"<td>");
     document.write("<td>" + this.getstudio()+"<td>");
     document.write("<td>"+ this.getASIN()+"<td>");
     document.write("<td>"+ this.getsonstiges()+"<td></tr>");
}

Filmausgabe(){
document.write("<tr>"+"<td>" + this.getartikelnummer() + "</td>"+"<td>" + this.getversandart() + "</td>"+"<td>" + this.getbezahlmethode() + "</td>"+"<td>" + this.getaltersfreigabe() + "</td>"+"<td>" + this.getpreis() + " € " + "</td>"+"<td>" + this.getcondition() + "</td>"+"<td>" + this.getdateofrelease() + "</td>"+"<td>" + this.getdatenträger() + "</td>"+"<td>" + this.gettitel() + "</td>"+"<td>" + this.getsprache() + "</td>"+"<td>" + this.getseitenverhältnis() + "</td>"+"<td>" + this.getverpackungsabmessungen() + "</td>"+"<td>" + this.getherstellerreferenz() + "</td>"+"<td>" + this.getregisseur() + "</td>"+"<td>" + this.getmedienformat() + "</td>"+"<td>" + this.getlaufzeit() + "</td>"+"<td>" + this.getuntertitel() + "</td>"+"<td>" + this.getstudio() + "</td>"+"<td>" + this.getASIN() + "</td>"+"<td>" + this.getsonstiges() + "</td>" + "</tr>")}}  

let movie1= new movie("23971294","Kein Versand", "Abonemment", "FSK 16",5.40,"B"," 24. Oktober 2019","DVD", "Apocalypse Now","Deutsch (Dolby Digital 5.1), Englisch (Dolby Digital 5.1)","16:9 - 2.35:1"," 13.8 x 1.5 x 19.2 cm; 85 Gramm"," 37074665","Francis Ford Coppola","Dolby, PAL, Original Recording Remastered, Breitbild"," 2 Stunden und 56 Minuten","Deutsch","Studiocanal","B07S7763Z1","Final Cut Edition");
let movie2= new movie("23971294","Kein Versand", "Normalkauf", "FSK 12",8.50,"B"," 13. September 1947","DVD", "Die Spur des Falkken","Deutsch (Dolby Digital 5.1), Englisch (Dolby Digital 5.1)","16:9 - 2.35:1"," 13.8 x 1.5 x 19.2 cm; 85 Gramm"," 32397239","Dashel Hammet","Dolby, PAL, Original Recording Remastered, Breitbild"," 1 Stunden und 37 Minuten","Deutsch","Warnerbrothers","B077289392","Normal Edition");

//2.Unterklasse
class album extends medienartikel{

    #musikgenre;
    #interpret;
    #label;
    #single;
    #EAN;

    constructor(artikelnummer,versandart,bezahlmethode,altersfreigabe,preis,condition,dateofrelease,datenträger,titel,sprache,musikgenre,interpret,label,single,EAN){
    super(artikelnummer,versandart,bezahlmethode,altersfreigabe,preis,condition,dateofrelease,datenträger,titel,sprache);
    this.#musikgenre = musikgenre;
    this.#interpret = interpret;
    this.#label = label;
    this.#single = single;
    this.#EAN = EAN;
    }

setmusikgenre(musikgenre) {
    this.#musikgenre = musikgenre;
        }
getmusikgenre(){
    return this.#musikgenre;
}
setinterpret(interpret) {
    this.#interpret = interpret;
        }
getinterpret(){
    return this.#interpret;
}
setlabel(label) {
    this.#label = label;
        }
getlabel(){
    return this.#label;
}
setsingle(single) {
    this.#single = single;
}
getsingle(){
    return this.#single;
}
setEAN(EAN) {
    this.#EAN = EAN;
        }
getEAN(){
    return this.#EAN;
}
Albumausgabe(){

         this.Medienartikelausgeben();
         document.write("<td>"+this.getmusikgenre()+"<td>");
         document.write("<td>"+this.getinterpret()+"<td>");
         document.write("<td>"+ this.getlabel()+"<td>");
         document.write("<td>"+ this.getsingle()+"<td>");
         document.write("<td>"+ this.getEAN()+"<td>");}}

//3.Unterklasse
class ebook extends medienartikel{
    #autor;
    #verlag;
    #seitenzahl;
    #ISBN;
    #abmessung;
    #literaturgenre;
    #auflage;

    constructor(artikelnummer,versandart,bezahlmethode,altersfreigabe,preis,condition,dateofrelease,datenträger,titel,sprache,autor,verlag,seitenzahl,ISBN,abmessung,literaturgenre,auflage){
    super(artikelnummer,versandart,bezahlmethode,altersfreigabe,preis,condition,dateofrelease,datenträger,titel,sprache);
    this.#autor = autor;
    this.#verlag = verlag;
    this.#seitenzahl = seitenzahl;
    this.#ISBN = ISBN;
    this.#abmessung = abmessung;
    this.#literaturgenre = literaturgenre;
    this.#auflage = auflage;
    }
setautor(autor) {
    this.#autor =autor;
}
getautor(){
    return this.#autor;
}
setverlag(verlag) {
    this.#verlag =verlag;
}
getverlag(){
    return this.#verlag;
}
setseitenzahl(seitenzahl) {
    this.#seitenzahl =seitenzahl;
}
getseitenzahl(){
    return this.#seitenzahl;
}
setISBN(ISBN) {
    this.#ISBN =ISBN;
        }
getISBN(){
    return this.#ISBN;
}
setabmessung(abmessung) {
    this.#abmessung =abmessung;
}
getabmessung(){
    return this.#abmessung;
}
setliteraturgenre(literaturgenre) {
    this.#literaturgenre =literaturgenre;
}
getliteraturgenre(){
    return this.#literaturgenre;
}
setauflage(auflage) {
    this.#auflage =auflage;
}
getauflage(){
    return this.#auflage;
}
Ebookausgabe(){
        
        this.Medienartikelausgeben();
        document.write("<td>"+ this.getautor()+"<td>");
        document.write("<td>"+ this.getverlag()+"<td>");
        document.write("<td>"+ this.getseitenzahl()+"<td>");
        document.write("<td>"+ this.getISBN()+"<td>");
        document.write("<td>"+ this.getabmessung()+"<td>");
        document.write("<td>"+ this.getliteraturgenre()+"<td>");
        document.write("<td>"+ this.getauflage()+"<td>");}}

const medien =[
    //Alben
    {artikelnummer:"1234567",versandart:"Expressversand",bezahlmethode:"Paypal",altersbeschränkung:"none",preis:11.99,condition:"A",dateofrelease:"1979",datenträger:"MP3 Download",titel: "London Calling",sprache:"Englisch",musikgenre:"Punk/Rock",interpret:"The Clash",label:"SONY MUSIC CATALOG",single:"Train in Vain",EAN:"B00002MVQO"},
    {artikelnummer:"1234567",versandart:"Standardversand",bezahlmethode:"Onlinebanking",altersbeschränkung:"none",preis:11.78,condition:"A",dateofrelease:"2003",datenträger:"CD",titel:"WWII",sprache:"Englisch/Deutsch",musikgenre:"Industrial Metal",interpret:"KMFDM",label:"Sanctuary",single:"WWII",EAN:"B0000CABGD"},
    {artikelnummer:"2379126",versandart:"Expressversand",bezahlmethode:"Paypal",altersbeschränkung:"none",preis:17.99,condition:"A",dateofrelease:"1959",datenträger:"Vinyl",titel:"Kind of Blue",sprache:"Englisch", musikgenre:"Jazz",interpret:"Miles Davis",label:"SONY Legacy",single:"So What",EAN:"B01FX5UG2S"},
    {artikelnummer:"1234567",versandart:"Lieferung an Packstation",bezahlmethode:"Onlinebanking",altersbeschränkung:"none",preis:6.79,condition:"A",dateofrelease:"2016",datenträger:"CD",titel: "High und Hunrig 2 ",sprache:"Deutsch",musikgenre:"Rap/Hip Hop",interpret:"Bonez MC",label:"AUF!KEINEN!FALL!",single:"Optimal",EAN:"B01EVZDZTM"},
    {artikelnummer:"232384",versandart:"Expressversand",bezahlmethode:"Paypal",altersbeschränkung:"none",preis:6.79,condition:"A",dateofrelease:"2011",datenträger:"CD",titel:"Debussy: Children´s Corner",sprache:"Keine Sprache",musikgenre:"Klassik",interpret:"Claude Debussy",label:"Atma Classique",single:"Claire de Lune",EAN:"B005OV1NEC"},
    //Bücher
    {artikelnummer:"127384392",versandart:"Standardversand",bezahlmethode:"Rechnung",altersbeschränkung:"none",preis:11,condition:"A",dateofrelease:"1932",datenträger:"Buch",titel:"Schöne neue Welt",sprache:"Deutsch",autor:"Aldous Huxley",verlag:"Fischer Verlag",seitenzahl:"363 Seiten",ISBN:"978-3-596-90573-7",abmessung:"19 cm x 12,5 cm",literaturgenre:"Science Fiction",auflage:"7.Auflage" },
    {artikelnummer:"823719293",versandart:"Expressversand",bezahlmethode:"Paypal",altersbeschränkung:"none",preis:8.75,condition:"A",dateofrelease:"2018",datenträger:"Leseheft",titel: "Hamlet",sprache:"Englisch",autor: "William Shakespeare",verlag:"Hamburger Lesehefte",seitenzahl:"84 Seiten",ISBN:"978-3-87291-130-8",abmessung:"15 cm x 7,5cm",literaturgenre:"Drama",auflage:"12.Auflage" },
    {artikelnummer:"738283922",versandart:"Standardversand",bezahlmethode:"Paypal",altersbeschränkung:"none",preis:15.45,condition:"A",dateofrelease:"1994",datenträger:"Taschenbuch",titel: "Vom Kriege",sprache:"Deutsch",autor:"Carl von Clausewitz",verlag:"Reclam",seitenzahl:"422 Seiten",ISBN:"978-3-15-009961-2",abmessung:"9 cm x 7 cm",literaturgenre:"Kriegsliteratur",auflage:"7. Auflage" },
    {artikelnummer:"738238299",versandart:"Expressversand",bezahlmethode:"Überweisung",altersbeschränkung:"none",preis:7.99,condition:"A",dateofrelease:"1953",datenträger:"Taschenbuch",titel: "Warten auf Godot",sprache:"Englisch,Deutsch,Französisch",autor:"Samuel Beckett",verlag:"Suhrkamp",seitenzahl:"121 Seiten",ISBN:"978-3-518-36501-4",abmessung:"12 cm x 8 cm",literaturgenre:"Drama",auflage:"37.Auflage" },
    {artikelnummer:"128792839",versandart:"Standardversand",bezahlmethode:"Paypal",altersbeschränkung:"none",preis:12.90,condition:"A",dateofrelease:"1968",datenträger:"Buch",titel: "Früchte des Zorns",sprache:"Deutsch",autor:"John Steinbeck",verlag:"dtv",seitenzahl:"543",ISBN:"978-3-423-10474-6",abmessung:"14 cm x 12 cm ",literaturgenre:"Roman",auflage:"11.Auflage" },
];
  
for ( var i = 0; i < 10; i++ ){
console.log(medien[i]);}	

</script>
<h1 style="font-size: 60px">Medienshop</h1>
<h2>Herzlich willkommen beim Medienshop!</h2>
<table cellspacing="20"; cellpadding="3"; style="border: 3pt solid rgb(35, 32, 216); margin: auto; margin-top: 30px; text-align: center;">
    <h2>Filme</h2>
    <thead>
        <tr>
          <th style="font-size: 18px">Artikelnummer</th>
          <th style="font-size: 18px">Versandart</th>
          <th style="font-size: 18px">Bezahlmethode</th>
          <th style="font-size: 18px">Altersbeschränkung</th>
          <th style="font-size: 18px">Preis</th>
          <th style="font-size: 18px">Warenklasse</th>
          <th style="font-size: 18px">Dateofrelease</th>
          <th style="font-size: 18px">Datenträger</th>
          <th style="font-size: 18px">Titel</th>
          <th style="font-size: 18px">Sprache</th>
          <th style="font-size: 18px">Seitenverhältnis</th>
          <th style="font-size: 18px">Verpackungsabmessungen</th>
          <th style="font-size: 18px">Herstellerreferenz</th>
          <th style="font-size: 18px">Regisseur</th>
          <th style="font-size: 18px">Medienformat</th>
          <th style="font-size: 18px">Laufzeit</th>
          <th style="font-size: 18px">Untertitel</th>
          <th style="font-size: 18px">Studio</th>
          <th style="font-size: 18px">ASIN</th>
          <th style="font-size: 18px">Sonstiges</th>
        </tr>
    </thead>
<script>
movie1.retoure()
movie2.retoure()
movie1.Filmausgabe()
movie2.Filmausgabe()
</script>
</table>
<table cellspacing="20"; cellpadding="3"; style="border: 3pt solid rgb(35, 32, 216); margin: auto; margin-top: 30px; text-align: center;">
<h2>Musikalben</h2>
  <thead>
    <tr>
        <th style="font-size: 18px">Artikelnummer</th>
        <th style="font-size: 18px">Versandart</th>
        <th style="font-size: 18px">Bezahlmethode</th>
        <th style="font-size: 18px">Altersbeschränkung</th>
        <th style="font-size: 18px">Preis</th>
        <th style="font-size: 18px">Warenklasse</th>
        <th style="font-size: 18px">Dateofrelease</th>
        <th style="font-size: 18px">Datenträger</th>
        <th style="font-size: 18px">Titel</th>
        <th style="font-size: 18px">Sprache</th>
        <th style="font-size: 18px">Musikgenre</th>
        <th style="font-size: 18px">Interpret</th>
        <th style="font-size: 18px">Label</th>
        <th style="font-size: 18px">Single</th>
        <th style="font-size: 18px">EAN</th>
    </tr>
  </thead>
<script>
for ( var i = 0; i < 5; i++ ){
document.write("<tr><td>" + medien[i].artikelnummer + "</td><td>" + medien[i].versandart + "</td><td>" + medien[i].bezahlmethode +  "</td><td>" + medien[i].altersbeschränkung + "</td><td>" + medien[i].preis + " € " + "</td><td>" + medien[i].condition + "</td><td>" + medien[i].dateofrelease + "</td><td>" + medien[i].datenträger + "</td><td>" + medien[i].titel + "</td><td>" + medien[i].sprache + "</td><td>" + medien[i].musikgenre + "</td><td>" + medien[i].interpret + "</td><td>" + medien[i].label + "</td><td>" + medien[i].single + "</td><td>" + medien[i].EAN + "</td>" + "</tr>")}	
</script>
</table>
<table cellspacing="20"; cellpadding="3"; style="border: 3pt solid rgb(35, 32, 216); margin: auto; margin-top: 30px; text-align: center;">
  <thead>
<h2>Bücher</h2>
    <tr>
        <th style="font-size: 18px">Artikelnummer</th>
        <th style="font-size: 18px">Versandart</th>
        <th style="font-size: 18px">Bezahlmethode</th>
        <th style="font-size: 18px">Altersbeschränkung</th>
        <th style="font-size: 18px">Preis</th>
        <th style="font-size: 18px">Warenklasse</th>
        <th style="font-size: 18px">Dateofrelease</th>
        <th style="font-size: 18px">Datenträger</th>
        <th style="font-size: 18px">Titel</th>
        <th style="font-size: 18px">Sprache</th>
        <th style="font-size: 18px">Autor</th>
        <th style="font-size: 18px">Verlag</th>
        <th style="font-size: 18px">Seitenzahl</th>
        <th style="font-size: 18px">ISBN</th>
        <th style="font-size: 18px">Abmessung</th>
        <th style="font-size: 18px">Literaturgenre</th>
        <th style="font-size: 18px">Auflage</th>
     </tr>
  </thead>
<script>
      for ( var i = 5; i < 10; i++ ){
document.write("<tr><td>" + medien[i].artikelnummer + "</td><td>" + medien[i].versandart + "</td><td>" + medien[i].bezahlmethode + "</td><td>" + medien[i].altersbeschränkung + "</td><td>" + medien[i].preis + " € " + "</td><td>" + medien[i].condition + "</td><td>" + medien[i].dateofrelease + "</td><td>" + medien[i].datenträger + "</td><td>" + medien[i].titel + "</td><td>" + medien[i].sprache + "</td><td>" + medien[i].autor + "</td><td>" + medien[i].verlag + "</td><td>" + medien[i].seitenzahl + "</td><td>" + medien[i].ISBN + "</td><td>" + medien[i].abmessung + "</td><td>" + medien[i].literaturgenre + "</td><td>" + medien[i].auflage + "</td>" + "</tr>")}	
</script>
</table>
</body>
</html>
