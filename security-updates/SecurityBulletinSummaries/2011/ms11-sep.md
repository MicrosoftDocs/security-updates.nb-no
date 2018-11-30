---
title: Sammendrag av Microsofts sikkerhetsbulletiner for september 2011
TOCTitle: MS11-SEP
ms:assetid: ms11-sep
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms11-sep(v=Security.10)
ms:contentKeyID: 61315235
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for september 2011

Publisert: 13. september 2011 | Oppdatert: 13. september 2011

**Versjon:** 1.1

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i september 2011.

I forbindelse med utgivelsen av sikkerhetsbulletinene for september 2011 erstatter dette sammendraget av bulletiner forhåndsvarslingen for bulletiner som ble utstedt 8. september 2011. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://go.microsoft.com/fwlink/?linkid=217213).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 14. september 2011 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for september på webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487951). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://go.microsoft.com/fwlink/?linkid=217214).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

## Kortfattede sammendrag

Følgende tabell viser et sammendrag av sikkerhetsbulletinene for denne måneden etter alvorlighetsgrad.

Hvis du vil ha informasjon om berørt programvare, kan du se den neste delen, **Berørt programvare og nedlastingssteder**.

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-ID</th>
<th style="border:1px solid black;">Bulletintittel og kortfattet sammendrag</th>
<th style="border:1px solid black;">Maksimal alvorlighetsgrad og følger av sikkerhetsproblemet</th>
<th style="border:1px solid black;">Krav om omstart</th>
<th style="border:1px solid black;">Berørt programvare</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i WINS kan tillate rettighetsutvidelse (2571621)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows Internet Name Service (WINS). Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en bruker mottar en spesiallaget WINS-replikeringspakke på et berørt system som kjører WINS-tjenesten. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte dette sikkerhetsproblemet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Rettighetsutvidelse</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Windows-komponenter kan tillate ekstern kjøring av kode (2570947)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker åpner en legitim RTF-fil (rikt tekstformat) eller tekstfil (TXT) eller et Word-dokument (DOC) som ligger i samme nettverkskatalog som en spesiallaget DLL-fil (dynamic-link library). En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (2587505)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer i Microsoft Office. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-fil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Ved å installere og konfigurere Office File Validation (OFV) slik at mistenkelige filer ikke åpnes, hindres angrepsvektorene i å utnytte sikkerhetsproblemene som beskrives i CVE-2011-1986 og CVE-2011-1987.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server-programvare</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Microsoft Office kan tillate ekstern kjøring av kode (2587634)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Office. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Office-fil, eller hvis en bruker åpner en legitim Office-fil som ligger i samme nettverkskatalog som en spesiallaget biblioteksfil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Microsoft SharePoint kan tillate rettighetsutvidelse (2451858)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer i Microsoft SharePoint og Windows SharePoint Services. De mest alvorlige sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en bruker klikker på en spesiallaget URL eller går til et spesiallaget webområde. For de mest alvorlige sikkerhetsproblemene reduseres risikoen for brukere med Internet Explorer 8 og Internet Explorer 9 som går til et SharePoint-område i Internett-sonen, fordi XSS-filteret i Internet Explorer 8 og Internet Explorer 9 som standard bidrar til å blokkere angrep i Internett-sonen. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 er imidlertid ikke aktivert som standard i intranettsonen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Rettighetsutvidelse</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Server-programvare</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført etter bulletin-ID og deretter etter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan bruker jeg denne tabellen?**  

Bruk denne tabellen til å få mer informasjon om sannsynligheten for angrep i form av kjøring av kode og tjenestenekt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen av denne månedens oppdateringer. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/security/cc998259.aspx).

