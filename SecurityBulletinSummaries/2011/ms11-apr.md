---
title: Sammendrag av Microsofts sikkerhetsbulletiner for april 2011
TOCTitle: MS11-APR
ms:assetid: ms11-apr
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms11-apr(v=Security.10)
ms:contentKeyID: 61315224
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for april 2011

Publisert: 12. april 2011 | Oppdatert: 26. oktober 2011

**Versjon:** 6.1

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i april 2011.

I forbindelse med utgivelsen av bulletinene for april 2011 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 7. april 2011. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 13. april 2011 kl. 11.00 stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for april på webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032455069&eventcategory=4). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

## Kortfattede sammendrag

Følgende tabell viser et sammendrag av sikkerhetsbulletinene for denne måneden etter alvorlighetsgrad.

Hvis du vil ha informasjon om berørt programvare, kan du se den neste delen, **Berørt programvare og nedlastingssteder**.

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Bulletintittel og kortfattet sammendrag</th>
<th>Maksimal alvorlighetsgrad og følger av sikkerhetsproblemet</th>
<th>Krav om omstart</th>
<th>Berørt programvare</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (2497640</strong> <strong>)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fire personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem i Internet Explorer. Denne sikkerhetsoppdateringen har alvorlighetsgraden Kritisk for Internet Explorer 6, Internet Explorer 7 og Internet Explorer 8 på Windows-klienter. For Internet Explorer 6, Internet Explorer 7 og Internet Explorer 8 på Windows-servere har den alvorlighetsgraden Moderat. Internet Explorer 9 er ikke berørt av disse sikkerhetsproblemene.<br />
<br />
De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212314">MS11-019</a></td>
<td><strong>Sikkerhetsproblemer i SMB-klienten kan tillate ekstern kjøring av kode (2511455)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem og et personlig rapportert sikkerhetsproblem i Microsoft Windows. Det mest alvorlige av disse sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en angriper sender et spesiallaget SMB-svar på en SMB-forespørsel som startes fra en klient. En angriper må overbevise brukeren om å starte en SMB-tilkobling til en spesiallaget SMB-server for å kunne utnytte dette sikkerhetsproblemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212236">MS11-020</a></td>
<td><strong>Sikkerhetsproblem i SMB-serveren kan tillate ekstern kjøring av kode (2508429)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper oppretter en spesiallaget SMB-pakke og deretter sender pakken til et berørt system. Gode sikkerhetsrutiner for brannmurer og vanlige standard brannmurkonfigurasjoner kan beskytte nettverk mot angrep fra andre steder enn innenfor virksomheten som forsøker å utnytte disse sikkerhetsproblemene.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=214005">MS11-027</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering av</strong> <strong>kill bits for ActiveX (2508272)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem i Microsoft-programvare. Sikkerhetsproblemene kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside som starter en bestemt ActiveX-kontroll med Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Denne oppdateringen inneholder også kill bits for tre tredjeparts ActiveX-kontroller.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207931">MS11-028</a></td>
<td><strong>Sikkerhetsproblem i .NET Frame</strong> <strong>work kan tillate ekstern kjøring av kode (2484015)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem i Microsoft .NET Framework. Sikkerhetsproblemet kan tillate ekstern kjøring av kode på et klientsystem hvis en bruker viser en spesiallaget webside ved hjelp av en webleser som kan kjøre XAML-leserprogrammer (XBAPer). Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Sikkerhetsproblemet kan videre tillate ekstern kjøring av kode på et serversystem som kjører IIS, hvis den serveren tillater behandling av ASP.NET-sider og en angriper lykkes i å laste opp en spesiallaget ASP.NET-side til den serveren og deretter kjører siden, slik det kan være tilfelle i et webvertscenario. Dette sikkerhetsproblemet kan også brukes av Windows .NET-programmer til å omgå kodetilgangssikkerhetsrestriksjoner (CAS).</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208524">MS11-029</a></td>
<td><strong>Et sikkerhetsproblem i GDI+ kan tillate ekstern kjøring av kode (2489979)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft GDI+. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker viser en spesiallaget bildefil ved hjelp av den berørte programvaren eller går til et webområde som inneholder spesiallaget innhold. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows,<br />
Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212595">MS11-030</a></td>
<td><strong>Sikkerhetsproblem i DNS-oppløsning kan tillate ekstern kjøring av kode (2509553)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows DNS-oppløsning. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper får tilgang til nettverket og lager et tilpasset program for å sende spesiallagede LLMNR-kringkastingsspørringer til målsystemene. Gode fremgangsmåter for brannmurer og vanlige standard brannmurkonfigurasjoner kan beskytte nettverk mot angrep fra andre steder enn innenfor virksomheten. Gode fremgangsmåter anbefaler at systemer som er knyttet til Internett, bør eksponere så få porter som mulig. For å oppnå det bør LLMNR-porter blokkeres fra Internett.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212243">MS11-031</a></td>
<td><strong>Sikkerhetsproblem i skriptmotorene for JScript og VBScript</strong> <strong>kan tillate ekstern kjøring av kode (2514666)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i skriptmotorene for JScript og VBScript. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker besøker et spesiallaget webområde. En angriper kan ikke tvinge brukere til å besøke webområdet. I stedet må angriperen lokke brukere til å besøke webområdet, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212224">MS11-032</a></td>
<td><strong>Sikkerhetsproblem i driver for OpenType-skrifter i CFF-format kan føre til ekstern kjøring av kode (2507618)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i driveren for OpenType-skrifter i CFF-format. Sikkerhetsproblemet kan føre til ekstern kjøring av kode hvis en bruker viser innhold gjengitt i en spesiallaget CFF-skrift. Uansett kan ikke en angriper tvinge brukerne til å bruke det spesiallagde innholdet. I stedet må angriperen lokke brukere til å besøke et webområde, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (2489279)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ni personlig rapporterte sikkerhetsproblemer i Microsoft Office. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-fil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft PowerPoint kan tillate ekstern kjøring av kode (2489283)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser tre personlig rapporterte sikkerhetsproblemer i Microsoft PowerPoint. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget PowerPoint-fil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Den automatiserte løsningen <strong>Microsoft Fix it</strong> for PowerPoint 2010, &quot;Disable Edit in Protected View for PowerPoint 2010,&quot; tilgjengelig i<a href="http://support.microsoft.com/kb/2501584">Microsoft Knowledge Base-artikkel 2501584</a>, blokkerer angrepsvektorene for utnyttelse av sikkerhetsproblemene som beskrives i CVE-2011-0655 og CVE-2011-0656.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office,<br />
Microsoft Server-programvare</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210206">MS11-023</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Office kan tillate e</strong> <strong>kstern kjøring av kode (2489293)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem og et personlig rapportert sikkerhetsproblem i Microsoft Office. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Office-fil, eller hvis en bruker åpner en legitim Office-fil som ligger i samme nettverkskatalog som en spesiallaget biblioteksfil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212226">MS11-024</a></td>
<td><strong>Sikkerhetsproblemer i Redigering av faksforside for Windows kan tillate ekstern kjøring av kode (2527308)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to offentliggjorte sikkerhetsproblemer i Microsoft Windows. Sikkerhetsproblemene kan tillate ekstern kjøring av kode dersom en bruker åpner en spesiallaget faksforsidefil (.cov) med Redigering av faksforside for Windows. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=209720">MS11-025</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Foundation Class-bibliotek (MFC) kan tillate ekstern</strong> <strong>kjøring av kode (2500212)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i bestemte programmer som er bygd med Microsoft Foundation Class-biblioteket (MFC). Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker åpner en legitim fil som er tilknyttet et berørt program som ligger i samme nettverksmappe som en spesiallaget biblioteksfil. For at et angrep skal lykkes, må brukeren besøke en ikke-klarert ekstern filsystemplassering eller delt WebDAV-ressurs og åpne et dokument fra denne plasseringen som deretter blir lastet inn av et berørt program.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Utviklerverktøy og programvare fra Microsoft</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212523">MS11-026</a></td>
<td><strong>Sikkerhetsproblem i MHTML kan tillate tilgjengeliggjøring av informasjon (2503658)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i MHTML-protokollbehandleren i Microsoft Windows. Dette sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en bruker besøker en spesiallaget webside. I et webbasert angrepsscenario kan et webområde inneholde en spesiallaget kobling som brukes for å utnytte dette sikkerhetsproblemet. En angriper må overbevise brukere om å besøke webområdet og åpne den spesiallagede filen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tilgjengeliggjøring av informasjon</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208110">MS11-033</a></td>
<td><strong>Sikkerhetsproblem i tekstkonverteringsprogrammer for WordPad kan tillate ekstern kjøring av kode (2485663)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Denne sikkerhetsoppdateringen har alvorlighetsgraden Viktig for alle støttede versjoner av Windows XP og Windows Server 2003. Ingen støttede versjoner av Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er berørt av sikkerhetsproblemet.<br />
<br />
Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget fil ved hjelp av WordPad. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td><strong>Sikkerhetsproblemer i Windows-kjernemodusdrivere kan tillate rettighetsutvidelse (2506223)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser tretti personlig rapporterte sikkerhetsproblemer i Microsoft Windows. Disse sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en angriper logger seg på lokalt og kjører et spesiallaget program. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte disse sikkerhetsproblemene. Sikkerhetsproblemene kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført i synkende rekkefølge etter utnyttelsesvurderingsnivå og deretter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan** **bruker jeg denne tabellen?**

