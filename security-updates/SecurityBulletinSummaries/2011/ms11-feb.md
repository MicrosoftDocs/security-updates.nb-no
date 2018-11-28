---
title: Sammendrag av Microsofts sikkerhetsbulletiner for februar 2011
TOCTitle: MS11-FEB
ms:assetid: ms11-feb
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms11-feb(v=Security.10)
ms:contentKeyID: 61315227
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for februar 2011

Publisert: 8. februar 2011 | Oppdatert: 18. mars 2011

**Versjon:** 4.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i februar 2011.

I forbindelse med utgivelsen av bulletinene for febuar 2011 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 3. februar 2011. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 9. februar 2011 kl. 11.00 stillehavstid (USA og Canada). Registrer deg nå for å følge [sikkerhetsbulletinen for februar på webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032455047&eventcategory=4). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (2482017)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer og to offentliggjorte sikkerhetsproblemer i Internet Explorer. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside i Internet Explorer eller hvis en bruker åpner en legitim HTTP-fil som laster inn en spesiallaget biblioteksfil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208146">MS11-006</a></td>
<td><strong>Sikkerhetsproblem i grafikkbehandling i Windows-skallet kan tillate ekstern kjøring av kode (2483185)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i grafikkbehandlingen i Windows-skallet. Sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner et spesiallaget miniatyrbilde. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208059">MS11-007</a></td>
<td><strong>Sikkerhetsproblem i driver for OpenType-skrifter i CFF-format kan føre til ekstern kjøring av kode (2485376)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows-driveren for OpenType-skrifter i CFF-format. Sikkerhetsproblemet kan føre til ekstern kjøring av kode hvis en bruker viser innhold gjengitt i en spesiallaget CFF-skrift. Uansett kan ikke en angriper tvinge brukerne til å bruke det spesiallagde innholdet. I stedet må angriperen lokke brukere til å besøke et webområde, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208522">MS11-004</a></td>
<td><strong>Sikkerhetsproblem i FTP-tjenesten for Internet Information Services (IIS) kan tillate ekstern kjøring av kode (2489256)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i FTP-tjenesten for Microsoft Internet Information Services (IIS). Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en FTP-server mottar en spesiallaget FTP-kommando. FTP-tjenesten er ikke installert som standard for IIS.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207843">MS11-005</a></td>
<td><strong>Sikkerhetsproblem i Active Directory kan føre til tjenestenekt (2478953)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i Active Directory. Sikkerhetsproblemet kan føre til tjenestenekt hvis en angriper sender en spesiallaget pakke til en berørt Active Directory-server. En angriper må ha gyldige lokale administratorrettigheter på en datamaskin som er tilknyttet et domene, for å kunne utnytte dette sikkerhetsproblemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204799">MS11-008</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Visio kan tillate ekstern kjøring av kode (2451879)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Visio. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Visio-fil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207839">MS11-009</a></td>
<td><strong>Sikkerhetsproblem i skriptmotorer for JScript og VBScript kan føre til tilgjengeliggjøring av informasjon (2475792)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i skriptmotorene for JScript og VBScript. Dette sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en bruker besøker en spesiallaget webside. En angriper kan ikke tvinge brukere til å besøke disse webområdene. I stedet må angriperen lokke brukere til å besøke webområdet, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tilgjengeliggjøring av informasjon</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207840">MS11-010</a></td>
<td><strong>Sikkerhetsproblem i Windows Client/Server Run-time Subsystem kan tillate rettighetsutvidelse (2476687)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows Client/Server Run-time Subsystem (CSRSS) i Windows XP og Windows Server 2003.<br />
<br />
Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på systemet og starter et spesiallaget program som er utformet for å fortsette å kjøre etter at angriperen logger seg av, for å få tilgang til påloggingsinformasjonen til de neste brukerne. En angriper må ha gyldig legitimasjon for pålogging og må kunne logge seg på lokalt for å kunne utnytte sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208365">MS11-011</a></td>
<td><strong>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (2393802)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem og et personlig rapportert sikkerhetsproblem i Microsoft Windows. Disse sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en angriper logger seg på lokalt og kjører et spesiallaget program. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte disse sikkerhetsproblemene. Sikkerhetsproblemene kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td><strong>Sikkerhetsproblemer i Windows-kjernemodusdrivere kan tillate rettighetsutvidelse (2479628)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer i Microsoft Windows. Disse sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en angriper logger seg på lokalt og kjører et spesiallaget program. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte disse sikkerhetsproblemene. Sikkerhetsproblemene kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208523">MS11-013</a></td>
<td><strong>Sikkerhetsproblemer i Kerberos kan tillate rettighetsutvidelse (2496930)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem og et offentliggjort sikkerhetsproblem i Microsoft Windows. Det mest alvorlige av disse sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en lokal, godkjent angriper installerer en skadelig tjeneste på en datamaskin som er tilknyttet et domene.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208395">MS11-014</a></td>
<td><strong>Sikkerhetsproblem i Local Security Authority Subsystem Service kan tillate lokal rettighetsutvidelse (2478960)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Local Security Authority Subsystem Service (LSASS) i Windows XP og Windows Server 2003.<br />
<br />
Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på systemet og deretter kjører et spesiallaget program. En angriper må ha gyldig legitimasjon for pålogging og må kunne logge seg på lokalt for å kunne utnytte sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført i synkende rekkefølge etter utnyttelsesvurderingsnivå og deretter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan bruker jeg denne tabellen?**

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=208146">MS11-006</a></td>
<td>Sikkerhetsproblem i grafikkbehandlingsoverløp i Windows-skallet</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3970">CVE-2010-3970</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert, og skadelig kode er tilgjengelig</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td>Sikkerhetsproblem i CSS kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3971">CVE-2010-3971</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert og utnyttes på Internett</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208365">MS11-011</a></td>
<td>Sikkerhetsproblem i Windows-kjernen med uriktig driversamhandling</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-4398">CVE-2010-4398</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207840">MS11-010</a></td>
<td>Sikkerhetsproblem i CSRSS som kan føre til rettighetsutvidelse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0030">CVE-2011-0030</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td>Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0035">CVE-2011-0035</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208304">MS11-003</a></td>
<td>Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0036">CVE-2011-0036</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208395">MS11-014</a></td>
<td>Sikkerhetsproblem med validering av lengde i LSASS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0039">CVE-2011-0039</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208523">MS11-013</a></td>
<td>Sikkerhetsproblem med kontrollsum uten nøkkel i Kerberos</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0043">CVE-2011-0043</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208365">MS11-011</a></td>
<td>Sikkerhetsproblem med trunkering av heltall i Windows-kjernen</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0045">CVE-2011-0045</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td>Sikkerhetsproblem med uriktig validering av brukerinndata i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0086">CVE-2011-0086</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td>Sikkerhetsproblem med utilstrekkelig validering av brukerinndata i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0087">CVE-2011-0087</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td>Sikkerhetsproblem med sammenblanding av pekere for vindusklasser i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0088">CVE-2011-0088</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td>Sikkerhetsproblem med uriktig validering av pekere for vindusklasser i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0089">CVE-2011-0089</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208362">MS11-012</a></td>
<td>Sikkerhetsproblem med minnefeil i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0090">CVE-2011-0090</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204799">MS11-008</a></td>
<td>Sikkerhetsproblem med Visio-objekt som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0092">CVE-2011-0092</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204799">MS11-008</a></td>
<td>Sikkerhetsproblem med Visio-datatype som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0093">CVE-2011-0093</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208522">MS11-004</a></td>
<td>Sikkerhetsproblem med heap-bufferoverløp i FTP-tjenesten for IIS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3972">CVE-2010-3972</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert offentlig, og PoC-kode er tilgjengelig</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208059">MS11-007</a></td>
<td>Sikkerhetsproblem med kodede tegn i OpenType-skrift</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0033">CVE-2011-0033</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207839">MS11-009</a></td>
<td>Sikkerhetsproblem med skriptmotorer som kan føre til tilgjengeliggjøring av informasjon</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0031">CVE-2011-0031</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=207843">MS11-005</a></td>
<td>Sikkerhetsproblem i Active Directory med SPN-validering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0040">CVE-2011-0040</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong><br />
<br />
Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=208523">MS11-013</a></td>
<td>Sikkerhetsproblem med etterligningsangrep i Kerberos</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0091">CVE-2011-0091</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette er et sikkerhetsproblem som bare kan tillate etterligningsangrep</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

