---
title: Sammendrag av Microsofts sikkerhetsbulletiner for august 2011
TOCTitle: MS11-AUG
ms:assetid: ms11-aug
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms11-aug(v=Security.10)
ms:contentKeyID: 61315225
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for august 2011

Publisert: 9. august 2011 | Oppdatert: 26. oktober 2011

**Versjon:** 1.2

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i august 2011.

I forbindelse med utgivelsen av bulletinene for august 2011 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 4. august 2011. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://go.microsoft.com/fwlink/?linkid=217213).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 10. august 2011 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for august på webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?culture=en-us&eventid=1032487857). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (2559049)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer og to offentliggjorte sikkerhetsproblemer i Internet Explorer. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td><strong>Sikkerhetsproblemer i DNS-serveren kan tillate ekstern kjøring av kode (2562485)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Windows DNS-server. Det mest alvorlige av disse sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en angriper registrerer et domene, oppretter en NAPTR DNS-ressursoppføring og deretter sender ut en spesiallaget NAPTR-spørring til DNS-målserveren. Servere der DNS-rollen ikke er aktivert, berøres ikke.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td><strong>Sikkerhetsproblem i Data Access Components kan tillate ekstern kjøring av kode (2560656)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker åpner en legitim Excel-fil (for eksempel en XLSX-fil) som ligger i samme nettverkskatalog som en spesiallaget biblioteksfil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Visio kan tillate ekstern kjøring av kode (2560978)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Visio. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Visio-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td><strong>Sikkerhetsproblem i Remote Desktop Web Access kan tillate rettighetsutvidelse (2546250)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Remote Desktop Web Access. Sikkerhetsproblemet er et skripting-på-tvers-av-områder-sikkerhetsproblem (XSS) som kan føre til rettighetsutvidelse, slik at en angriper kan utstede vilkårlige kommandoer på området i omgivelsene til målbrukeren. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 forebygger dette angrepet hos brukerne som går til en Remote Desktop Web Access-server i Internett-sonen. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 er som standard ikke aktivert i intranettsonen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td><strong>Sikkerhetsproblem i Remote Access Service NDISTAPI-driver kan tillate rettighetsutvidelse</strong> <strong>(2566454)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i alle støttede versjoner av Windows XP og Windows Server 2003. Denne sikkergetsoppdateringen har alvorlighetsgraden Viktig for alle støttede versjoner av Windows XP og Windows Server 2003. Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er ikke berørt av sikkerhetsproblemet.<br />
<br />
Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på et berørt system og starter et spesiallaget program som er utformet for å utnytte sikkerhetsproblemet og fullstendig ta over kontrollen over det berørte systemet. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte dette sikkerhetsproblemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td><strong>Sikkerhetsproblem i Windows Client/Server Run-time Subsystem kan tillate rettighetsutvidelse (2567680)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på et berørt system og starter et spesiallaget program som er utformet for å sende en enhetshendelsesmelding til en prosess med høyere integritet. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte dette sikkerhetsproblemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td><strong>Sikkerhetsproblemer i TCP/IP-stakk kan føre til tjenestenekt (2563894)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Windows. Sikkerhetsproblemene kan føre til tjenestenekt hvis en angriper sender en rekke med spesiallagede ICMP-meldinger (Internet Control Message Protocol) til et målsystem eller sender en spesiallaget URL-forespørsel til en server som er server for webinnhold og har den URL-baserte QoS-funksjonen (Quality of Service) aktivert.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td><strong>Sikkerhetsproblem i Remote Desktop Protocol kan tillate rettighetsutvidelse (2570222)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Remote Desktop Protocol. Sikkerhetsproblemet kan forårsake tjenestenekt hvis et berørt system mottar en rekke med spesiallagede RDP-pakker. Microsoft har også mottatt rapporter om begrensede, målrettede angrep som forsøker å utnytte dette sikkerhetsproblemet. Som standard er Remote Desktop Protocol (RDP) ikke aktivert på noe Windows-operativsystem.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Chart-kontroll kan tillate tilgjengeliggjøring av informasjon (2567943)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i ASP.NET Chart-kontroller. Sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en angriper sender en spesiallaget GET-forespørsel til en berørt server som er vert for Chart-kontrollene. Legg merke til at dette sikkerhetsproblemet ikke gjør det mulig for en angriper å kjøre kode eller å utvide egne brukerrettigheter direkte, men at det kan brukes til å fremskaffe informasjon som kan brukes til å skade det berørte systemet ytterligere. Bare Internett-programmer som bruker Microsoft Chart-kontroll er berørt av dette problemet. Standardinstallasjoner av .NET Framework er ikke berørt.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tilgjengeliggjøring av informasjon</td>
<td>Kan kreve omstart</td>
<td>Microsoft .NET Framework,<br />
Utviklerverktøy fra Microsoft</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Report Viewer kan tillate tilgjengeliggjøring av informasjon (2578230)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Report Viewer. Dette sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en bruker viser en spesiallaget webside. En angriper kan imidlertid aldri tvinge brukere til å besøke dette webområdet. Angriperen må derfor i stedet forsøke å overtale brukere til å besøke webområdet, vanligvis ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som viderekobler brukeren til det skadelige webområdet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tilgjengeliggjøring av informasjon</td>
<td>Kan kreve omstart</td>
<td>Utviklerverktøy fra Microsoft</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223578">MS11-068</a></td>
<td><strong>Sikkerhetsproblem i Windows-kjernen kan føre til tjenestenekt (2556532)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan føre til tjenestenekt hvis en bruker besøker en delt nettverksressurs (eller besøker et webområde som viser til en delt nettverksressurs) som inneholder en spesiallaget fil. En angriper kan imidlertid aldri tvinge brukere til å besøke slike webområder eller delte nettverksressurser. I stedet må en angriper forsøke å overtale brukere til å besøke de skadelige webområdene eller delte nettverksressursene, vanligvis ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Tjenestenekt</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221537">MS11-069</a></td>
<td><strong>Sikkerhetsproblem i .NET Framework kan føre til tilgjengeliggjøring av informasjon (2567951)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft .NET Framework. Sikkerhetsproblemet kan føre til tilgjengeliggjøring av informasjon hvis en bruker viser en spesiallaget webside ved hjelp av en webleser som kan kjøre XAML-leserprogrammer (XBAPer). I et webbasert angrepsscenario kan angriperen være vert for et webområde som inneholder en webside som brukes til å utnytte dette sikkerhetsproblemet. I tillegg kan utsatte webområder og webområder som godtar eller er vert for innhold eller reklame fra brukere, inneholde spesiallaget innhold som kan utnytte dette sikkerhetsproblemet. Men en angriper kan ikke i noen tilfeller tvinge brukere til å gå til disse webområdene. I stedet må angriperen lokke brukere til å besøke webområdet, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde. Dette sikkerhetsproblemet kan også brukes av Windows .NET-programmer til å omgå kodetilgangssikkerhetsrestriksjoner (CAS).</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Tilgjengeliggjøring av informasjon</td>
<td>Kan kreve omstart</td>
<td>Microsoft .NET Framework</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført etter bulletin-ID og deretter etter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan bruker jeg denne tabellen?**