Bruk denne tabellen til å få mer informasjon om sannsynligheten for at fungerende skadelig kode blir utgitt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Du bør se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Tittel på sikkerhetsproblem</th>
<th>CVE-ID</th>
<th>Utnyttelsesindeksvurdering</th>
<th>Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=209720">MS11-025</a></td>
<td>Sikkerhetsproblem med usikker bibliotekinnlasting i MFC</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3190">CVE-2010-3190</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207931">MS11-028</a></td>
<td>Sikkerhetsproblem med stakkfeil i .NET Framework</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3958">CVE-2010-3958</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212224">MS11-032</a></td>
<td>Sikkerhetsproblem med stakkoverflyt i OpenType-skrift</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0034">CVE-2011-0034</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208524">MS11-029</a></td>
<td>Sikkerhetsproblem med heltallsoverflyt i GDI+</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0041">CVE-2011-0041</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td>Sikkerhetsproblem ved oppsetthåndtering som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0094">CVE-2011-0094</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes</strong> <strong>i begrensede, målrettede angrep</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem med heltallsoverflyt i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0097">CVE-2011-0097</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem med heap-overflyt i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0098">CVE-2011-0098</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem med WriteAV ved analyse av Excel-poster</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0101">CVE-2011-0101</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210206">MS11-023</a></td>
<td>Sikkerhetsproblem med usikker bibliotekinnlasting i Office-komponent</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0107">CVE-2011-0107</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td>Sikkerhetsproblem i MSHTML som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0346">CVE-2011-0346</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212314">MS11-019</a></td>
<td>Sikkerhetsproblem med analysering av svar i SMB-klienten</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0660">CVE-2011-0660</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212236">MS11-020</a></td>
<td>Sikkerhetsproblem med SMB-transaksjonsanalyse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0661">CVE-2011-0661</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0662">CVE-2011-0662</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0665">CVE-2011-0665</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0666">CVE-2011-0666</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0667">CVE-2011-0667</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0670">CVE-2011-0670</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0671">CVE-2011-0671</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0672">CVE-2011-0672</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0673">CVE-2011-0673</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0674">CVE-2011-0674</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0675">CVE-2011-0675</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0676">CVE-2011-0676</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0677">CVE-2011-0677</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td>Sikkerhetsproblem med OfficeArt Atom RCE</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0976">CVE-2011-0976</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem med datatabellindeksering i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0978">CVE-2011-0978</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem i Excel med feil ved koblet liste</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0979">CVE-2011-0979</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem med peker uten mål i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0980">CVE-2011-0980</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1225">CVE-2011-1225</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1226">CVE-2011-1226</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1227">CVE-2011-1227</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1228">CVE-2011-1228</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1229">CVE-2011-1229</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1230">CVE-2011-1230</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1231">CVE-2011-1231</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1232">CVE-2011-1232</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>Sikkerhetsproblem med nullpeker uten referanse i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1233">CVE-2011-1233</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1235">CVE-2011-1235</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1236">CVE-2011-1236</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1237">CVE-2011-1237</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1239">CVE-2011-1239</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1240">CVE-2011-1240</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1241">CVE-2011-1241</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1242">CVE-2011-1242</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td>Sikkerhetsproblem med objektstyring som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1345">CVE-2011-1345</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes i begrensede,</strong> <strong>målrettede angrep</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208110">MS11-033</a></td>
<td>Sikkerhetsproblem med analyse i WordPad-konvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0028">CVE-2011-0028</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem i Excel som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0103">CVE-2011-0103</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem med bufferoverskriving i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0104">CVE-2011-0104</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210121">MS11-021</a></td>
<td>Sikkerhetsproblem med initialisering av data i Excel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0105">CVE-2011-0105</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212314">MS11-019</a></td>
<td>Sikkerhetsproblem med feil i nettleserutvalget</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0654">CVE-2011-0654</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td>Sikkerhetsproblem med flytende punktteknologifarge i Time Bandit RCE</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0655">CVE-2011-0655</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210727">MS11-022</a></td>
<td>Sikkerhetsproblem i Persist Directory RCE</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0656">CVE-2011-0656</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212595">MS11-030</a></td>
<td>Sikkerhetsproblem med spørring i DNS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0657">CVE-2011-0657</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212243">MS11-031</a></td>
<td>Sikkerhetsproblem med omallokering av skriptminne</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0663">CVE-2011-0663</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=210206">MS11-023</a></td>
<td>Sikkerhetsproblem med Microsoft Office-grafikkobjekt uten referanse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0977">CVE-2011-0977</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1234">CVE-2011-1234</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212226">MS11-024</a></td>
<td>Sikkerhetsproblem i Redigering av faksforside for Windows kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3974">CVE-2010-3974</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212226">MS11-024</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem for faksforside</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4701">CVE-2010-4701</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=212523">MS11-026</a></td>
<td>Sikkerhetsproblem med MHTML Mime-formatert forespørsel</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0096">CVE-2011-0096</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette sikkerhetsproblemet er publisert.<br />
<br />
Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=211826">MS11-034</a></td>
<td>&quot;Use after free&quot;-sikkerhetsproblem med Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1238">CVE-2011-1238</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=214126">MS11-018</a></td>
<td>Sikkerhetsproblem med Javascript som kan føre til tilgjengeliggjøring av informasjon</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1245">CVE-2011-1245</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