I kolonnene nedenfor refererer "ny programvareversjon" til den aktuelle programvaren, og "eldre programvareversjoner" refererer til alle eldre, støttede versjoner av den aktuelle programvaren, slik de er oppført i tabellene Berørt programvare eller Uberørt programvare i bulletinen.

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-ID</th>
<th style="border:1px solid black;">Tittel på sikkerhetsproblem</th>
<th style="border:1px solid black;">CVE-ID</th>
<th style="border:1px solid black;">Vurdering av utnyttelsesgrad for kjøring av kode i ny programvareversjon</th>
<th style="border:1px solid black;">Vurdering av utnyttelsesgrad for kjøring av kode i eldre programvareversjoner</th>
<th style="border:1px solid black;">Vurdering av utnyttelsesgrad for tjenestenekt</th>
<th style="border:1px solid black;">Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225825">MS11-070</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i WINS som kan føre til lokal rettighetsutvidelse</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1984">CVE-2011-1984</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=223632">MS11-071</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med usikker bibliotekinnlasting i Windows-komponenter</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1991">CVE-2011-1991</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">&quot;Use after free&quot; WriteAV-sikkerhetsproblem med Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1986">CVE-2011-1986</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med datatabellindeksering utenfor område i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1987">CVE-2011-1987</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med heapfeil i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1988">CVE-2011-1988</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med betinget uttrykksanalyse i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1989">CVE-2011-1989</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225047">MS11-072</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med datatabellindeksering utenfor område i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1990">CVE-2011-1990</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med usikker bibliotekinnlasting i Office-komponent</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1980">CVE-2011-1980</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=225103">MS11-073</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med ikke-initialisert objektpeker i Office</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1982">CVE-2011-1982</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med XSS i SharePoint-kalender</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0653">CVE-2011-0653</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med sanitisering i HTML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon<br />
<br />
Dette sikkerhetsproblemet er offentliggjort</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med skriptinjeksjon i Editform</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1890">CVE-2011-1890</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med gjenspeiling av kontaktdetaljer i XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1891">CVE-2011-1891</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med tilgjengeliggjøring av eksterne filer i SharePoint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1892">CVE-2011-1892</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=204797">MS11-074</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med XSS i SharePoint</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1893">CVE-2011-1893</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

Følgende tabeller viser bulletinene etter store programvarekategorier og alvorlighetsgrad.

**Hvordan bruker jeg disse tabellene?**  

Bruk disse tabellene til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det kommer noen sikkerhetsoppdateringer som angår installasjonen din. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for ett enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

<table style="border:1px solid black;" class="dataTable">
                <tr><th colspan="3" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 3</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70f944b0-9bf0-4168-b150-67d2ff68df2d">Windows XP Service Pack 3</a>
                    <br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b9debed-edbb-43e1-b755-0faf01980289">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e6ac3b2-752e-49a0-84e5-5a8dfe955299">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d44274d2-0401-4fd8-bc4f-c59f6d81c34f">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9378339-c58e-4e84-9427-85aeb35b0d99">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=935720ee-cee0-42c2-965e-ce1b07e95e1a">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 SP2 for Itanium-baserte systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c35c71a8-13b4-47a6-9763-06f6f65327b1">Windows Server 2003 med SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=78c2ac72-da89-42a4-bff9-79551b5d3c4e">Windows Server 2003 med SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15840336-4886-4a1b-8c1e-2c535c3938f7">Windows Vista Service Pack 2</a>
                    <br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e80739b4-89bb-4317-8381-991244a71cb8">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a9039660-3cc2-470d-a0a5-a70f78074495">Windows Server 2008 for 32-biters systemer Service Pack 2</a>*<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05c39ab3-7b57-4147-8913-df5df6005799">Windows Server 2008 for 32-biters systemer Service Pack 2</a>*<br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ea78a9b-b1f7-4e94-b69e-c984e1622ae9">Windows Server 2008 for x64-baserte systemer Service Pack 2</a>*<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1499d988-fd55-4317-b859-ec170907d547">Windows Server 2008 for x64-baserte systemer Service Pack 2</a>*<br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for Itanium-baserte systemer Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e2d2ea9-0af6-4d23-875d-3211722cd62f">Windows Server 2008 for Itanium-baserte systemer Service Pack 2</a>
                    <br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76b99ab2-7e99-4aad-a419-7996bae05c48">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f6d32de-d3ff-4af9-9b26-a4f12581f5fe">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225825">
                      <strong>MS11-070</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223632">
                      <strong>MS11-071</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58cf343-946c-4e74-bd9c-40ac934a4986">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8a451bd-3e5c-4845-9941-daabd9418776">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fdfb1f9-20b3-4d61-8019-33d1003290c8">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Viktig!)</td></tr>
              </table>