Følgende tabeller viser bulletinene etter store programvarekategorier og alvorlighetsgrad.

**Hvordan bruker jeg disse tabellene?**

Bruk disse tabellene til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det kommer noen sikkerhetsoppdateringer som angår installasjonen din. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

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
  </tr>
                <tr><th colspan="12">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208304">
                      <strong>MS11-003</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208146">
                      <strong>MS11-006</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208059">
                      <strong>MS11-007</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208522">
                      <strong>MS11-004</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207843">
                      <strong>MS11-005</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207839">
                      <strong>MS11-009</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207840">
                      <strong>MS11-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208365">
                      <strong>MS11-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208362">
                      <strong>MS11-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208523">
                      <strong>MS11-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208395">
                      <strong>MS11-014</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae343de6-ec61-4891-b136-cfc4234d97d9">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85bf88b7-2dd9-4204-8492-b2c1d8d2264e">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72fbb97-2313-45f6-842d-99db373822dd">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbea7ead-6c5c-4da8-aa03-a40325fd2de3">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f86e9e64-801a-431a-b24e-772011dfa66d">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cfa10178-9859-4e03-bedc-e3f5297a0251">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a511d33a-9ae0-46ee-a225-9d97390de7d1">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56f4f43e-c313-49dc-a278-e3e8a83a907e">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=486d1969-6814-4556-8dc0-5bfbaee528b0">Windows XP Service Pack 3</a>
                    <br />(KB2478971)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=541f228f-79b3-402a-8ff9-366c1e595227">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d431100d-a627-4ea0-b75b-2d4157e38df2">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a795de21-13f4-4035-a4d5-4257ddc92fe7">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69dfa24b-7c56-4521-850c-1485b062154a">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bcb7217e-624a-4d61-86a1-f2440a1afd57">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=074396f0-a68c-4190-8dac-0b883d56e3f1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9f0b7b77-5b90-4a4b-97a4-0c1ce6a70126">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7273a85-ce96-464b-8c4f-2710701213e3">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e80db313-b470-4d71-bc34-70bfbfb6579f">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a210c796-7077-4617-a9a8-9ea99fe11a5e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2478971)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82189bf2-3f34-4949-92da-eea98036d18e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="12">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208304">
                      <strong>MS11-003</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208146">
                      <strong>MS11-006</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208059">
                      <strong>MS11-007</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208522">
                      <strong>MS11-004</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207843">
                      <strong>MS11-005</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207839">
                      <strong>MS11-009</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207840">
                      <strong>MS11-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208365">
                      <strong>MS11-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208362">
                      <strong>MS11-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208523">
                      <strong>MS11-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208395">
                      <strong>MS11-014</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e0f4bf2-f727-483a-af3a-9a2abf0c36bb">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45e504d4-c17d-4b73-b08e-d9c0cb3f4918">Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=74238e08-fae2-4f17-ac72-681226a53a40">Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aa94528-5063-427b-97f7-2a0a55cbb6bf">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a99c2b13-db81-4f18-9cf7-c20614ba0132">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=651c1f4f-4e69-4d17-8aa2-72681dfc5463">Active Directory</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aed08b96-24cc-4e23-8fd5-c7e52f8ef41a">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bf2eeec-8225-477f-a606-263d3ee434d6">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54fe2669-8a63-4d96-8b82-5b10f45b293e">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8a1e2675-0bf0-4d94-b48a-6e846dd6d9f5">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2478971)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e31e6b1-577e-468e-9c94-67227d2273c2">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0592b520-88d1-45bc-8b15-d3f0c8fa2181">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29adcfb5-540f-4980-b2ca-9a22aa7bba13">Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebef4869-9812-46ce-9c01-2fb8c866ec90">Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e740922-6ce4-46ec-a35e-e94201a9e398">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aeed45fb-9395-4c2b-a674-e38b04fe0914">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec962b0e-e951-4e70-8d97-8c2afd360c28">Active Directory</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca7879e1-e295-445d-a658-0a31be1928cc">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec544894-ee98-4a2b-ac4d-33b0c3754213">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4632e1ce-6ae8-431c-9104-9a8840e5ac63">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e79bbbd4-8d5a-4c4c-8427-21c14400f041">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2478971)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76e3c229-d812-433c-ad05-7cbd1f9c6a6d">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td>Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b2298b32-238a-4970-bc1f-2ede51a6c361">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c41a0094-204b-4d05-ab39-a32915201af1">Internet Explorer 7</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a4f9ec46-35b2-44c9-abf6-647f7a474b99">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc09e42b-2eed-41b3-a03f-cb8cc94adfee">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ac66eae-e6d8-4e8b-b4ea-e7a77cc74db0">Active Directory</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50855101-a15c-4c81-ad81-a7fe3f1d2026">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fcd48499-1bb4-4304-b9cc-27d9d92e11cd">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a09c3e6e-c55c-492a-b7ad-3e3d35711643">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=856fbcc2-ead9-4ec1-92dd-988e6d22dae9">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(KB2478971)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0cde8d8-7c85-4fcb-bcf7-205064970b41">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="12">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208304">
                      <strong>MS11-003</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208146">
                      <strong>MS11-006</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208059">
                      <strong>MS11-007</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208522">
                      <strong>MS11-004</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207843">
                      <strong>MS11-005</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207839">
                      <strong>MS11-009</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207840">
                      <strong>MS11-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208365">
                      <strong>MS11-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208362">
                      <strong>MS11-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208523">
                      <strong>MS11-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208395">
                      <strong>MS11-014</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b176777e-4897-4cf1-9fc0-dd608930bb4c">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77971c3c-55ec-4a9c-bcb8-8fb8c61431e3">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c18ecca-afb9-4738-bc7b-76a0e815dfb8">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d60a2098-7351-4fce-83b2-2c1c3a24faa0">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c09ccc72-8f94-416b-9a7f-ed16e90342a2">Microsoft FTP Service 7.0 for IIS 7.0</a>
                    [1]
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da9b7982-1c6b-45ac-8dd0-d7101bb83949">Microsoft FTP Service 7.5 for IIS 7.0</a>[1]<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66978514-bb7f-42cc-9360-2fd1c686f4e6">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6fb7ebcc-2052-457b-b5bc-1bbcb17696b9">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20ad0136-c6df-4c7b-811f-d6b3dd9e2c56">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3580784-aada-4118-b7f2-3a23aec2ed04">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62dc454f-4b1e-4ac0-8ffe-6c73112f8d4d">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=065ad8fe-1caf-488e-a2e1-96db29f2fa57">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e88d072f-0f5f-4c85-ad2f-91b9b8bf6b3a">Microsoft FTP Service 7.0 for IIS 7.0</a>
                    [1]
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e4b9878-b5d2-4025-8839-b41515932cf2">Microsoft FTP Service 7.5 for IIS 7.0</a>[1]<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fdb8c37-1b22-457b-bdc0-21f6a5061dd3">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88d68757-1ab0-4585-9578-52a474b10882">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="12">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208304">
                      <strong>MS11-003</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208146">
                      <strong>MS11-006</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208059">
                      <strong>MS11-007</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208522">
                      <strong>MS11-004</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207843">
                      <strong>MS11-005</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207839">
                      <strong>MS11-009</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207840">
                      <strong>MS11-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208365">
                      <strong>MS11-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208362">
                      <strong>MS11-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208523">
                      <strong>MS11-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208395">
                      <strong>MS11-014</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee61f0dd-9797-4e11-8281-a05b201d0c0b">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef1ae382-8835-4f60-83bd-e84a3400d55c">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=253c47a0-69ac-437a-ad3e-778c37fa37cb">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88ba83b9-c14e-499a-8335-04bac1c49c0c">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3cc55af7-5cd9-4923-8ec5-462ff201d734">Microsoft FTP Service 7.0 for IIS 7.0</a>
                    [1]*<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4dfa0a25-b7e3-4fb6-a351-58ec3f8a8435">Microsoft FTP Service 7.5 for IIS 7.0</a>[1]*<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b37418a-e044-415e-b566-4507f157934a">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80494972-db45-475f-97cd-dac46b9486a1">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=558bc86a-a49d-4d6c-b5e4-f12956f6b61b">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5607df02-93fa-45fe-a928-e5f6329851f3">Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec7101aa-96c2-4931-a3e4-0c55cbc74d9c">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c74d7f4-6372-4809-89b8-c79b05e54cdd">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f485b30d-dcaf-47c3-ac62-982b14670a1f">Microsoft FTP Service 7.0 for IIS 7.0</a>
                    [1]*<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a98a74c1-0c91-446d-b822-fe57ff06d90b">Microsoft FTP Service 7.5 for IIS 7.0</a>[1]*<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=163d3aca-3703-452e-b1cb-73932e2bcf8c">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5597d449-17e3-440f-8b0e-56a902a96569">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c2abba5-0597-4565-9b87-a37e574690e0">Internet Explorer 7</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e62493cb-8d25-4975-bbe6-a368e039872b">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91d5d34b-9d7e-4e83-89a4-f1aa388dc4e4">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55b07bc0-dff5-4cd7-87c9-c08e5a49197d">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d10eda21-b3c3-4d8e-8596-bc45e4165f93">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="12">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208304">
                      <strong>MS11-003</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208146">
                      <strong>MS11-006</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208059">
                      <strong>MS11-007</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208522">
                      <strong>MS11-004</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207843">
                      <strong>MS11-005</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207839">
                      <strong>MS11-009</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207840">
                      <strong>MS11-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208365">
                      <strong>MS11-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208362">
                      <strong>MS11-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208523">
                      <strong>MS11-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208395">
                      <strong>MS11-014</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07aa7ffc-47c7-4611-b32c-ecb3fbcad32f">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1da57fbc-9ea4-4fc4-911d-d5c7825e012c">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9dabd1d1-3f1e-46d1-b171-aafd3f08d291">Microsoft FTP Service 7.5 for IIS 7.5</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac">JScript 5.8</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54a64215-e407-4b7b-8536-28817ef23bac">VBScript 5.8</a><br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1224c90-b0bc-4e4b-999a-efae327213b4">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=078fe6c0-1b2c-4896-a345-25cc1b1105e2">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffed7c76-0b75-4f57-9b63-3961a8b449f6">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(KB2425227)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b8ffafe-78bb-4fa7-aea2-01208b6a3dfe">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=587adb89-2f6a-4893-9906-b6d6d9ada2bd">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66fb4efe-bcd3-4e90-8e35-b013e014a952">Microsoft FTP Service 7.5 for IIS 7.5</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d">JScript 5.8</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b854d76e-6891-426d-8c09-0ed8243a3b8d">VBScript 5.8</a><br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ddcf352e-742c-485e-9ed5-19cdba673562">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b42642b3-fb78-4700-bfe8-bfa997b90c16">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c26cebcf-683f-4a51-be75-76535fb979a7">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(KB2425227)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="12">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208304">
                      <strong>MS11-003</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208146">
                      <strong>MS11-006</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208059">
                      <strong>MS11-007</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208522">
                      <strong>MS11-004</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207843">
                      <strong>MS11-005</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207839">
                      <strong>MS11-009</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=207840">
                      <strong>MS11-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208365">
                      <strong>MS11-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208362">
                      <strong>MS11-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208523">
                      <strong>MS11-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=208395">
                      <strong>MS11-014</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer med Service Pack 2**[1]</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38b67efb-dd4b-4e8c-8460-0f40f0367441">Internet Explorer 8</a>**<br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=638318ed-4000-4b1a-bb4b-65b795f59784">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e075f57-1723-4933-9b8e-7bce4a44a1c1">Microsoft FTP Service 7.5 for IIS 7.5</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285">JScript 5.8</a>**<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f482bd40-f0b9-4534-a768-45879f1e7285">VBScript 5.8</a>**<br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70f5056a-72ad-46ff-a43f-ee151639b9a7">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2c53f44-12eb-4293-9fa5-2a14075b636e">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46bb3ef1-24c3-41cb-8141-0fdbd85093f7">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>*<br />(KB2425227)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0e41cbe5-5e5e-4ece-a71a-71f4b6319f0d">Internet Explorer 8</a>
                    <br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4688ea0d-a467-4f24-ac52-104d05c8cae8">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfddd539-c64f-4467-88ee-6bdfe645b478">Microsoft FTP Service 7.5 for IIS 7.5</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0">JScript 5.8</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f05a3de0-381c-4d17-83ee-ca4f6da1bdb0">VBScript 5.8</a><br />(Moderat)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1646b3a5-714f-4ea5-b109-566fa9b933b6">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c6bf720-f544-4f58-9b1c-2399957ec43d">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01737933-e7de-451b-b02f-b7ca24693965">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</a>
                    <br />(KB2425227)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene om [administrasjon av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [betjening av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene om [administrasjon av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [betjening av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS11-004**

\[1\]Ikke standard FTP-tjeneste for dette operativsystemet

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Office-programmer</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204799">
                      <strong>MS11-008</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visio 2002 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=273d8078-0dc7-43d8-bcae-54c811e49e0e">Microsoft Visio 2002 Service Pack 2</a>
                    <br />(KB2434711)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visio 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1067eaa-d18d-4bff-a02e-1d990c36ca7f">Microsoft Visio 2003 Service Pack 3</a>
                    <br />(KB2434733)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Visio 2007 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=097a642b-b786-4724-a907-79f37cded836">Microsoft Visio 2007 Service Pack 2</a>
                    <br />(KB2434737)<br />(Viktig)</td></tr>
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

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse oppgaven med å levere og administrere oppdateringer til IT-systemer i hele bedriften. Med Configuration Manager 2007 kan IT-administratorer levere oppdateringer av Microsoft-produkter til en rekke enheter, inkludert stasjonære datamaskiner, bærbare datamaskiner, servere og mobile enheter.

Den automatiske sikkerhetsproblemvurderingen i Configuration Manager 2007 oppdager behov for oppdateringer og rapporterer om anbefalte handlinger. Software Update Management i Configuration Manager 2007 er bygd på Microsoft Windows Software Update Services (WSUS), en tidstestet oppdateringsinfrastruktur som er velkjent for IT-administratorer over hele verden. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke Configuration Manager 2007 til å distribuere oppdateringer, kan du se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Hvis du vil ha mer informasjon om Configuration Manager, kan du gå til [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne.

**Obs\!**  System Management Server 2003 har ikke vanlig kundestøtte etter 12. januar 2010. Hvis du vil ha mer informasjon om produktlivssykluser, kan du gå til [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den neste utgivelsen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se det tidligere avsnittet **System Center Configuration Manager 2007**.

Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du se [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Obs\!**  SMS bruker Microsoft Baseline Security Analyzer for å gi bred støtte i forbindelse med søking etter og distribusjon av sikkerhetsbulletinoppdateringer. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til å installere disse oppdateringene.

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

For å forbedre sikkerheten for kundene gir Microsoft store leverandører av sikkerhetsprogramvare informasjon om sikkerhetsproblemer før hver månedlige utgivelse av sikkerhetsoppdateringer. Leverandører av sikkerhetsprogramvare kan deretter bruke denne informasjonen om sikkerhetsproblemer til å oppdatere beskyttelsen til kundene via sikkerhetsprogramvaren eller -enhetene deres, som antivirusprogrammer, nettverksbaserte systemer for oppdaging av inntrengere eller vertsbaserte systemer for forhindring av inntrengere. Hvis du vil finne ut om det finnes aktiv beskyttelse tilgjengelig fra leverandører av sikkerhetsprogramvare, kan du gå til webområdene for aktiv beskyttelse fra programpartnerne som er oppført i artikkelen om [MAPP-programpartnere (Microsoft Active Protections Program)](http://www.microsoft.com/security/msrc/mapp/partners.mspx).

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

  - Yuki Chen hos [Trend Micro](http://www.trendmicro.com) for rapporten om et sikkerhetsproblem som beskrives i MS11-003
  - SkyLined hos [Google Inc.](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-003
  - Haifei Li hos [Fortinet’s FortiGuard Labs](http://www.fortiguard.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-003
  - Kobi Pariente og Yaniv Miron i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/), for rapporten om et sikkerhetsproblem som beskrives i MS11-006
  - Procyun i samarbeid med [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-008
  - Xin Ouyang hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS11-008
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-009
  - Sihan Qing (professor), Weiping Wen (førsteamanuensis), Liang Yin og Husheng Zhou (høyeregradsstudenter) hos [Instituttet for informasjonnsikkerhet ved universitetet i Beijing](http://www.ss.pku.edu.cn/en/) for rapporten om et sikkerhetsproblem som beskrives i MS11-010
  - Zhengwenbin hos [360safe](http://www.360.cn) for rapporten om et sikkerhetsproblem som beskrives i MS11-011
  - Guo Bojun for rapporten om et sikkerhetsproblem som beskrives i MS11-011
  - Wei Zhang for rapporten om et sikkerhetsproblem som beskrives i MS11-011
  - Marco Giuliani hos [Prevx](http://www.prevx.com/) for samarbeidet om et sikkerhetsproblem som beskrives i MS11-011
  - std\_logic i samarbeid med [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-011
  - Tarjei Mandt hos [Norman](http://www.norman.com) for rapporten om fem sikkerhetsproblemer som beskrives i MS11-012
  - [MIT Kerberos Team](http://web.mit.edu/kerberos) for rapporten om et sikkerhetsproblem som beskrives i MS11-013
  - Scott Stender hos [iSEC Partners Labs](http://www.isecpartners.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-013
  - Sikkerhetstester Jorge Moura hos Primavera BSS for rapporten om et sikkerhetsproblem som beskrives i MS11-014

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (8. februar 2011): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (9. februar 2010): For MS11-013 er utnyttelsesindeksvurderingen korrigert for CVE-2011-0091 til 3 – Fungerende skadelig kode er usannsynlig. Dette er bare en informasjonsendring.
  - V2.0 (8. mars 2011): Informasjon om den berørte programvaren Windows 7 for 32-biters systemer med Service Pack 1, Windows 7 for x64-baserte systemer med Service Pack 1, Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1 og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1 for MS11-003, MS11-004, MS11-007 og MS11-009. Les Vanlige spørsmål for oppdateringen hvis du vil ha mer informasjon.
  - V3.0 (16. mars 2011): Informasjon om den berørte programvaren Windows 7 for 32-biters systemer med Service Pack 1, Windows 7 for x64-baserte systemer med Service Pack 1, Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1 og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1 for MS11-013. Les Vanlige spørsmål for oppdateringen hvis du vil ha mer informasjon.
  - V4.0 (18. mars 2011): Informasjon om den berørte programvaren Windows 7 for 32-biters systemer med Service Pack 1, Windows 7 for x64-baserte systemer med Service Pack 1, Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1 og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1 for MS11-012. Les Vanlige spørsmål for oppdateringen hvis du vil ha mer informasjon.

*Built at 2014-04-18T01:50:00Z-07:00*