Følgende tabeller viser bulletinene etter store programvarekategorier og alvorlighetsgrad.

**Hvordan bruker jeg disse tabellene?**

Bruk disse tabellene til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det kommer noen sikkerhetsoppdateringer som angår installasjonen din. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for ett enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="14">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214126">
                      <strong>MS11-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212314">
                      <strong>MS11-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212236">
                      <strong>MS11-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214005">
                      <strong>MS11-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=207931">
                      <strong>MS11-028</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212595">
                      <strong>MS11-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212243">
                      <strong>MS11-031</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212224">
                      <strong>MS11-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212226">
                      <strong>MS11-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212523">
                      <strong>MS11-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208110">
                      <strong>MS11-</strong>
                      <strong>033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=211826">
                      <strong>MS11-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3a8cec0-f947-4d4e-a6ae-c7f4f1f311b0">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b7d0403-8965-4c62-970c-20b561f66713">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=689c5496-56c4-48a6-9f3d-b5f5aaf3e566">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5378e7b-4619-4c42-9d9f-87b209c6d878">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccb08a8a-f4d9-4320-8ffb-3fd4fe217987">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b031a496-aa74-4367-b2ae-24843c061745">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>
                    <br />(KB2446704)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59266a9d-a319-4309-a046-7f15c6da0136">Windows XP Service Pack 3</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2d433adb-bcaf-4c59-9405-a4892f8ccba3">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=637f4d4c-de07-4c6a-95f8-3bd0cbfe77b2">JScript 5.7 og VBScript 5.7</a>
                    <br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fbe1e7e3-1d5f-4daf-a4a5-67fe79292963">JScript 5.8 og VBScript 5.8</a><br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9080c5a1-e638-4047-a70a-9367f1acced7">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50fc3869-f2fc-43c8-8049-aad62f2cb332">Windows XP Service Pack 3</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8220a21-02fc-4ad6-988d-844276b2fd66">Windows XP Service Pack 3</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f0a4616-8e3e-4925-9d95-ce6e614e45ae">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6753ca98-feb4-4c7f-9969-9294038a2bbb">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39e55bbf-c1c5-4696-bfe7-632e997cd98e">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=986f07ae-0fdc-4be2-8a74-5eb56d4300ef">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed88f183-dd06-46f6-ae8a-a594a752f248">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d3433ee-c2e1-433f-a3d9-c049d66e2190">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c01441da-8933-4f60-923b-d9b00db8ba3d">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ee202da-a711-42ee-bea3-7202a70e4ea0">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eddd2964-9765-461d-9df8-2c05402948e8">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>
                    <br />(KB2446704)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3797009a-b9a4-4e83-8614-e1589c8b5090">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29ff546e-a232-4f23-a223-c029c71ff1c6">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a5586246-2908-4def-9298-c16060098197">JScript 5.6 og VBScript 5.6</a>
                    <br />(KB2510587)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a5f65e0-bb00-4e55-b8b5-77751349a3ec">JScript 5.7 og VBScript 5.7</a><br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57aa7ee2-254d-40b5-9ff0-cba969daf45a">JScript 5.8 og VBScript 5.8</a><br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2374e09a-cb3e-4bc3-bb4b-53b611025121">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b93311b4-1b8f-478d-8833-750c5e01e6f8">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f60fc99-cd88-4237-8b31-a4e618502f7e">Windows XP Professional x64 Edition Service Pack 2</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b01fe9a5-66a4-4683-963b-e78aea214579">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c94bc96-99ea-44a1-9052-e69de5e21f81">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83771177-284e-4918-86a9-980e8229c7c9">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="14">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214126">
                      <strong>MS11-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212314">
                      <strong>MS11-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212236">
                      <strong>MS11-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214005">
                      <strong>MS11-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=207931">
                      <strong>MS11-028</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212595">
                      <strong>MS11-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212243">
                      <strong>MS11-</strong>
                      <strong>031</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212224">
                      <strong>MS11-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212226">
                      <strong>MS11-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212523">
                      <strong>MS11-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208110">
                      <strong>MS11-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=211826">
                      <strong>MS11-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b902c58a-9e2f-4352-8d2f-fffda5344598">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c464287-3dab-4342-a38d-a12719d3b158">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45feb35b-b24e-4160-adb0-d0b7ae530e90">Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d46fe0bf-28c2-4696-87bc-dd3c8287fc28">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=64c550d4-c927-4382-91e1-473ed6790819">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53756404-39e4-43af-81e9-81471536aa66">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>
                    <br />(KB2446704)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd284233-e177-4064-9b02-f83dcb727dbe">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=753ed6e3-df2e-4b2d-9e9f-7275cd94d214">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e026f2ed-8a20-4268-9b29-04a78bde1999">JScript 5.6 og VBScript 5.6</a>
                    <br />(KB2510587)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b0ed0b2-07f9-43da-bb5d-5be5a45969ee">JScript 5.7 og VBScript 5.7</a><br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01aa2beb-9fc1-40f0-a2a4-bcd3d9cb31f8">JScript 5.8 og VBScript 5.8</a><br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d71d3f5-fd6b-4f3b-8389-37c899748d4b">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edda8cce-b764-4ef1-afbe-391fbd087362">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf084b4c-aac9-4cc6-bb30-87fc96ba9430">Windows Server 2003 Service Pack 2</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0209a004-f23a-40d9-991f-864046f4605f">Windows Server 2003 Service Pack 2</a>
                    <br />(Lav)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9fbfc742-6c74-49a2-b3cc-e1d5d8c84b77">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=af320f27-bb3a-4e76-a279-4632267c8761">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d8f14d1-85cc-478f-8b50-5c355a331f59">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d8bbea9-c456-4569-ad96-c2cd0f5fae7e">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=979d2ec5-5114-4ec7-aa97-e9289c590cbb">Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca0fb4d3-7651-4760-83fa-b71c86cbe459">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef62db94-4f72-4245-ac9f-6391035e2516">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8d59f49-45ec-4527-b3a8-4925f710bbfd">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>
                    <br />(KB2446704)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5adaf4e-4cd7-42ea-8202-31b5c856f5e3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0192dbc-4d0d-4555-9ef7-3e10209a6389">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83ce6c99-a57d-4ed1-972b-a6b6798e6675">JScript 5.6 og VBScript 5.6</a>
                    <br />(KB2510587)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=af791715-77a1-405b-a69e-d63f75dd7ccd">JScript 5.7 og VBScript 5.7</a><br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf0a2966-25c4-4717-bcd6-016ce610d220">JScript 5.8 og VBScript 5.8</a><br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a498ff0-21d9-493a-b127-6bc20f1baf95">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f04d939a-da11-4a9f-9e03-b6c3bf3ca58b">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12b01f3a-ccf8-41c1-ac5a-e417a6ddbe95">Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c287571-54ea-4298-8b7d-b98b2c830cc3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Lav)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=897b97b0-1bab-4b1b-b417-950fab0d4a65">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c95f81c-9812-4070-88d7-34422c638e42">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td>Windows Server 2003 SP2 for Itanium-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8afe86fc-58b4-4a95-b047-c09138fa4f5e">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1abfb48-3c8a-4b2d-b739-cc61628b387d">Internet Explorer 7</a><br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87eb8b93-9829-45ec-9528-52787732044e">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79aeb3cd-7c73-467b-b91e-02c6ea01e911">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c784734-f44f-4a3c-8223-6289f7dc2ad8">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Ingen alvorlighetsgrad[1])</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce925e76-cb85-48f6-8c0f-e53fa2b09be6">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>
                    <br />(KB2446704)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72a513bb-f901-4992-8562-d1afe1afec8a">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5ad6963-2d6a-4d59-9e25-4fc088647fcd">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7d36bae-7ca4-4a40-9efb-13f484fa5518">JScript 5.6 og VBScript 5.6</a>
                    <br />(KB2510587)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f519013-ed14-41a8-aa45-cf8b095d3152">JScript 5.7 og VBScript 5.7</a><br />(KB2510581)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c71f4398-2e3b-4b81-a650-8806e618db7f">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efb575c7-3259-49b1-b59c-89d9544e37a6">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03a7ee49-7bd6-4215-9779-1b48c10d08b9">Windows Server 2003 SP2 for Itanium-baserte systemer</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3fb450a0-d087-4f36-9301-05ffbf94cc1a">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Lav)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ede38974-4e57-4ea1-8731-b91e96534693">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58cf64a-bf31-4496-be75-5775a123338b">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="14">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214126">
                      <strong>MS11-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212314">
                      <strong>MS11-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212236">
                      <strong>MS11-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214005">
                      <strong>MS11-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=207931">
                      <strong>MS11-028</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212595">
                      <strong>MS11-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212243">
                      <strong>MS11-031</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212224">
                      <strong>MS11-</strong>
                      <strong>032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212226">
                      <strong>MS11-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212523">
                      <strong>MS11-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208110">
                      <strong>MS11-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=211826">
                      <strong>MS11-034</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Vik</strong>
                      <strong>tig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00c3c176-feff-4022-ac4c-2d4732ca3d78">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ea94705-4f76-4b0d-bbbc-afb5e75204bf">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da8dd55d-6630-484e-836c-9feeab5cc311">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6eddff4-a242-4dec-9d84-72891db2b754">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80bf050a-9aff-4cd4-8e2f-196b0a92b1c0">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>Bare Windows Vista Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2449741)<br />(Kritisk)<br /><br />Bare Windows Vista Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2449742)<br />(Kritisk)<br /><br />Windows Vista Service Pack 1 og Windows Vista Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ff2e440-79c2-4045-b225-913d1740fdb9">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a17e44f-54aa-423d-b3c7-a4f404f7c28b">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719e2c86-30e5-4cd5-94f4-d6de54efee5f">JScript 5.7 og VBScript 5.7</a>
                    <br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21decb84-75ef-4bde-a802-1e661a505e94">JScript 5.8 og VBScript 5.8</a>[1]<br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7c4fc81-d1ef-4378-862b-e955d75fb2de">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11a8f240-51b3-4e31-a24a-a235179f3396">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6cba040-9d7c-4777-a2f7-e4dd11dfb845">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8fce0fb-4c90-479b-8ce9-75e60d52d256">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4743167-9614-445a-9e91-10efdac505a8">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79f52733-44e4-47b6-86ca-1395a095b4e7">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc63b233-9db0-4fb1-a61c-fa7e9e44ba10">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=040f8b46-f458-4a72-a1b0-ad8a65a1194c">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2878c587-6544-40b4-9288-fc3b3ce1128d">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a81412d0-2516-4bf4-87f7-3e41ebf6b82b">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>Bare Windows Vista x64 Edition Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2449741)<br />(Kritisk)<br /><br />Bare Windows Vista x64 Edition Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2449742)<br />(Kritisk)<br /><br />Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d826026-e62a-4cec-8682-49fbe7f65cd6">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e708d24f-e348-4c4d-99ed-e78dd1689d01">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89b9d01e-bcbc-4f2c-973b-51051494f406">JScript 5.7 og VBScript 5.7</a>
                    <br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4ac199e-7bf8-4661-a4e5-c53719b2673a">JScript 5.8 og VBScript 5.8</a>[1]<br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8d654a78-0e4f-452c-8874-fbf478813857">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=61db662e-88d7-4454-b4b7-e987728fb137">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c942282-0f80-46c1-aeef-1ef948e105a3">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7da10b64-d0a9-4e42-aa3a-87c657122a8c">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e410d5c-b9f7-4a63-8300-36b2d57c6128">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="14">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214126">
                      <strong>MS11-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212314">
                      <strong>MS11-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212236">
                      <strong>MS11-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214005">
                      <strong>MS11-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=207931">
                      <strong>MS11-028</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212595">
                      <strong>MS11-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212243">
                      <strong>MS11-031</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212224">
                      <strong>MS11-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212226">
                      <strong>MS11-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212523">
                      <strong>MS11-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208110">
                      <strong>MS11-</strong>
                      <strong>033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=211826">
                      <strong>MS11-034</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d8603b8-bb52-4cf6-be8b-bb3475d30fc5">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5d76e90-1cef-47e8-9d8d-2c5a43f42ba3">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8c9390a-5ca1-492a-9e35-a516de48deb5">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31c48ba9-7774-4633-862d-5c27c3703584">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3247886-76d0-4292-be9d-3e9b0221c46a">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Moderat)</td><td>Bare Windows Server 2008 for 32-biters systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2449741)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for 32-biters systemer med Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2449742)<br />(Kritisk)<br /><br />Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fbada866-7d36-4b85-acde-fd856a998737">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>***<br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9894be38-a582-4c15-ad0e-cc3afab2aebc">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8b33ffd-eff1-4a10-b6fc-3c8f01e0fec5">JScript 5.7 og VBScript 5.7</a>**<br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afd128ff-717f-4d98-b214-f2c28d59623d">JScript 5.8 og VBScript 5.8</a>**[1]<br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9105377e-83c7-4010-8fd6-26e42e98c2cc">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90f56368-776b-4d45-ad68-91afbd316d25">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>** <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa972742-1166-4a9e-ab64-6a4f968f9c6d">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>* <br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=036f1285-7484-4e3b-8799-2c6c08166596">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Lav)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c6ac26b8-8cc8-40fe-baab-22bf13df1aa8">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td></tr>
                <tr><td>Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c6d58f64-bdd5-4fe6-96f4-9641b8e7b570">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51203a31-368b-4b47-96a5-9e9e5a55cd76">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0cfd5e0-6de5-4863-b5e4-b223a0e36d72">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de843115-cf98-4511-aa93-f620e4572555">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51521b6b-94a7-4bcf-ad5f-fc304728b10f">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Moderat)</td><td>Bare Windows Server 2008 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2449741)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for x64-baserte systemer med Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2449742)<br />(Kritisk)<br /><br />Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f4ddfcb-374d-4cad-8c61-2b988b46f628">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>***<br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2d7d2021-020f-4cc9-a027-258d7e5faec9">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c2e6b87-afcd-461a-8a43-9a2fb277b18a">JScript 5.7 og VBScript 5.7</a>**<br />(KB2510581)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40e8beca-0b5a-43b0-98f8-b32a82ad65d6">JScript 5.8 og VBScript 5.8</a>**[1]<br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=060e8b20-edca-4427-9d60-eb57261eb668">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22a001fc-5c2e-4539-85c9-0c2054a1777d">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>** <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc250c8a-ebaf-4264-9393-dc23cc372d9f">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>* <br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1438cec8-8dab-4510-ad75-dc6959dac0d8">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Lav)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac49f5d3-5e2f-4916-99be-a3254278da7e">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6f6f22c-fc7f-4e96-b6b5-be3c1acecf6e">Internet Explorer 7</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8eaf51cd-2f6e-4bbc-bc4f-9deed03649ac">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b89b8e28-cd98-4bcc-8729-5e51d52d1e92">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7c38b0d-7240-420a-88d3-2749a40e386f">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Ingen alvorlighetsgrad[1])</td><td>Bare Windows Server 2008 for Itanium-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94b6a1b3-e048-437b-a224-2a64b3735bc3">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2449741)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for Itanium-based Systems Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1407aaec-b3e0-404c-b84f-0c8e808614c4">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2449742)<br />(Kritisk)<br /><br />Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fd71543-0e18-4907-89b9-355d24d7db69">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(KB2412687)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c0275df0-10ac-4500-ab86-b7e9a34f8e1d">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afb49d24-1913-4e5f-a3ea-c6c9642e2017">JScript 5.7 og VBScript 5.7</a>
                    <br />(KB2510581)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b8571cb-2dae-4bff-9f13-feb89840044c">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=421024f1-aa86-459e-b6de-53851a3fcba2">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f35ecdd1-6b5c-40e7-a00b-ca083bdf5cba">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Lav)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b93de4f-01f4-4efd-afc1-31d87b92fad2">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="14">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214126">
                      <strong>MS11-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212314">
                      <strong>MS11-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212236">
                      <strong>MS11-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214005">
                      <strong>MS11-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=207931">
                      <strong>MS11-028</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212595">
                      <strong>MS11-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212243">
                      <strong>MS11-031</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212224">
                      <strong>MS11-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212226">
                      <strong>MS11-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212523">
                      <strong>MS11-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208110">
                      <strong>MS11-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=211826">
                      <strong>MS11-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritis</strong>
                      <strong>k</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59676b71-8b9d-4230-a9e0-b20db3e3ec7e">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0dcba089-19f7-46ca-9e52-24eaebad4715">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3ef905b-3584-4842-9ec2-cf3856305d49">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46510959-e4a2-4c21-b33c-fd3d97b3ac3d">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>Bare Windows 7 for 32-biters systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa">Microsoft .NET Framework 3.5.1</a><br />(KB2446709)<br />(Kritisk)<br /><br />Windows 7 for 32-biters systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a">Microsoft .NET Framework 3.5.1</a><br />(KB2446710)<br />(Kritisk)<br /><br />Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fdae09b-d1bb-4ef5-aa45-2a05f2a5e12d">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17ebf291-fdae-4e78-9377-871b3103ce16">JScript 5.8 og VBScript 5.8</a>
                    [1]
                    <br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=751c45ea-0943-4948-807f-8716c6ff9198">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf762b86-b949-4e84-8ca4-93ebe669c1b8">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f5a122e-dd5e-4b08-881a-f13b38642720">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aed201c1-f1fb-4df9-8875-6f57ea0eb15b">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e7ff003-ff3f-49bb-8e45-d869885dd8d7">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a998678-2678-489e-8711-39322663147d">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7fd356a-56d0-4638-8901-40acfa600f25">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ddc943b-6868-4e8f-a869-89b47133c287">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=432555cf-aed8-4329-a74f-526441521082">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>Bare Windows 7 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa">Microsoft .NET Framework 3.5.1</a><br />(KB2446709)<br />(Kritisk)<br /><br />Windows 7 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a">Microsoft .NET Framework 3.5.1</a><br />(KB2446710)<br />(Kritisk)<br /><br />Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40879dfb-efa4-41ba-8d5c-22e926a55eef">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c95ad86d-da58-4d7a-9ffd-8441f92baaa5">JScript 5.8 og VBScript 5.8</a>
                    [1]
                    <br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=976c882a-bc07-4128-927f-82a2df46cf45">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6793ecf-a3f6-4989-8e4c-c5c0005f9ac4">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=658301f1-103a-48a2-9b67-61cf8e1dad50">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a><br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a32bf04-7eed-4d27-a8e4-054b4a5b76cb">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c0aef7e-501c-4ca3-ae7f-497a8c169121">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="14">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214126">
                      <strong>MS11-018</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212314">
                      <strong>MS11-019</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212236">
                      <strong>MS11-020</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=214005">
                      <strong>MS11-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=207931">
                      <strong>MS11-028</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212595">
                      <strong>MS11-030</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212243">
                      <strong>MS11-031</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212224">
                      <strong>MS11-032</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212226">
                      <strong>MS11-</strong>
                      <strong>024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212523">
                      <strong>MS11-026</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208110">
                      <strong>MS11-033</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=211826">
                      <strong>MS11-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritis</strong>
                      <strong>k</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7b2482b-44bf-4c01-99d8-f93868659a24">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27a3847b-695b-4f60-aea5-86b0dbe68945">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4352802-9c5a-4c07-8303-3a4b78d3f954">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e4fa8ed0-acb0-4864-be18-29a27f8501de">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>**<br />(Moderat)</td><td>Bare Windows Server 2008 R2 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa">Microsoft .NET Framework 3.5.1</a>*<br />(KB2446709)<br />(Kritisk)<br /><br />Bare Windows Server 2008 R2 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a">Microsoft .NET Framework 3.5.1</a>*<br />(KB2446710)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>*[1]<br />(KB2446708)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2084c726-187e-41f9-9bea-da18f490d29e">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aecc2c7a-285c-409d-be23-c5b4b5449496">JScript 5.8 og VBScript 5.8</a>**[1]<br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f2a52cc-4833-448d-becc-2eac1a447410">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=465c0478-6a74-4b00-8608-938cc492549f">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>** <br />(KB2491683)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c5c3a0f-0672-49d0-bcbd-c7f40e11d092">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>* <br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=665faa7e-2368-4421-9dd5-ea6df2c79498">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>**<br />(Lav)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2fc66224-45c6-4e8f-ad00-6a1ec30b4505">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=af6db318-fbec-4286-a3a7-4081620146e5">Internet Explorer 8</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e7d3f21-bdbd-4826-855d-85422aa5f836">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0005377b-443f-44ca-a890-620b2dcea6f1">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7bcf4d7-b697-4c5f-adbc-a2b3700e0ad5">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Windows Server 2008 R2 bare for Itanium-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=157aa425-953c-4fc9-ab76-4e65d4be8baa">Microsoft .NET Framework 3.5.1</a><br />(KB2446709)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f87b8aa-1a2a-405e-aee0-9247d553756a">Microsoft .NET Framework 3.5.1</a><br />(KB2446710)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91aa6772-4811-4a58-9bc0-8aa271ed99df">Microsoft .NET Framework 4.0</a>[1]<br />(KB2446708)<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d2793e-a2cd-49f6-b524-6598ea86175f">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1bc0ed8-5a93-4d01-b407-919dfd894b5f">JScript 5.8 og VBScript 5.8</a>
                    [1]
                    <br />(KB2510531)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c6ca0b7c-8151-4d54-aa9b-5ec2b75d8ab6">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a993f8c-d28a-4a95-a3c6-059f06e75461">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(KB2506212)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=140ea384-2877-401f-ac3b-f84f6966e970">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Lav)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=485ccf96-27a0-499e-9f52-2836b73d26d2">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Server Core-installasjonen er ikke berørt.** Sikkerhetsproblemet som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core, selv om filer som er berørt av dette sikkerhetsproblemet, kan være til stede i systemet. Brukere blir imidlertid fortsatt tilbudt denne oppdateringen fordi oppdateringsfilene er nyere (med høyere versjonsnumre) enn filene som finnes på systemet. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS11-027**