**Merknad for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene om [administrasjon av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [betjening av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office-serier og -programvare

<table style="border:1px solid black;" class="dataTable">
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office-serier og -komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dee4f3d7-bc4b-47fd-8e3f-9d2b0e82d0f6">Microsoft Excel 2003 Service Pack 3</a>
                    <br />(KB2553072)<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7faa2f90-2e64-4dbf-ac93-bb8cffc9b5fe">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB2584052)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2007 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=498ac241-d728-4944-abac-ec8444ca6418">Microsoft Excel 2007 Service Pack 2</a>
                    <br />(KB2553073)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df04b9ce-2daa-4b4d-a944-a873075656f9">Microsoft Office 2007 Service Pack 2</a><br />(KB2553089)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90eef02b-db1f-4fdd-bb1d-408063671e4d">Microsoft Office 2007 Service Pack 2</a><br />(KB2553090)[1]<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34bbee95-0e83-4705-8bfe-02e4fb22f8e7">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2584063)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-biters versjoner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4612c6e4-ac29-4cc4-9da5-88779ea3643e">Microsoft Excel 2010 og Microsoft Excel 2010 Service Pack 1 (32-biters versjoner)</a>
                    <br />(KB2553070)<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fd15144-5547-4927-8583-8d9b06819226">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-biters versjoner)</a><br />(KB2553091)<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18840d78-944f-400a-addc-dce7e570a569">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-biters versjoner)</a><br />(KB2553096)<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8fd04a-9df6-4726-a9bc-811f49665981">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (32-biters versjoner)</a>
                    <br />(KB2584066)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-biters versjoner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d40db27b-1318-4ca7-b44f-c90bb6342109">Microsoft Excel 2010 og Microsoft Excel 2010 Service Pack 1 (64-biters versjoner)</a>
                    <br />(KB2553070)<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f83800aa-6403-4341-afea-d363e54d5831">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-biters versjoner)</a><br />(KB2553091)<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92787e00-6f30-4020-9c1a-70270be5a623">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-biters versjoner)</a><br />(KB2553096)<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85360dc1-99e7-4e3e-be6f-3795e8a8122f">Microsoft Office 2010 og Microsoft Office 2010 Service Pack 1 (64-biters versjoner)</a>
                    <br />(KB2584066)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office for Mac</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2004 for Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=868f4d9f-3498-4d59-a017-59204553889c">Microsoft Office 2004 for Mac</a>
                    <br />(KB2598782)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2008 for Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa79cfc-6e8a-4d0b-88aa-0d7e05031e44">Microsoft Office 2008 for Mac</a>
                    <br />(KB2598781)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office for Mac 2011</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=535fcf4a-eeb2-44eb-b2a6-9c512509c49d">Microsoft Office for Mac 2011</a>
                    <br />(KB2598783)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Open XML File Format Converter for Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9796588d-238f-4694-9598-1aa8d2becb55">Open XML File Format Converter for Mac</a>
                    <br />(KB2598785)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office Groove og Microsoft SharePoint Workspace</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Groove 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ea6192b-55e5-4ca4-8d91-cc768ede8277">Microsoft Office Groove 2007 Service Pack 2</a>
                    <br />(KB2552997)<br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (32-biters versjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6ee7e43-9da9-4b96-abd0-390cfcacb885">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (32-biters versjoner)</a>
                    <br />(KB2566445)<br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (64-biters versjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=234efac1-4f09-41f5-90a9-4a3c2e81c05e">Microsoft SharePoint Workspace 2010 og Microsoft SharePoint Workspace 2010 Service Pack 1 (64-biters versjoner)</a>
                    <br />(KB2566445)<br />(Viktig!)</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Annen Microsoft Office-programvare</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225103">
                      <strong>MS11-073</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Excel Viewer Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f82ca5da-a55a-487c-8170-46a40000c8e3">Microsoft Excel Viewer Service Pack 2</a>
                    <br />(KB2553075)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01093f22-06b7-4c9b-bff9-f54ac5d73bf8">Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB2553074)<br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Merknader for MS11-072**

\[1\]For Microsoft Excel 2007 Service Pack 2 må kunder i tillegg til sikkerhetsoppdateringspakkene KB2553073, KB2553089 og KB2553090 også installere sikkerhetsoppdateringen for Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007 (KB2553074) for å være beskyttet mot sikkerhetsproblemene beskrevet i denne bulletinen.

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

**Merknad for MS11-074**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Microsoft Server-programvare

<table style="border:1px solid black;" class="dataTable">
                <tr><th colspan="3" style="border:1px solid black;">Microsoft SharePoint Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-biters versjoner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd532201-485c-4270-88d3-63bd3f24327e">Microsoft Excel Services</a>
                    <br />(KB2553093)[2]<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad52c341-13ce-4b53-87b4-269cb3f41275">Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (32-biters versjoner)</a>
                    <br />(KB2508964)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd6189c9-ab3b-441f-a901-6ac7f3b202aa">Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (32-biters versjoner)</a><br />(KB2553001)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9601fae-4a80-45cd-a49b-ef441856d7e4">Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (32-biters versjoner)</a><br />(KB2553002)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55b60e2f-ec68-4ccb-803a-5d03add8a1f1">Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (32-biters versjoner)</a><br />(KB2553003)[1]<br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-biters versjoner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1086a5b0-e441-4e26-a8d1-924a20121dde">Microsoft Excel Services</a>
                    <br />(KB2553093)[2]<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5e60751-242a-4fdb-9852-6d94050d3d0e">Microsoft Office SharePoint Server 2007 Service Pack 2 (coreserver) (64-biters versjoner)</a>
                    <br />(KB2508964)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1466366-e2ae-498e-b964-135e034e7348">Microsoft Office SharePoint Server 2007 Service Pack 2 (oserver) (64-biters versjoner)</a><br />(KB2553001)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb788c8d-8383-4e53-ac05-2a7dd9b83e70">Microsoft Office SharePoint Server 2007 Service Pack 2 (sserverx) (64-biters versjoner)</a><br />(KB2553002)[1]<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8e1a5bb-a552-45fe-8e81-e05fbfbb57ee">Microsoft Office SharePoint Server 2007 Service Pack 2 (dlc) (64-biters versjoner)</a>[1]<br />(Viktig!)<br />(KB2553003)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c150328-6a15-4852-a09c-4063142bd946">Microsoft Excel Services</a>
                    <br />(KB2553094)<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c17eb04d-cbbc-457e-a424-4ee26b7a9654">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (osrchwfe)</a>
                    <br />(KB2494022)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a80a849-b712-47d4-9def-9395ee54a265">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (osrv)</a><br />(KB2560885)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b84c2bcb-0327-4916-871e-7a5c19b8c41b">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe)</a><br />(KB2560890) <br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1597f295-02a9-4479-9d52-f18f0e83eaba">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmawfe)</a><br />(KB2566456)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6b666a4-a795-441c-9bda-23e2de2e7b05">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (dlc)</a><br />(KB2566954)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57592ce4-5d99-45c2-830f-380d67af8899">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (ppsmamui)</a><br />(KB2566958)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd64a635-1e55-4b4d-9718-9b94c31c5625">Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (wosrv)</a><br />(KB2566960)<br />(Viktig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office Forms Server</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet  </strong>
                    <strong>alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Forms Server 2007 Service Pack 2 (32-biters versjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4c8ad7e-50bd-460e-9678-d8c72c6ee7ab">Microsoft Office Forms Server 2007 Service Pack 2 (32-biters versjoner)</a>
                    <br />(KB2553005)<br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Forms Server 2007 Service Pack 2 (64-biters versjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7390b526-f411-45a4-8587-8077b473ac17">Microsoft Office Forms Server 2007 Service Pack 2 (64-biters versjoner)</a>
                    <br />(KB2553005)<br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Groove Server</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Groove Data Bridge Server 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5958247e-204e-409c-bdc1-7aff06e854b8">Microsoft Office Groove Data Bridge Server 2007 Service Pack 2</a>
                    <br />(KB2552999)<br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Groove Management Server 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b5b4caf-6a95-487d-ac17-c4435225af3a">Microsoft Office Groove Management Server 2007 Service Pack 2</a>
                    <br />(KB2552998)<br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Groove Server 2010 og Microsoft Groove Server 2010 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71c0f217-5112-4dca-b9aa-46c69f6099e4">Microsoft Groove Server 2010 og Microsoft Groove Server 2010 Service Pack 1</a>
                    <br />(KB2508965)<br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office Web Apps</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Web Apps 2010 og Microsoft Office Web Apps 2010 Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73d49094-a9cf-407e-8921-1b22fbc30427">Microsoft Excel Web App 2010 og Microsoft Excel Web App 2010 Service Pack 1</a>
                    <br />(KB2553095)<br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=288a7394-b8d5-4445-bd4c-65bbf4b10eaf">Microsoft Office Web Apps 2010 og Microsoft Office Web Apps 2010 Service Pack 1</a>
                    <br />(KB2566449)<br />(Viktig!)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=152ff9f4-d720-41af-8f89-793133ece037">Microsoft Word Web App 2010 og Microsoft Word Web App 2010 Service Pack 1</a><br />(KB2566450)<br />(Viktig!)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows SharePoint Services og Microsoft SharePoint Foundation</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=225047">
                      <strong>MS11-072</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=204797">
                      <strong>MS11-074</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Windows SharePoint Services 2.0</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71e32745-cb05-4b87-a447-741ccdac7450">Microsoft Windows SharePoint Services 2.0</a>
                    <br />(KB2494007)<br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-biters versjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f306cbd-a652-4e77-b394-1a6dc38ba83c">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-biters versjoner)</a>
                    <br />(KB2493987)<br />(Viktig!)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-biters versjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3137e4c6-783d-4461-88bd-90da064e3105">Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-biters versjoner)</a>
                    <br />(KB2493987)<br />(Viktig!)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft SharePoint Foundation 2010 og Microsoft SharePoint Foundation 2010 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0db799e2-896f-464b-8cd5-ecf2014f0588">Microsoft SharePoint Foundation 2010 og Microsoft SharePoint Foundation 2010 Service Pack 1</a>
                    <br />(KB2494001)<br />(Viktig!)</td></tr>
              </table>


**Merknader for MS11-072**

\[2\]Denne oppdateringen gjelder for servere som har Excel Services installert, for eksempel standardkonfigurasjonen til Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 for Internett-områder. Microsoft Office SharePoint Server 2007 Standard inkluderer ikke Excel Services.

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

**Merknader for MS11-074**

\[1\]For støttede versjoner av Microsoft Office SharePoint Server 2007 må kunder også installere sikkerhetsoppdateringen for Microsoft Windows SharePoint Services 3.0 (KB2508964, KB2553001, KB2553002 og KB2553003) i tillegg til sikkerhetsoppdateringspakkene for Microsoft Office SharePoint Server 2007 for å være beskyttet mot sikkerhetsproblemene som beskrives i denne bulletinen.

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

For kunder med Microsoft Office for Mac kan Microsoft AutoUpdate for Mac hjelpe med å holde Microsoft-programvaren oppdatert. Hvis du vil ha mer informasjon om bruk av Microsoft AutoUpdate for Mac, kan du se [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Veiledning for søking og distribusjon**

Microsoft tilbyr veiledning for søking etter og distribusjon av sikkerhetsoppdateringer. Denne veiledningen inneholder anbefalinger og informasjon som kan hjelpe IT-eksperter med å forstå hvordan ulike verktøy for søking etter og distribusjon av sikkerhetsoppdateringer skal brukes. Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Med Windows Server Update Services (WSUS) kan administratorer raskt og trygt distribuere de nyeste kritiske oppdateringene og sikkerhetsoppdateringene for Microsoft Windows 2000 og nyere operativsystemer, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse oppgaven med å levere og administrere oppdateringer til IT-systemer i hele bedriften. Med Configuration Manager 2007 kan IT-administratorer levere oppdateringer av Microsoft-produkter til en rekke enheter, inkludert stasjonære datamaskiner, bærbare datamaskiner, servere og mobile enheter.

Den automatiske sikkerhetsproblemvurderingen i Configuration Manager 2007 oppdager behov for oppdateringer og rapporterer om anbefalte handlinger. Software Update Management i Configuration Manager 2007 er bygd på Microsoft Windows Software Update Services (WSUS), en tidstestet oppdateringsinfrastruktur som er velkjent for IT-administratorer over hele verden. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke Configuration Manager 2007 til å distribuere oppdateringer, kan du se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Hvis du vil ha mer informasjon om Configuration Manager, kan du gå til [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne.

**Obs\!** System Management Server 2003 har ikke vanlig kundestøtte etter 12. januar 2010. Hvis du vil ha mer informasjon om produktlivssykluser, kan du gå til [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den neste utgivelsen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se det tidligere avsnittet **System Center Configuration Manager 2007**.

Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du se [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer for å gi bred støtte i forbindelse med søking etter og distribusjon av sikkerhetsbulletinoppdateringer. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validering av Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte oppdateringer på MU, WU og WSUS

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Innholdet i beskrivelsen av Software Update Services og Windows Server Update Services endres. Omfatter alt Windows-innhold.
  - [Oppdateringer de siste månedene for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Vis alle nye, reviderte og nyutgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For å forbedre sikkerheten for kundene gir Microsoft store leverandører av sikkerhetsprogramvare informasjon om sikkerhetsproblemer før hver månedlige utgivelse av sikkerhetsoppdateringer. Leverandører av sikkerhetsprogramvare kan deretter bruke denne informasjonen om sikkerhetsproblemer til å oppdatere beskyttelsen til kundene via sikkerhetsprogramvaren eller -enhetene deres, som antivirusprogrammer, nettverksbaserte systemer for oppdaging av inntrengere eller vertsbaserte systemer for forhindring av inntrengere. Hvis du vil finne ut om det finnes aktiv beskyttelse tilgjengelig fra leverandører av sikkerhetsprogramvare, kan du gå til webområdene for aktiv beskyttelse fra programpartnerne som er oppført i artikkelen om [MAPP-programpartnere (Microsoft Active Protections Program)](http://go.microsoft.com/fwlink/?linkid=215201).

#### Sikkerhetsstrategier og -sone

**Strategier for behandling av oppdateringer**

På webområdet [Security Guidance for Update Management](http://go.microsoft.com/fwlink/?linkid=21168) finner du mer informasjon om Microsofts anbefalinger for gode fremgangsmåter for å bruke sikkerhetsdata.

**Få tak i andre sikkerhetsoppdateringer**

Oppdateringer for andre sikkerhetsproblemer finnes på følgende steder:

  - Sikkerhetsoppdateringer finnes på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".
  - Oppdateringer for forbrukerplattformer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan få sikkerhetsoppdateringene som tilbys på Windows Update denne måneden, fra Download Center på Security and Critical Releases ISO CD Image-filer. Hvis du vil ha mer informasjon, kan du se [Microsoft Knowledge Base-artikkel 913086](http://support.microsoft.com/kb/913086).

**Sikkerhetsmiljø for IT-eksperter**

Lær hvordan du kan forbedre sikkerheten og optimalisere IT-infrastrukturen, og delta sammen med andre IT-eksperter i diskusjoner om sikkerhet i [sikkerhetssonen for IT-eksperter](http://go.microsoft.com/fwlink/?linkid=21164).

#### Takk til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for samarbeidet med å beskytte kundene:

  - Nicolas Economou hos [Core Security Technologies](http://www.coresecurity.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-070
  - En anonym forsker i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-072
  - Sean Larsson hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-072
  - En anonym forsker i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-072
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-072
  - Omair i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-072
  - Parvez Anwa i samarbeid med [Secunia Research](http://secunia.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-073
  - David Warren hos [CERT/CC](http://www.cert.org/) for rapporten om et sikkerhetsproblem som beskrives i MS11-073
  - Andrew Connell hos [Critical Path Training, LLC](http://www.criticalpathtraining.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-074
  - David Feldman hos [Raytheon](http://www.raytheon.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-074
  - Adi Cohen hos [IBM Rational Application Security](http://blog.watchfire.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-074
  - [Trend Micro](http://www.trendmicro.com/) for samarbeidet i forbindelse med et problem som beskrives i MS11-074
  - Pedro Jimenez hos [ITT](http://www.itt.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-074
  - [Seeker automatisk programsikkerhetstestløsning](http://www.seekersec.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-074
  - Nicolas Grégoire hos [Agarri](http://www.agarri.fr/) for rapporten om et sikkerhetsproblem som beskrives i MS11-074
  - Jim LaValley hos [LaValley Consulting, LLC](http://www.lavalley.net) for rapporten om et sikkerhetsproblem som beskrives i MS11-074
  - Irene Abezgauz hos [Seeker](http://www.seekersec.com) for samarbeidet om en oppdatering av dybdeforsvar i MS11-074

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (13. september 2011): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (13. september 2011): For MS11-074 er det lagt til oppdateringskobling for oppdateringen for Microsoft Office SharePoint Server 2010 og Microsoft Office SharePoint Server 2010 Service Pack 1 (pplwfe) (KB2560890).

*Built at 2014-04-18T01:50:00Z-07:00*