Bruk denne tabellen til å få mer informasjon om sannsynligheten for angrep i form av kjøring av kode og tjenestenekt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen av denne månedens oppdateringer. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

I kolonnene nedenfor refererer "ny programvareversjon" til den aktuelle programvaren, og "eldre programvareversjoner" refererer til alle eldre, støttede versjoner av den aktuelle programvaren, slik de er oppført i tabellene Berørt programvare eller Uberørt programvare i bulletinen.

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Tittel på sikkerhetsproblem</th>
<th>CVE-ID</th>
<th>Vurdering av utnyttelsesgrad for kjøring av kode i ny programvareversjon</th>
<th>Vurdering av utnyttelsesgrad for kjøring av kode i eldre programvareversjoner</th>
<th>Vurdering av utnyttelsesgrad for tjenestenekt</th>
<th>Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sikkerhetsproblem med kappløpssituasjon ved åpning av vindu</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1257">CVE-2011-1257</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sikkerhetsproblem i hendelsesbehandling som kan føre til tilgjengeliggjøring av informasjon</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1960">CVE-2011-1960</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Ikke relevant</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sikkerhetsproblem i Telnet-behandler som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1961">CVE-2011-1961</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sikkerhetsproblem med minnefeil i XSLT</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1963">CVE-2011-1963</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221946">MS11-057</a></td>
<td>Sikkerhetsproblem med stilobjekt som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1964">CVE-2011-1964</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td>Sikkerhetsproblem med DNS NAPTR-spørring</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1966">CVE-2011-1966</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221812">MS11-058</a></td>
<td>Sikkerhetsproblem med feil i ikke-initialisert minne i DNS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1970">CVE-2011-1970</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Permanent</td>
<td>Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221539">MS11-059</a></td>
<td>Sikkerhetsproblem med usikker bibliotekinnlasting i Data Access Components</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1975">CVE-2011-1975</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td>Sikkerhetsproblem i pStream-versjon som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1972">CVE-2011-1972</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223425">MS11-060</a></td>
<td>Sikkerhetsproblem med Move Around the Block som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1979">CVE-2011-1979</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=217099">MS11-061</a></td>
<td>Sikkerhetsproblem i Remote Desktop Web Access</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1263">CVE-2011-1263</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223669">MS11-062</a></td>
<td>Sikkerhetsproblem i NDISTAPI som kan føre til rettighetsutvidelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1974">CVE-2011-1974</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221864">MS11-063</a></td>
<td>Sikkerhetsproblem i CSRSS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1967">CVE-2011-1967</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td>Sikkerhetsproblem med tjenestenekt i ICMP</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1871">CVE-2011-1871</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Permanent</td>
<td>Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221808">MS11-064</a></td>
<td>Sikkerhetsproblem med tjenestenekt i TCP/IP QOS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1965">CVE-2011-1965</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Ikke berørt</td>
<td>Permanent</td>
<td>Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221880">MS11-065</a></td>
<td>Sikkerhetsproblem i Remote Desktop Protocol</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1968">CVE-2011-1968</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Permanent</td>
<td>Det rapporteres om begrensede, målrettede angrep i forbindelse med dette sikkerhetsproblemet<br />
<br />
Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=221536">MS11-066</a></td>
<td>Sikkerhetsproblem i Chart-kontroll som kan føre til tilgjengeliggjøring av informasjon</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1977">CVE-2011-1977</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Ikke berørt</td>
<td>Ikke relevant</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=223643">MS11-067</a></td>
<td>Sikkerhetsproblem i XSS i Report Viewer-kontroller</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1976">CVE-2011-1976</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Ikke relevant</td>
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