\[1\]Dette bestemte operativsystemet er ikke berørt av sikkerhetsproblemene som er beskrevet i denne bulletinen. Den tilgjengelige oppdateringen angir kill bits for tredjepartskontroller.

**Merknad for MS11-028**

\[1\] **.NET Framework 4.0 og .NET Framework 4.0 Client Profile er berørt.** Omdistribuerbare pakker for .NET Framework versjon 4 er tilgjengelig i to profiler: .NET Framework 4.0 og .NET Framework 4.0 Client Profile. .NET Framework 4.0 Client Profile er en del av .NET Framework 4.0. Sikkerhetsproblemet som løses i denne oppdateringen, berører både .NET Framework 4.0 og .NET Framework 4.0 Client Profile. Hvis du vil ha mer informasjon, kan du se artikkelen om å [installere .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

**Merknad for MS11-029**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

**Merknad for MS11-031**

\[1\]Systemer med Internet Explorer 9 installert er ikke berørt av sikkerhetsproblemene som er beskrevet i denne bulletinen. Systemer som ikke er oppgraderte til Internet Explorer 9, trenger de riktige oppdateringene for de versjonene av JScript og VBScript som er installert. Se bulletinen for instrukser om hvordan du finner ut hvilken versjon av JScript og VBScript som er installert på systemet.

**Merknad for MS11-024**

Hvis det er to tilgjengelige oppdateringer for samme operativsystem, må du installere begge oppdateringene.

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="5">Microsoft Office-serier og -komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210121">
                      <strong>MS11-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210727">
                      <strong>MS11-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210206">
                      <strong>MS11-023</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet  </strong>
                    <strong>alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d">Microsoft Office XP Service Pack 3</a>
                    <br />(KB2509461)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db2c5cfe-588c-4646-b86a-3fb8248f7af4">Microsoft Excel 2002 Service Pack 3</a>
                    <br />(KB2466169)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d215ab6-c9be-4f43-9501-658bb7ef008e">Microsoft PowerPoint 2002 Service Pack 3</a>
                    <br />(KB2464617)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c87c2a9-3705-4680-8a9b-63b6ec83674d">Microsoft Office XP Service Pack 3</a>
                    <br />(KB2509461)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 3</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=916a076d-d754-4092-b23d-c8826db7e397">Microsoft Excel 2003 Service Pack 3</a>
                    <br />(KB2502786)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ce8349f-79b1-41ef-a1c0-cbe40ccf9f20">Microsoft PowerPoint 2003 Service Pack 3</a>
                    <br />(KB2464588)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b68cf68-1606-4649-b860-a64702c6cf33">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB2509503)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ae34fe0-03bd-48a9-a7ac-de8f7b1aff90">Microsoft Excel 2007 Service Pack 2</a>
                    [1]
                    <br />(KB2464583)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b2526fe-a061-4a17-992e-ac867bef130e">Microsoft PowerPoint 2007 Service Pack 2</a>
                    <br />(KB2464594)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbba0cd4-ab72-4e2b-9524-fd6be27f0b02">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2509488)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (32-biters versjoner)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a427f0e2-b74d-4ef3-bec4-0a101d09bfa3">Microsoft Excel 2010 (32-biters versjoner)</a>
                    <br />(KB2466146)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=549ca7f0-44bf-4965-a9d2-aa5e8dac2238">Microsoft PowerPoint 2010 (32-biters versjoner)</a>
                    <br />(KB2519975)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office 2010 (64-biters versjoner)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13dca35d-2209-4c5c-9150-d6db2bb3b496">Microsoft Excel 2010 (64-biters versjoner)</a>
                    <br />(KB2466146)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef62deae-2b07-41c9-a4bf-b746566e59ee">Microsoft PowerPoint 2010 (64-biters versjoner)</a>
                    <br />(KB2519975)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="5">Microsoft Office for Mac</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210121">
                      <strong>MS11-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210727">
                      <strong>MS11-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210206">
                      <strong>MS11-023</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5">Microsoft Office 2004 for Mac</a>
                    <br />(KB2505924)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5">Microsoft Office 2004 for Mac</a>
                    <br />(KB2505924)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f756d836-6ab2-4adb-9dee-6cb523d7c1f5">Microsoft Office 2004 for Mac</a>
                    <br />(KB2505924)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office 2008 for Mac</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918">Microsoft Office 2008 for Mac</a>
                    <br />(KB2505927)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918">Microsoft Office 2008 for Mac</a>
                    <br />(KB2505927)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84dfe3f4-a2a1-47b9-8da1-29ae67230918">Microsoft Office 2008 for Mac</a>
                    <br />(KB2505927)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office for Mac 2011</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3">Microsoft Office for Mac 2011</a>
                    <br />(KB2525412)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef1e612f-d8e3-4628-9fe4-ad136f0debd3">Microsoft Office for Mac 2011</a>
                    <br />(KB2525412)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Open XML File Format Converter for Mac</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14">Open XML File Format Converter for Mac</a>
                    <br />(KB2505935)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14">Open XML File Format Converter for Mac</a>
                    <br />(KB2505935)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c323a12-6385-4666-ad39-a9516a8eda14">Open XML File Format Converter for Mac</a>
                    <br />(KB2505935)<br />(Viktig)</td></tr>
              
                <tr><th colspan="5">Annen Office-programvare</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=208524">
                      <strong>MS11-029</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210121">
                      <strong>MS11-021</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210727">
                      <strong>MS11-022</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210206">
                      <strong>MS11-023</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Microsoft Excel Viewer Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2d75786a-2368-4ef2-970b-fa2e57d63ca9">Microsoft Excel Viewer Service Pack 2</a>
                    <br />(KB2466158)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft PowerPoint Viewer 2007 Service Pack 2</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e23d3c3-2944-42ea-80b3-0663af60d0f1">Microsoft PowerPoint Viewer 2007 Service Pack 2</a>
                    <br />(KB2464623)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft PowerPoint Viewer</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44a703f5-b581-4900-bdbb-0f0e8d9bf0e6">Microsoft PowerPoint Viewer</a>
                    <br />(KB2519984)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=946cc611-4d75-4728-b9d3-1c8b557b02c2">Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB2466156)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=913efc28-7deb-47b8-8c22-8eb5fc2631e4">Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB2464635)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              </table>


