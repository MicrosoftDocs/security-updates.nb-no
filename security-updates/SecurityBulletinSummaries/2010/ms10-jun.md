---
title: Sammendrag av Microsofts sikkerhetsbulletiner for juni 2010
TOCTitle: MS10-JUN
ms:assetid: ms10-jun
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms10-jun(v=Security.10)
ms:contentKeyID: 61315218
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for juni 2010

Publisert: 8. juni 2010 | Oppdatert: 13. september 2011

**Versjon:** 2.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i juni 2010.

I forbindelse med utgivelsen av bulletinene for juni 2010 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 3. juni 2010. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 9. juni 2010 kl. 11.00 stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for juni på webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer med dekomprimering av media kan tillate ekstern kjøring av kode (979902)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Windows. Disse sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget mediefil eller mottar spesiallaget direkteavspilt innhold fra et webområde eller et program som leverer webinnhold. En angriper som klarer å utnytte disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159">MS10-034</a></td>
<td style="border:1px solid black;"><strong>Kumulativ sikkerhetsoppdatering av kill bits for ActiveX (980195)</strong><br />
<br />
Denne sikkerhetsoppdateringen gjelder to personlig rapporterte sikkerhetsproblemer for Microsoft-programvare. Denne sikkerhetsoppdateringen har alvorlighetsgraden Kritisk for alle støttede versjoner av Microsoft Windows 2000, Windows XP, Windows Vista og Windows 7 og Moderat for alle støttede versjoner av Windows Server 2003, Windows Server2008 og Windows Server 2008 R2.<br />
<br />
Sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside som starter en bestemt ActiveX-kontroll med Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Denne oppdateringen inneholder også kill bits for fire tredjeparts ActiveX-kontroller.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (982381)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem i Internet Explorer. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Windows-kjernemodusdrivere kan tillate rettighetsutvidelse (979559)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to offentliggjorte sikkerhetsproblemer og ett personlig rapportert sikkerhetsproblem i Windows-kjernemodusdriverne. Sikkerhetsproblemene kan føre til rettighetsutvidelse hvis en bruker viser innhold gjengitt i en spesiallaget TrueType-skrift.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Rettighetsutvidelse</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem med COM-validering i Microsoft Office kan tillate ekstern kjøring av kode (983235)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem med COM-validering i Microsoft Office. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-, Word-, Vision-, Publisher- eller PowerPoint-fil med en berørt versjon av Microsoft Office. Sikkerhetsproblemet kan ikke utnyttes automatisk via e-post. For at et angrep skal lykkes, må brukeren åpne vedlegget som fulgte med e-posten.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i driver for OpenType Compact Font Format (CFF) kan tillate rettighetsutvidelse (980218)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i driveren for OpenType Compact Font Format (CFF). Sikkerhetsproblemet kan føre til rettighetsutvidelse hvis en bruker viser innhold gjengitt i en spesiallaget CFF-skrift. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte dette sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Rettighetsutvidelse</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (2027452)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser 14 personlig rapporterte sikkerhetsproblemer i Microsoft Office. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-fil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Microsoft SharePoint kan tillate rettighetsutvidelse (2028554)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ett offentliggjort sikkerhetsproblem og to personlig rapporterte sikkerhetsproblem i Microsoft SharePoint. Det mest alvorlige sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper overbeviser en bruker av et utvalgt SharePoint-område om å klikke en spesiallaget kobling.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Rettighetsutvidelse</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Server-programvare</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i IIS (Internet Information Services) kan tillate ekstern kjøring av kode (982666)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i IIS (Internet Information Services). Sikkerhetsproblemet kan tillate ekstern kjøring av kode dersom en bruker mottar en spesiallaget HTTP-forespørsel. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Microsoft .NET Framework kan tillate manipulering (981343)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem i Microsoft .NET Framework. Sikkerhetsproblemet kan tillate datamanipulering i signert XML-innhold uten at det oppdages. I egendefinerte programmer kommer innvirkningen på sikkerheten an på hvordan det signerte innholdet brukes i det bestemte programmet. Scenarioer der signerte XML-meldinger overføres via en sikker kanal (som SSL), berøres ikke av dette sikkerhetsproblemet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig!</a><br />
Manipulering</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført i synkende rekkefølge etter utnyttelsesvurderingsnivå og deretter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan bruker jeg denne tabellen?**  