**Tabell 1**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90312c78-1fbd-4143-b2e6-ae5c48af6f57">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a771c93b-55a4-456f-a315-d0d1f2696960">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5feb8ed7-99d2-4dd6-986f-57a7fd0c6f19">Internet Explorer 8</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bc1f0ac-223d-4b0b-86cd-2ba3863955c4">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0231c103-c0cb-4705-9d92-5356b8cbb265">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23d77f3b-13f8-49f3-9c3c-27ad217cd59e">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=acb14d82-a801-4ec7-84cc-9f131009ebcb">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=272c813b-bd39-4e63-9fa7-c5b8ed0b08d7">Internet Explorer 8</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5ee6787-408d-4870-af70-9338158b161b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09276f6e-e3f4-4b7e-996e-4ec376c103e1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet  </strong>
                    <strong>alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26b5fb48-346a-49f1-840f-03f218a41c20">Internet Explorer 6</a>
                    <br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=042552ad-f46a-4bfc-9e5c-58f095eba1de">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=648596fc-fd97-438a-97be-d5d590f1c561">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2d4aa38-9241-465d-8d65-aba73e936d0f">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8de0f2db-aa09-48cd-a13b-e26a973e9cdc">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=870fdfdd-16bf-42a2-a23b-ed6045438d5e">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c3d14d8-6716-4423-91a9-a05373227237">Internet Explorer 6</a>
                    <br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9e283d8-d4a2-41e2-a73c-92fae957ba3d">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=470d56d1-5789-42cc-a088-a2c8ac934ab3">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2db4098a-f4f9-4211-b55d-5d0df1409c43">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f208407-4bb3-41fe-b0d6-fc8a5e30e667">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31af27b8-7b73-4090-94bd-2fb89d3970fc">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td>Windows Server 2003 SP2 for Itanium-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=64496a87-2225-402a-a94a-a8e92b17ac83">Internet Explorer 6</a>
                    <br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5aa3a493-4188-48a9-a549-cf9ba01ed32a">Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1934acfa-5637-4ae9-9e9a-fc7e58930b7a">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef140089-d022-4ee8-9cc4-7fb25295a39d">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=410c72d8-3b78-4c4a-ad61-acb7f854ffc2">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66ddc7ce-5280-494d-bb3c-dab06e27fb5c">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a080f36e-c24f-40ac-bb40-b26cb31bcae3">Internet Explorer 8</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c82417ec-232f-4f84-ba2c-0ffad77e9bb5">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f25ced5-ef86-4b9d-91fb-443c9a2c1458">Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f119902-8398-4814-8229-9eb9f0980e87">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=704c1c9c-d1c1-40cb-97a7-fbb1f195f9f8">Internet Explorer 8</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a6ff7b27-bc21-4945-8b2e-757b6f83fa58">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5b8ff09-237e-49f1-a566-e323ca11fbc3">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
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
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da9c98d1-973c-44d9-aee5-f5c4a8e8c0e1">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d65ae4cc-d82a-42da-829f-d9479e23b7a5">Internet Explorer 8</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70065bd0-7c97-4ffc-828f-2cc245d04429">Internet Explorer 9</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac2d5122-6f9b-46f5-9840-77aa7ff84308">Windows Server 2008 for 32-biters systemer Service Pack 2</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fbaabb9-8601-4760-813d-aeedfdcafb8b">Windows Server 2008 for 32-biters systemer Service Pack 2</a>*<br />(Viktig)</td></tr>
                <tr><td>Windows Server 2008 for x64-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9facff69-618f-4a64-8665-5dd6cde07de9">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00f28d81-3714-403c-bcd7-55f2ac97f75b">Internet Explorer 8</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ce60689-ca85-4c9f-af96-a73b1e43c10b">Internet Explorer 9</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f605f6f-3854-403d-878b-637626aef78f">Windows Server 2008 for x64-baserte systemer Service Pack 2</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e7253d8-fdc7-4563-9714-21ca3c77e4b1">Windows Server 2008 for x64-baserte systemer Service Pack 2</a>*<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01885624-cfb1-4918-abef-ab0ea765cb04">Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe37eb6d-b1fa-496c-a0d3-19a6d35a6cb9">Windows Server 2008 for Itanium-baserte systemer Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="7">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7019de24-8c58-4565-ada1-ca8755115096">Internet Explorer 8</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12292081-23f7-4968-8cd7-17aaef2aed6a">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bc168d9-6664-41fb-914f-dbd7514a4b0e">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4551b77-eb09-448a-9dc5-66de846035e7">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fcdb872f-2ee2-4f74-b7ae-1b82daf66761">Internet Explorer 8</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef664114-6582-49d3-b332-078a7d075337">Internet Explorer 9</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aafeff2d-db9a-4b3b-b620-be4ec5f5bdcc">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fc9a501-523d-4cbb-8d99-a773089afc4c">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221946">
                      <strong>MS11-057</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221812">
                      <strong>MS11-058</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221539">
                      <strong>MS11-059</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217099">
                      <strong>MS11-061</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223669">
                      <strong>MS11-062</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221864">
                      <strong>MS11-063</strong>
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
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fe68eb-2aa6-4a59-b9d8-deeae5236af2">Internet Explorer 8</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd709da2-4cb1-482f-88eb-dfab4d3c59c6">Internet Explorer 9</a>**<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a86e2cf-4e7d-4012-88c3-6957a3842dd3">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c29deec3-4672-4658-a550-dce244434cd4">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=777f3bbe-094c-411d-879d-34a5a20ae7f3">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>**<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f4043df-c07c-4611-b06a-7fcbb7416e7d">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82403fd3-ed75-4ea8-aa3f-ed9dda75612a">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d6b8036-d38f-408a-a36c-027553faefc1">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b420cae3-de30-4c6c-8ed9-7431ad7ab4da">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Tabell 2**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="6">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c07e1630-43ba-491e-bd59-9eb53105986c">Windows XP Service Pack 3</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=797a01dc-39fb-4511-832a-42d2975133f5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=694ba1a6-7512-497d-a572-646a6e07b13b">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=308da543-d49d-4591-8bbc-d65c524bb0ad">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 SP2 for Itanium-baserte systemer</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b459bf0-7844-4740-895c-d149d56e781f">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14fdbaa4-b42b-499c-819f-bb239b48a4cc">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539631)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=114c2835-921a-4d3e-be91-dfd217fd26a9">Windows Vista Service Pack 2</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9713b7b8-f260-440d-a994-845f17683fe9">Windows Vista Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fcee476-8d7e-49a7-b6ea-89043304a653">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d67ec00-e86a-49b6-a9a2-85b2520fa4bb">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c01d9132-af5f-4039-8195-95f6761f2d0e">Windows Server 2008 for 32-biters systemer Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>**[1]<br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da219735-b8b7-4f97-b8a8-7c253838de6b">Windows Server 2008 for 32-biters systemer Service Pack 2</a>***<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>**[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 for x64-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70797adb-d693-4102-9e7c-ba1ea8fb07d0">Windows Server 2008 for x64-baserte systemer Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>**[1]<br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e077af5-5823-4377-a997-44b022a694d8">Windows Server 2008 for x64-baserte systemer Service Pack 2</a>***<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>**[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9babf81a-8b21-42ae-a65c-f414793516ab">Windows Server 2008 for Itanium-baserte systemer Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=560efa6f-c956-47cb-a2f4-a1f45278b7cd">Windows Server 2008 for Itanium-baserte systemer Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7348c0-a036-4d86-b7bb-bd6810cdc834">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2539633)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=814bbdfa-7cbc-40e5-8ca3-8fed9d13ff00">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c8dd72b-abf8-4e1f-aafc-777c1a3ef3db">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Bare Windows 7 for 32-biters systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a><br />(KB2539634)<br />(Moderat)<br /><br />Bare Windows 7 for 32-biters systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Windows 7 for 32-biters systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a><br />(KB2539635)<br />(Moderat)<br /><br />Windows 7 for 32-biters systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=085ee785-b6ad-4c68-835a-e17bc8f12a53">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d90c07c1-3c07-4989-825c-fb8453541a0e">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Bare Windows 7 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a><br />(KB2539634)<br />(Moderat)<br /><br />Bare Windows 7 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Windows 7 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a><br />(KB2539635)<br />(Moderat)<br /><br />Windows 7 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              
                <tr><th colspan="6">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221808">
                      <strong>MS11-064</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221880">
                      <strong>MS11-065</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223578">
                      <strong>MS11-068</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221537">
                      <strong>MS11-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9fd2b4ba-d98e-4ad6-99f2-c471335042d3">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>Bare Windows Server 2008 R2 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>[1]<br />(KB2487367)<br />(Viktig)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>*[1]<br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67cccd09-5b82-4546-884a-d2a9e2400820">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>***<br />(Moderat)</td><td>Bare Windows Server 2008 R2 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a>*<br />(KB2539634)<br />(Moderat)<br /><br />Bare Windows Server 2008 R2 for x64-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a>*<br />(KB2539635)<br />(Moderat)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>*[1]<br />(KB2539636)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93752c8f-5461-4e6f-9cab-6401b985ef17">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ca837f7-eda1-4ebe-b48a-8c77f949ebfd">Microsoft .NET Framework 4</a>
                    [1]
                    <br />(KB2487367)<br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1edf843-9a2a-4334-a95f-78e75a9b3ef1">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Moderat)</td><td>Windows Server 2008 R2 bare for Itanium-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c628c6-5dcc-4c8f-b379-e2249a44f12c">Microsoft .NET Framework 3.5.1</a><br />(KB2539634)<br />(Moderat)<br /><br />Windows Server 2008 R2 bare for Itanium-baserte systemer:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1f84749-77bb-42bf-a539-fb647cacff8b">Microsoft .NET Framework 3.5.1</a><br />(KB2539635)<br />(Moderat)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer bare med Service Pack 1:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2069b12-d78b-420c-84b7-46bba12827c8">Microsoft .NET Framework 4</a>[1]<br />(KB2539636)<br />(Moderat)</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*\*Server Core-installasjonen er ikke berørt.** Sikkerhetsproblemet som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core, selv om filer som er berørt av dette sikkerhetsproblemet, kan være til stede i systemet. Brukere blir imidlertid fortsatt tilbudt denne oppdateringen fordi oppdateringsfilene er nyere (med høyere versjonsnumre) enn filene som finnes på systemet. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknader for MS11-066**

\[1\] **.NET Framework 4 Client Profile er ikke berørt.** Omdistribuerbare pakker for .NET Framework versjon 4 er tilgjengelig i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er en del av .NET Framework 4. Sikkerhetsproblemet som løses i denne oppdateringen, berører bare .NET Framework 4 og ikke .NET Framework 4 Client Profile. Hvis du vil ha mer informasjon, kan du se MSDN-artikkelen om å [installere .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

**Merknad for MS11-069**

\[1\] **.NET Framework 4 og .NET Framework 4 Client Profile er berørt.** Omdistribuerbare pakker for .NET Framework versjon 4 er tilgjengelig i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er en del av .NET Framework 4. Sikkerhetsproblemet som løses i denne oppdateringen, berører både .NET Framework 4 og .NET Framework 4 Client Profile. Hvis du vil ha mer informasjon, kan du se MSDN-artikkelen om å [installere .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Visio</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223425">
                      <strong>MS11-060</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visio 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=866d64b3-7147-4b5f-80fe-4d3317f140df">Microsoft Visio 2003 Service Pack 3</a>
                    <br />(KB2553009)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visio 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0eeabde-5a92-45ae-aef6-81b7bdb4e0cd">Microsoft Visio 2007 Service Pack 2</a>
                    <br />(KB2553010)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Visio 2010 og Microsoft Visio 2010 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6da236c2-0ef5-4c13-8393-673b70298a77">Microsoft Visio 2010 og Microsoft Visio 2010 Service Pack 1 (32-biters versjoner)</a>
                    <br />(KB2553008)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7f5f2a9-116a-41ef-a19e-a7dd0947d2cb">Microsoft Visio 2010 og Microsoft Visio 2010 Service Pack 1 (64-biters versjoner)</a><br />(KB2553008)<br />(Viktig)</td></tr>
              </table>


#### Utviklerverktøy og programvare fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Chart Control</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223643">
                      <strong>MS11-067</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Chart Control for Microsoft .NET Framework 3.5 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8a80cc03-0db9-4446-9ce6-159ad02cab52">Chart Control for Microsoft .NET Framework 3.5 Service Pack 1</a>
                    <br />(KB2500170)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Microsoft Visual Studio og Microsoft Report Viewer</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=221536">
                      <strong>MS11-066</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=223643">
                      <strong>MS11-067</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2005 Service Pack 1</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59231988-5413-4238-a3aa-32a127871430">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB2548826)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28bf2ae0-9e21-4201-b7f1-a207abc2866f">Microsoft Report Viewer 2005 Service Pack 1 Redistributable Package</a>
                    <br />(KB2579115)<br />(Viktig)</td></tr>
              </table>


**Merknad for MS11-066**

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

  - Yngve N. Pettersen hos [Opera Software ASA](http://www.opera.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-057
  - [Lostmon Lords](http://lostmon.blogspot.com) for rapporten om et sikkerhetsproblem som beskrives i MS11-057
  - Makoto Shiotsuki hos [Security Professionals Network Inc.](http://www.sec-pro.net/) for rapporten om et sikkerhetsproblem som beskrives i MS11-057
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-057
  - Stephen Fewer hos [Harmony Security](http://www.harmonysecurity.com/) i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS11-057
  - Michal Zalewski hos [Google Inc.](http://www.google.com/) for for samarbeidet om endringer i dybdeforsvar som er inkludert i MS11-057
  - Grischa Zengel ([Zengel Medizintechnik GmbH](http://www.zmt.info/)) for rapporten om et sikkerhetsproblem som beskrives i MS11-058
  - Linlin Zhao hos [Baidu Security Team](http://www.baidu.com) for rapporten om to sikkerhetsproblemer som beskrives in MS11-060
  - Sven Taute for rapporten om et sikkerhetsproblem som beskrives i MS11-061
  - Lufeng Li hos for rapporten om et sikkerhetsproblem som beskrives i MS11-062
  - Alex Ionescu hos Winsider Seminars & Solutions Inc. for rapporten om et sikkerhetsproblem som beskrives i MS11-063
  - Nico Leidecker og James Forshaw hos Context Information Security for rapporten om et sikkerhetsproblem som beskrives i MS11-066
  - Adam Bixby hos [Gotham Digital Science](http://www.gdssecurity.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-067
  - Zheng Wenbin hos [Qihoo 360 Security Center](http://www.360.cn/) for rapporten om et sikkerhetsproblem som beskrives i MS11-068
  - Michael J. Liu for rapporten om et sikkerhetsproblem som beskrives i MS11-069

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (9. august 2011): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (10. august 2011): Informasjon om omstartskrav er korrigert for MS11-059 i delen **Kortfattet sammendra**g. En viktig merknad er korrigert for MS11-065 i **utnyttelsesindeksen** for CVE-2011-1968. En notasjon for serverkjerne er revidert for MS11-068 for Windows Server 2008 og Windows Server 2008 R2.
  - V1.2 (26. oktober 2011): For MS11-066 og MS11-069 er brukbarheten for Server Core-installasjon endret for .NET Framework 4 på Windows Server 2008 R2 for x64-baserte systemer.

*Built at 2014-04-18T01:50:00Z-07:00*