**Merknad for MS11-029**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

**Merknad for MS11-021**

\[1\]For Microsoft Excel 2007 Service Pack 2 må kunder i tillegg til sikkerhetsoppdateringen KB2464583 også installere sikkerhetsoppdateringen for Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007 (KB2466156) for å være beskyttet mot sikkerhetsproblemene beskrevet i denne bulletinen.

**Merknad for MS11-022**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Microsoft Server-programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Office Web Apps</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=210727">
                      <strong>MS11-022</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office Web Apps</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9847dc05-7d4a-4a64-9e6a-622d3fa171f9">Microsoft PowerPoint Web App</a>
                    <br />(KB2520047)<br />(Viktig)</td></tr>
              </table>


**Merknad for MS11-022**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Utviklerverktøy og programvare fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Visual Studio</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=209720">
                      <strong>MS11-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual Studio .NET 2003 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9501082-a651-452b-8c1a-43987ffd3102">Microsoft Visual Studio .NET 2003 Service Pack 1</a>
                    <br />(KB2465373)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2005 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee64d83b-6c06-4ccf-b12d-99e2a7a7b18d">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB2538218)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Visual Studio 2008 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6a8e024-12ee-43d5-9aae-4c721505d6df">Microsoft Visual Studio 2008 Service Pack 1</a>
                    <br />(KB2538241)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2010 og Microsoft Visual Studio 2010 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7fd643a8-8e05-4d27-8853-33f79f01cb26">Microsoft Visual Studio 2010</a>
                    <br />(KB2542054)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a21c9db-dfa3-4a07-a1e0-89a8069b7c17">Microsoft Visual Studio 2010 Service Pack 1</a><br />(KB2565057)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Visual C++ 2005 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae2e1a40-7b45-4fe9-a20f-2ed2923aca62">Microsoft Visual C++ 2005 Service Pack 1 Redistributable Package</a>
                    <br />(KB2538242)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual C++ 2008 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a821847e-4c44-45c0-9128-61c822bb3280">Microsoft Visual C++ 2008 Service Pack 1 Redistributable Package</a>
                    <br />(KB2538243)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Visual C++ 2010 og Microsoft Visual C++ 2010 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe558aed-9274-415f-8a0f-d9d8622fb35b">Microsoft Visual C++ 2010 Redistributable Package</a>
                    <br />(KB2467173)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7557d29b-731b-4abb-8815-2b87a4132efb">Microsoft Visual C++ 2010 Redistributable Package Service Pack 1</a><br />(KB2565063)<br />(Viktig)</td></tr>
              </table>


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

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse oppgaven med å levere og administrere oppdateringer til IT-systemer i hele bedriften. Med Configuration Manager 2007 kan IT-administratorer levere oppdateringer av Microsoft-produkter til en rekke enheter, inkludert stasjonære datamaskiner, bærbare datamaskiner, servere og mobile enheter.