Bruk denne tabellen til å få mer informasjon om sannsynligheten for at fungerende skadelig kode blir utgitt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Du bør se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-ID</th>
<th style="border:1px solid black;">Tittel på sikkerhetsproblem</th>
<th style="border:1px solid black;">CVE-ID</th>
<th style="border:1px solid black;">Utnyttelsesindeksvurdering</th>
<th style="border:1px solid black;">Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Win32k med vindusoppretting</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485">CVE-2010-0485</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med Help.aspx i XSS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817">CVE-2010-0817</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemet ble rapportert for første gang i <a href="microsoft-security-advisory-983438.md">Microsofts sikkerhetsveiledning 983438</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel som kan føre til stakkoverflyt for objekt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822">CVE-2010-0822</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel-poster som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824">CVE-2010-0824</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel-poster som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245">CVE-2010-1245</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel RTD som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246">CVE-2010-1246</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247">CVE-2010-1247</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel HFPicture som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248">CVE-2010-1248</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249">CVE-2010-1249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel EDG som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250">CVE-2010-1250</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel ADO-objekter</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253">CVE-2010-1253</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med Open XML-tillatelser med Office for Mac</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254">CVE-2010-1254</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259">CVE-2010-1259</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262">CVE-2010-1262</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med COM-validering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263">CVE-2010-1263</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med mediedekomprimering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879">CVE-2010-1879</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon på tvers av domener</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255">CVE-2010-0255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemet ble rapportert for første gang i <a href="microsoft-security-advisory-980088.md">Microsofts sikkerhetsveiledning 980088</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Win32k med utilstrekkelig datavalidering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484">CVE-2010-0484</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med driver for OpenType-skrifter i CCF-format som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819">CVE-2010-0819</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem som kan føre til minnefeil ved analyse av Excel-poster</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821">CVE-2010-0821</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823">CVE-2010-0823</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel-poster som kan føre til stakkfeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251">CVE-2010-1251</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel på grunn av strengvariabel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252">CVE-2010-1252</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Win32k med analysering av TrueType-skrift</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255">CVE-2010-1255</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med IIS- godkjenning som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256">CVE-2010-1256</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med mediedekomprimering av MJPEG</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880">CVE-2010-1880</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med XML-signatur som kan føre til omgåing av godkjenning ved HMAC-trunkering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217">CVE-2009-0217</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som er kan føre til etterligningsangrep og manipulering</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med toStaticHTML som kan føre til tilgjengeliggjøring av informasjon</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257">CVE-2010-1257</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemer berører også <a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med toStaticHTML som kan føre til tilgjengeliggjøring av informasjon</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257">CVE-2010-1257</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemer berører også <a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i hjelpen for SharePoint som kan føre til tjenestenekt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264">CVE-2010-1264</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
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
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="8" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a">Quartz.dll (DirectShow) (DirectX 9)</a>
                    [1]
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2">Windows Media Format Runtime 9</a>[2]<br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527">Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Ingen alvorlighetsgrad)[1]<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7">Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB979909)<br />(Viktig)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br />Bare Windows XP Service Pack 2:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3">Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 og Windows Media Format Runtime 11</a><br />(KB978695)<br />(Kritisk)<br /><br />Bare Windows XP Service Pack 3:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085">Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 og Windows Media Format Runtime 11</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Bare Windows XP Media Center Edition 2005: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394">Microsoft .NET Framework 1.0 Service Pack 3</a><br />(KB979904) <br />(Viktig)<br /><br />Bare Windows XP Media Center Edition 2005 og Windows XP Tablet PC Edition 2005: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394">Microsoft .NET Framework 1.0 Service Pack 3</a><br />(KB979904)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB979906)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET 3.5 Service Pack 1</a><br />(KB979909)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2">Windows Media Format Runtime 9.5</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555">Windows Media Format Runtime 9.5 x64 Edition</a>[3]<br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc">Windows Media Format Runtime 11</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7">Windows Media Encoder 9 x64</a><br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB979909)<br />(Viktig)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5">Windows Media Format Runtime 9.5</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f">Internet Explorer 8</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d">Internet Information Services 6.0</a>
                    [1]
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979907)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979909)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163">Windows Media Format Runtime 9.5</a><br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555">Windows Media Format Runtime 9.5 x64 Edition</a>[3]<br />(KB978695)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7">Windows Media Encoder 9 x64</a><br />(KB979332)<br />(Viktig)<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7"><br /><br />Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4">Internet Explorer 8</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312">Internet Information Services 6.0</a>
                    [1]
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979909)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 SP2 for Itanium-baserte systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8">Windows Server 2003 med SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c">Quartz.dll (DirectShow)</a>
                    <br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f34bc115-022b-46b0-9517-806bd0fc73c5">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8">Windows Server 2003 med SP2 for Itanium-baserte systemer</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e">Internet Explorer 7</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1">Windows Server 2003 med SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig!)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea">Internet Information Services 6.0</a>
                    [1]
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9">Microsoft .NET Framework 3.5</a><br />(KB982865)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979909)<br />(Viktig)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Bare Windows Vista Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b64107f2-990a-42df-a75a-5bf371709fd6">Quartz.dll (DirectShow)</a><br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1">Internet Information Services 7.0</a>
                    [1]
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Viktig)<br /><br />Bare Windows Vista Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB979913)<br />(Viktig)<br /><br />Bare Windows Vista Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979911)<br />(Viktig)<br /><br />Bare Windows Vista Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a> (KB979910)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Bare Windows Vista x64 Edition Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0754addb-2f04-45c9-8594-174b8b8b297c">Quartz.dll (DirectShow)</a><br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9f033f6-f587-494d-b968-1316f1deed06">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f">Windows Media Encoder 9 x86</a><br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33">Windows Media Encoder 9 x64</a><br />(KB979332)<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f">Internet Information Services 7.0</a>
                    [1]
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Viktig)<br /><br />Bare Windows Vista x64 Edition Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB979913)<br />(Viktig)<br /><br />Bare Windows Vista x64 Edition Service Pack 1: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979911) <br />(Viktig)<br /><br />Bare Windows Vista x64 Edition Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979910)<br />(Viktig)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td style="border:1px solid black;">Bare Windows Server 2008 for 32-biters systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18fd814b-51f3-470b-a5bd-97be752298d9">Quartz.dll (DirectShow)</a>**<br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e">Asycfilt.dll (COM-komponent)</a>*<br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171">Windows Media Encoder 9 x86</a>**<br />(KB979332)<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385">Internet Explorer 8</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d">Internet Information Services 7.0</a>*[1]<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB979906)<br />(Viktig)<br /><br />Bare Windows Server 2008 for 32-biters systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB979913)<br />(Viktig)<br /><br />Bare Windows Server 2008 for 32-biters systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB979911)<br />(Viktig)<br /><br />Bare Windows Server 2008 for 32-biters systemer med Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB979910)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td style="border:1px solid black;">Bare Windows Server 2008 for x64-baserte systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731">Quartz.dll (DirectShow)</a>**<br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c">Asycfilt.dll (COM-komponent)</a>*<br />(KB979482)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6">Windows Media Encoder 9 x86</a>**<br />(KB979332)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3">Windows Media Encoder 9 x64</a>**<br />(KB979332)<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91">Internet Explorer 8</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706">Internet Information Services 7.0</a>*[1]<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>**<br />(KB979906)<br />(Viktig)<br /><br />Bare Windows Server 2008 for x64-baserte systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB979913)<br />(Viktig)<br /><br />Bare Windows Server 2008 for x64-baserte systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB979911)<br />(Viktig)<br /><br />Bare Windows Server 2008 for x64-baserte systemer med Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB979910)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Bare Windows Server 2008 for Itanium-baserte systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=120c68f5-4575-4e2a-912a-eed52736c403">Quartz.dll (DirectShow)</a><br />(KB975562)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e5753ab-848d-475f-917d-ba70f70b65f5">Asycfilt.dll (COM-komponent)</a><br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35">Internet Explorer 7</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913">Internet Information Services 7.0</a>
                    [1]
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB979906)<br />(Viktig)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB979913)<br />(Viktig)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979911)<br />(Viktig)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer med Service Pack 2: <br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB979910)<br />(Viktig)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 for 32-biters systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772">Asycfilt.dll (COM-komponent)</a>
                    <br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00">Windows 7 for 32-biters systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495">Internet Information Services 7.5</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB979916)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 for x64-baserte systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54">Asycfilt.dll (COM-komponent)</a>
                    <br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43">Windows 7 for x64-baserte systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595">Internet Information Services 7.5</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB979916)<br />(Viktig)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=184917">
                      <strong>MS10-032</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191065">
                      <strong>MS10-033</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185159">
                      <strong>MS10-034</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190898">
                      <strong>MS10-035</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190508">
                      <strong>MS10-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191788">
                      <strong>MS10-040</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=185042">
                      <strong>MS10-041</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 for x64-baserte systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330">Asycfilt.dll (COM-komponent)</a>*<br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77">Windows Server 2008 R2 for x64-baserte systemer</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0">Internet Explorer 8</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa">Internet Information Services 7.5</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>*<br />(KB979916)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 for Itanium-baserte systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f">Windows Server 2008 R2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937">Asycfilt.dll (COM-komponent)</a>
                    <br />(KB979482)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694">Windows Server 2008 R2 for Itanium-baserte systemer</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d">Internet Explorer 8</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f">Windows Server 2008 R2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd">Internet Information Services 7.5</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB979916)<br />(Viktig)</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Du finner mer informasjon om dette installasjonsalternativet, kan du se MSDN-artiklene [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet, kan du se MSDN-artiklene [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS10-033**

\[1\]Oppdateringen for Quartz.dll (Direct Show) (DirectX 9) gjelder også for DirectX 9.0a, DirectX 9.0b og DirectX 9.0c.

\[2\]Denne oppdateringspakken gjelder for Windows Media Format 9 SDK Runtime på Microsoft Windows 2000 med oppdateringen for DRM-aktiverte medieavspillere (KB891122). Hvis du vil ha mer informasjon, kan du se [Microsoft Knowledge Base-artikkel 974316](http://support.microsoft.com/kb/974316).

\[3\]Hvis du har installert Windows Media Format Runtime 9.5 x64 Edition, må du installere sikkerhetsoppdateringene for Windows Media Format Runtime 9.5 og Windows Media Format Runtime 9.5 x64 Edition for å være fullstendig beskyttet mot sikkerhetsproblemene som omtales i MS10-033.

**Merknad for MS10-035**

\[1\]Alvorlighetsgrader gjelder ikke for denne oppdateringen fordi sikkerhetsproblemene som omtales i denne bulletinen, ikke påvirker denne programvaren. Denne oppdateringen tilbys imidlertid for å rette opp i et regresjonsproblem fra [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979). Se [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) for mer detaljert informasjon.

**Merknad for MS10-040**

\[1\]Dette operativsystemet berøres bare når Utvidet beskyttelse for godkjenning er installert. Se [Microsoft Knowledge Base-artikkel 973917](http://support.microsoft.com/kb/973917).

#### Microsoft Office-serier og -programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office-serier, -systemer og -komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190554">
                      <strong>MS10-036</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191053">
                      <strong>MS10-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
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
                <tr><td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td><td style="border:1px solid black;">Microsoft Office XP Service Pack 3[1]<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB982299)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3">Microsoft Office 2003 Service Pack 3</a>
                    <br />(KB982311)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1">Microsoft Office Excel 2003 Service Pack 3</a>[2]<br />(KB982133)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc">Microsoft Office PowerPoint 2003 Service Pack 3</a>[2]<br />(KB982157)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4">Microsoft Office Publisher 2003 Service Pack 3</a>[2]<br />(KB982122)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a">Microsoft Office Visio 2003 Service Pack 3</a>[2]<br />(KB982126)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245">Microsoft Office Word 2003 Service Pack 3</a>[2]<br />(KB982134)<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB982133)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167">2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</a>
                    <br />(KB982312)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec">Microsoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2</a>[3]<br />(KB982308)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a">Microsoft Office PowerPoint 2007 Service Pack 1 og Microsoft Office PowerPoint 2007 Service Pack 2</a>[3]<br />(KB982158)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65">Microsoft Office Publisher 2007 Service Pack 1 og Microsoft Office Publisher 2007 Service Pack 2</a>[3]<br />(KB982124)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b">Microsoft Office Visio 2007 Service Pack 1 og Microsoft Office Visio 2007 Service Pack 2</a>[3]<br />(KB982127)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755">Microsoft Office Word 2007 Service Pack 1 og Microsoft Office Word 2007 Service Pack 2</a>[3]<br />(KB982135)<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec">Microsoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2</a>
                    [1]
                    <br />(KB982308)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Microsoft Office for Mac</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190554">
                      <strong>MS10-036</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191053">
                      <strong>MS10-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2004 for Mac</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125">Microsoft Office 2004 for Mac</a>
                    <br />(KB2028866)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2008 for Mac</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd">Microsoft Office 2008 for Mac</a>
                    <br />(KB2028864)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Open XML File Format Converter for Mac</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528">Open XML File Format Converter for Mac</a>
                    <br />(KB2078051)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="4" style="border:1px solid black;">Annen Office-programvare</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=190554">
                      <strong>MS10-036</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191053">
                      <strong>MS10-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Excel Viewer Service Pack 1 og Microsoft Office Excel Viewer Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a">Microsoft Office Excel Viewer Service Pack 1 og Microsoft Office Excel Viewer Service Pack 2</a>
                    <br />(KB982333)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Compatibility Pack Service Pack 1 for filformater for Word, Excel og PowerPoint 2007 og Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0">Microsoft Office Compatibility Pack Service Pack 1 for filformater for Word, Excel og PowerPoint 2007 og Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB982331)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office InfoPath 2003 Service Pack 3</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336">Microsoft Office InfoPath 2003 Service Pack 3</a>
                    <br />(KB980923)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office InfoPath 2007 Service Pack 1 og Microsoft Office InfoPath 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6">Microsoft Office InfoPath 2007 Service Pack 1 og Microsoft Office InfoPath 2007 Service Pack 2</a>
                    <br />(KB979441)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007 Service Pack 1 og Microsoft Office SharePoint Server 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df">Microsoft Office SharePoint Server 2007 Service Pack 1 (32-biters versjoner)</a>
                    [1]
                    <br />(KB979445)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-biters versjoner)</a>[1]<br />(KB979445)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90">Microsoft Office SharePoint Server 2007 Service Pack 1 (64-biters versjoner)</a>[1]<br />(KB979445)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-biters versjoner)</a>[1]<br />(KB979445)<br />(Viktig)</td></tr>
              </table>


**Merknader for MS10-036**

\[1\]Ingen tilgjengelig oppdatering. Se bulletinen hvis du vil ha mer informasjon.

\[2\]I tillegg til denne oppdateringen må kunder også installere oppdateringen for Microsoft Office 2003 Service Pack 3 (KB982311) for å være beskyttet mot sikkerhetsproblemet som beskrives i denne bulletinen.

\[3\]I tillegg til denne oppdateringen må kunder også installere oppdateringen for 2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2 (KB982312) for å være beskyttet mot sikkerhetsproblemet som beskrives i denne bulletinen.

**Merknad for MS10-038**

\[1\]I tillegg til denne oppdateringen må kunder også installere sikkerhetsoppdateringen for Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007 Service Pack 1 og Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007 Service Pack 2 (KB982308) for å beskytte seg mot sikkerhetsproblemene som beskrives i denne bulletinen.

**Merknader for MS10-039**

\[1\]For støttede versjoner av Microsoft Office SharePoint Server 2007 må kunder også installere sikkerhetsoppdateringen for Microsoft Windows SharePoint Services 3.0 (KB983444) i tillegg til sikkerhetsoppdateringspakken KB979445 for å være beskyttet mot sikkerhetsproblemene som beskrives i denne bulletinen.

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Microsoft Server-programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="" style="border:1px solid black;">Windows SharePoint Services</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=191905">
                      <strong>MS10-039</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows SharePoint Services 3.0 Service Pack 1 og Microsoft Windows SharePoint Services 3.0 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783">Microsoft Windows SharePoint Services 3.0 Service Pack 1 og Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-biters versjoner)</a>
                    <br />(KB983444)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f">Microsoft Windows SharePoint Services 3.0 Service Pack 1 og Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-biters versjoner)</a><br />(KB983444)<br />(Viktig)</td></tr>
              </table>


**Merknad for MS10-039**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Obs\!** Fra og med 1. august 2009 tilbyr ikke lenger Microsoft støtte for Office Update og Office Update Inventory Tool. Hvis du vil fortsette å få de nyeste oppdateringene for Microsoft Office-produkter, kan du bruke [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Hvis du vil ha mer informasjon, kan du se [Om Microsoft Office Update: Vanlige spørsmål](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Veiledning for søking og distribusjon**

Microsoft tilbyr veiledning for søking etter og distribusjon av sikkerhetsoppdateringer. Denne veiledningen inneholder anbefalinger og informasjon som kan hjelpe IT-eksperter med å forstå hvordan ulike verktøy for søking etter og distribusjon av sikkerhetsoppdateringer skal brukes. Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Med Windows Server Update Services (WSUS) kan administratorer raskt og trygt distribuere de nyeste kritiske oppdateringene og sikkerhetsoppdateringene for Microsoft Windows 2000 og nyere operativsystemer, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne. Den neste versjonen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du gå til [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brukere kan også bruke Security Update Inventory Tool (SUIT) som en hjelp til å distribuere sikkerhetsoppdateringer. Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer for å gi bred støtte i forbindelse med søking etter og distribusjon av sikkerhetsbulletinoppdateringer. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validering av Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

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

  - Sebastien Renaud hos [VUPEN Vulnerability Research Team](http://www.vupen.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-032
  - [Secunia Research](http://secunia.com/) for samarbeidet i forbindelse med et problem som beskrives i MS10-032
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS10-033
  - Shaun Colley hos [NGS Software](http://www.ngssoftware.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-034
  - Chris Ries hos Carnegie Mellon University Computing Services for rapporten om et sikkerhetsproblem som beskrives i MS10-034
  - Chris Weber hos [Casaba Security](http://www.casabasecurity.com/) for rapporten om et sikkerhetsproblem beskrevet i MS10-035 og MS10-039
  - Takeshi Terada hos [Mitsui Bussan Secure Directions, Inc.](http://www.mbsd.jp/) for rapporten om et sikkerhetsproblem som beskrives i MS10-035
  - Michal Zalewski hos [Google Inc.](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-035
  - Chris Rohlf hos [Matasano Security](http://www.matasano.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS10-035
  - Peter Vreugdenhil i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-035
  - David Dewey hos [IBM ISS X-Force](http://www.iss.net/) og Ryan Smith hos [Accuvant](http://www.accuvant.com/), tidligere hos [VeriSign iDefense Labs](http://labs.idefense.com/), for samarbeidet i forbindelse med forandringene i dybdeforsvar som er inkludert i MS10-036
  - Chris Carton hos Laserforce International, i samarbeid med [Secunia](http://secunia.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-037
  - En anonym forsker, i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-038
  - Nicolas Joly hos [VUPEN Vulnerability Research Team](http://www.vupen.com/) for rapporten om åtte sikkerhetsproblemer som beskrives i MS10-038
  - Bing Liu hos [Fortinets FortiGuard Labs](http://www.fortiguard.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-038.
  - Carsten Eiram hos [Secunia](http://secunia.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS10-038
  - En anonym forsker, i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-038
  - Rick Glaspie hos Gilbert Public Schools i Gilbert, Arizona for rapporten om et sikkerhetsproblem som beskrives i MS10-038
  - Rik Jones hos Dallas County Community College District for rapporten om et sikkerhetsproblem som beskrives i MS10-039
  - Arian Evans hos [WhiteHat Security](http://www.whitehatsec.com) for rapporten om omgåingssikkerhetsproblemet i ASP.NET ved validering av forespørsler som behandles i MS10-041 gjennom en endring i dybdeforsvaret

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (8. juni 2010): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (9. juni 2010): Reviderte merknadene for MS10-033 i delen **Berørt programvare og nedlastingssteder**.
  - V2.0 (13. september 2011): Bulletinen MS10-035 publisert på nytt for å tilby oppdateringen på nytt for Internet Explorer på Microsoft Windows 2000 og Windows XP for å løse et gjenkjenningsproblem. Det var ingen endringer i filer for sikkerhetsoppdateringen. Kunder som allerede har gjennomført en vellykket oppdatering av systemene, trenger ikke å gjøre noe.

*Built at 2014-04-18T01:50:00Z-07:00*