Den automatiske sikkerhetsproblemvurderingen i Configuration Manager 2007 oppdager behov for oppdateringer og rapporterer om anbefalte handlinger. Software Update Management i Configuration Manager 2007 er bygd på Microsoft Windows Software Update Services (WSUS), en tidstestet oppdateringsinfrastruktur som er velkjent for IT-administratorer over hele verden. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke Configuration Manager 2007 til å distribuere oppdateringer, kan du se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Hvis du vil ha mer informasjon om Configuration Manager, kan du gå til [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne.

**Obs\!** System Management Server 2003 har ikke vanlig kundestøtte etter 12. januar 2010. Hvis du vil ha mer informasjon om produktlivssykluser, kan du gå til [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den neste utgivelsen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se det tidligere avsnittet **System Center Configuration Manager 2007**.

Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du se [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer for å gi bred støtte i forbindelse med søking etter og distribusjon av sikkerhetsbulletinoppdateringer. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Comp** **atibility Toolkit**

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

  - En anonym forsker i samarbeid med [VeriSign iDefense Laps](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-018
  - [MITRE](http://mitre.org/) for samarbeidet i forbindelse med et problem som beskrives i MS11-018
  - Michal Zalewski hos [Google Inc.](http://www.google.com/) for samarbeidet i forbindelse med et problem som beskrives i MS11-018
  - David Bloom hos [Google Inc.](http://www.google.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS11-018
  - Stephen Fewer hos [Harmony Security](http://www.harmonysecurity.com/) i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-018
  - Alin Rad Pop hos [Secunia Research](http://secunia.com/) for rapporten om to sikkerhetsproblemer som beskrives i ms11-021
  - Muhammad Junaid Bohio hos [Telus Security Labs](http://www.telussecuritylabs.com) for rapporten om et sikkerhetsproblem som beskrives i ms11-021
  - Aniway i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) rapporten om tre sikkerhetsproblemer som beskrives i ms11-021
  - En anonym forsker i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-021
  - Rodrigo Rubira Branco hos [Check Point Vulnerability Discovery Team](http://www.checkpoint.com/) (VDT) for rapporten om et sikkerhetsproblem som beskrives i ms11-021
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i ms11-021
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i ms11-021
  - [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om tre sikkerhetsproblemer som beskrives i MS11-022
  - Haifei Li hos [Fortinets FortiGuard Labs](http://www.fortiguard.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-023
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-023
  - Carsten Eiram hos [Secunia](http://secunia.com/) for samarbeidet i forbindelse med et sikkerhetsproblem som beskrives i MS11-024
  - [Google Security Team](http://www.google.com/) for samarbeidet i forbindelse med et sikkerhetsproblem som beskrives i MS11-026
  - Chris Ries hos Carnegie Mellon University Information Security Office for rapporten om et sikkerhetsproblem som beskrives i MS11-027
  - RadLSneak i samarbeid med [iSIGHT Partners](http://www.isightpartners.com/) Global Vulnerability Partnership for rapporten om et sikkerhetsproblem som beskrives i MS11-027
  - Nicolas Joly og Chaouki Bekrar hos [VUPEN Threat Protection Program](http://www.vupen.com/english/services/tpp-index.php) for rapporten om et sikkerhetsproblem som beskrives i MS11-029
  - Neel Mehta hos [Google Inc.](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-030
  - [Jesse Ruderman](http://www.squarefree.com/) hos [Mozilla](http://www.mozilla.org/) for samarbeidet i forbindelse med et problem som beskrives i MS11-031
  - Adam Twardoch hos [Fontlab Ltd.](http://www.fontlab.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-032
  - Carsten Eiram hos [Secunia](http://secunia.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-033
  - Tarjei Mandt hos [Norman](http://www.norman.com/) for rapporten om 30 sikkerhetsproblemer som beskrives i MS11-034

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (12. april 2011): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (13. april 2011): For MS11-019 er beskrivelsen av sikkerhetsproblemet i Kortfattet sammendrag klarlagt.
  - V2.0 (15. april 2011): For MS11-032 er vurderingsgraden for utnyttelsesindeksen hevet for CVE-2011-0034 til 1 – Konsekvent skadelig kode er sannsynlig.
  - V3.0 (21. april 2011): Revidert for å tilby den nyutgitte sikkerhetsoppdateringen for MS11-025.
  - V3.1 (27. april 2011): For MS11-024 er utnyttelsesindeksen korrigert for å legge til CVE-2010-4701 som et sikkerhetsproblem som behandles i denne oppdateringen. Dette er bare en informasjonsendring.
  - V4.0 (16. mai 2011): Sikkerhetsbulletinen MS11-018 utgis på nytt for å tilby oppdateringen for Internet Explorer 7 på nytt for støttede versjoner av Windows XP og Windows Server 2003. Dette er bare en gjenkjenningsendring. Det var ingen endinger i binære filer. Oppdateringen tilbys bare til berørte kunder. Kunder som har installert oppdateringen manuelt, og kunder som kjører konfigurasjoner som ikke er berørt av endringen av søkelogikken, trenger ikke å gjøre noe.
  - V5.0 (14. juni 2011): For MS11-025 tilbys ny oppdatering for Microsoft Visual Studio 2005 Service Pack 1, Microsoft Visual Studio 2008 Service Pack 1, Microsoft Visual Studio 2010, Microsoft Visual C++ 2005 Service Pack 1 Redistributable Package og Microsoft Visual C++ 2008 Service Pack 1 Redistributable Package. Kunder som allerede har installert denne oppdateringen, bør installere de nye oppdateringspakkene på de berørte systemene.
  - V6.0 (9. august 2011): For MS11-025 er Microsoft Visual Studio 2010 Service Pack 1 (KB2565057) og Microsoft Visual C++ 2010 Redistributable Package Service Pack 1 (KB2565063) lagt til som berørt programvare.
  - V6.1 (26. oktober 2011): For MS11-028 er brukbarheten for Server Core-installasjon endret for .NET Framework 4 på Windows Server 2008 R2 for x64-baserte systemer.

*Built at 2014-04-18T01:50:00Z-07:00*

