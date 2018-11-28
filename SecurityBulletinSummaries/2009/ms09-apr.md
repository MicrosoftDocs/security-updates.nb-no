---
title: Sammendrag av Microsofts sikkerhetsbulletiner for april 2009
TOCTitle: MS09-APR
ms:assetid: ms09-apr
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms09-apr(v=Security.10)
ms:contentKeyID: 61315200
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for april 2009

Publisert: 14. april 2009 | Oppdatert: 16. april 2009

**Versjon:** 1.1

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i april 2009.

I forbindelse med utgivelsen av bulletinene for april 2009 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 9. april 2009. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 15. april 2009 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for april på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395126). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td><strong>Sikkerhetsproblemer i WordPad og tekstkonverteringsprogrammer for Office kan tillate ekstern kjøring av kode (960477)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to offentliggjorte sikkerhetsproblemer og to personlig rapporterte sikkerhetsproblemer i Microsoft WordPad og tekstkonverteringsprogrammer for Microsoft Office. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en spesiallaget fil åpnes i WordPad eller Microsoft Office Word. Ikke åpne Microsoft Office-, RTF-, Write- eller WordPerfect-filer fra ikke-klarerte kilder som bruker berørte versjoner av WordPad eller Microsoft Office Word.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows, Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td><strong>Sikkerhetsproblemer i Windows HTTP-tjenester kan tillate ekstern kjøring av kode (960803)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ett offentliggjort sikkerhetsproblem og to personlig rapporterte sikkerhetsproblemer i Microsoft Windows HTTP-tjenester (WinHTTP). Det mest alvorlige sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139107">MS09-011</a></td>
<td><strong>Sikkerhetsproblem i Microsoft DirectShow kan tillate ekstern kjøring av kode (961373)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft DirectX. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker åpnet en spesiallaget MJPEG-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (963027)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fire personlig rapporterte sikkerhetsproblemer og to offentliggjorte sikkerhetsproblemer i Internet Explorer. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside i Internet Explorer eller hvis en bruker kobles til serveren til en angriper via HTTP-protokollen. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143568">MS09-009</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (968557)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem og et offentliggjort sikkerhetsproblem i Microsoft Office Excel. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis brukeren åpnet en spesiallaget Excel-fil. En angriper som klarer å utnytte disse sikkerhetsproblemene, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td><strong>Sikkerhetsproblemer i Windows kan tillate rettighetsutvidelse (959454)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fire offentliggjorte sikkerhetsproblemer i Microsoft Windows. Sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en angriper kan logge seg på systemet og kjøre et spesiallaget program. Angriperen må kunne kjøre kode på den lokale maskinen for å utnytte dette sikkerhetsproblemet. En angriper som klarer å utnytte et av disse sikkerhetsproblemene, kan få full kontroll over det berørte systemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141639">MS09-016</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft ISA Server og Forefront Threat Management Gateway (Medium Business Edition) kan forårsake tjenestenekt (961759)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem og et offentliggjort sikkerhetsproblem i Microsoft Internet Security and Acceleration (ISA) Server og Microsoft Forefront Threat Management Gateway (TMG), Medium Business Edition (MBE). Disse sikkerhetsproblemene kan forårsake tjenestenekt hvis en angriper sender spesiallagde nettverkspakker til det berørte systemet eller tilgjengeliggjøring av informasjon hvis en bruker klikker en skadelig URL-adresse eller besøker et webområde med innhold som kontrolleres av angriperen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td>Krever omstart</td>
<td>Microsoft Forefront Edge Security</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146803">MS09-015</a></td>
<td><strong>Sikkerhetsproblem med blandet trussel i SearchPath kan tillate rettighetsutvidelse (959426)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem i Windows SearchPath-funksjonen som kan tillate rettighetsutvidelse hvis en bruker laster ned en spesiallaget fil til en bestemt plassering og deretter åpner et program som kan laste filen under bestemte forhold.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført etter bulletin-ID og CVE-ID.

**Hvordan bruker jeg denne tabellen?**

Bruk denne tabellen til å få mer informasjon om sannsynligheten for at fungerende skadelig kode blir utgitt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Du bør se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Bulletintittel</th>
<th>CVE-ID</th>
<th>Utnyttelsesindeksvurdering</th>
<th>Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143568">MS09-009</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (968557)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0100">CVE-2009-0100</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143568">MS09-009</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (968557)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0238">CVE-2009-0238</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td>Sikkerhetsproblemer i WordPad og tekstkonverteringsprogrammer for Office kan tillate ekstern kjøring av kode (960477)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4841">CVE-2008-4841</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td>Sikkerhetsproblemer i WordPad og tekstkonverteringsprogrammer for Office kan tillate ekstern kjøring av kode (960477)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0087">CVE-2009-0087</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>Dette er et komplisert sikkerhetsproblem på grunn av flere kodebaner. De fleste forekomster av skadelig kode vil føre til inkonsekvente resultater. Standard begrensende faktorer beskytter mot denne vektoren.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td>Sikkerhetsproblemer i WordPad og tekstkonverteringsprogrammer for Office kan tillate ekstern kjøring av kode (960477)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0088">CVE-2009-0088</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet kan utnyttes, men det berører bare eldre versjoner og et eldre, uvanlig filformat. Nyere versjoner som 2007 Microsoft Office system og Microsoft Office 2003 Service Pack 3 berøres ikke.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139849">MS09-010</a></td>
<td>Sikkerhetsproblemer i WordPad og tekstkonverteringsprogrammer for Office kan tillate ekstern kjøring av kode (960477)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0235">CVE-2009-0235</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet som kan forårsake minnefeil, kan enkelt utnyttes.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139107">MS09-011</a></td>
<td>Sikkerhetsproblem i Microsoft DirectShow kan tillate ekstern kjøring av kode (961373)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0084">CVE-2009-0084</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td>Sikkerhetsproblemer i Windows kan tillate rettighetsutvidelse (959454)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-1436">CVE-2008-1436</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td>Sikkerhetsproblemer i Windows kan tillate rettighetsutvidelse (959454)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0078">CVE-2009-0078</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td>Sikkerhetsproblemer i Windows kan tillate rettighetsutvidelse (959454)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0079">CVE-2009-0079</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=132587">MS09-012</a></td>
<td>Sikkerhetsproblemer i Windows kan tillate rettighetsutvidelse (959454)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0080">CVE-2009-0080</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td>Sikkerhetsproblemer i Windows HTTP-tjenester kan tillate ekstern kjøring av kode (960803)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0086">CVE-2009-0086</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>På grunn av utbredt bruk av denne teknologien kan dette sikkerhetsproblemet som kan forårsake minnefeil, enkelt kontrolleres, og det har flere angrepsvektorer og muligheter for utnyttelse.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td>Sikkerhetsproblemer i Windows HTTP-tjenester kan tillate ekstern kjøring av kode (960803)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0089">CVE-2009-0089</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139852">MS09-013</a></td>
<td>Sikkerhetsproblemer i Windows HTTP-tjenester kan tillate ekstern kjøring av kode (960803)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550">CVE-2009-0550</a>**</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Skadelig kode har blitt offentliggjort.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (963027)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540">CVE-2008-2540</a>*</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Detaljer om angrepet er offentliggjort, men det finnes for tiden ingen kjente angrepsvektorer for dette sikkerhetsproblemet. For at dette sikkerhetsproblemet skal kunne utnyttes, må en angriper og brukeren utføre en rekke kompliserte trinn, inkludert å lagre bestemte filer på skrivebordet.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (963027)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0550">CVE-2009-0550</a>**</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Skadelig kode har blitt offentliggjort.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (963027)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0551">CVE-2009-0551</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (963027)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0552">CVE-2009-0552</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Begrensende faktorer for Internet Explorer 7 forhindrer kjøring av kode. Internet Explorer 6 og tidligere versjoner er mer utsatt for å bli utnyttet hvis de ikke er oppdatert med alle sikkerhetsoppdateringer.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (963027)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0553">CVE-2009-0553</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146659">MS09-014</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (963027)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0554">CVE-2009-0554</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=146803">MS09-015</a></td>
<td>Sikkerhetsproblem med blandet trussel i SearchPath kan tillate rettighetsutvidelse (959426)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-2540">CVE-2008-2540</a>*</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>Detaljer om angrepet er offentliggjort, men det finnes for tiden ingen kjente angrepsvektorer for dette sikkerhetsproblemet. For at dette sikkerhetsproblemet skal kunne utnyttes, må en angriper og brukeren utføre en rekke kompliserte trinn, inkludert å lagre bestemte filer på skrivebordet.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141639">MS09-016</a></td>
<td>Sikkerhetsproblemer i Microsoft ISA Server og Forefront Threat Management Gateway (Medium Business Edition) kan forårsake tjenestenekt (961759)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0077">CVE-2009-0077</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Tjenestebasert tjenestenekt er svært sannsynlig. Det er imidlertid ikke mulig med kjøring av kode.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141639">MS09-016</a></td>
<td>Sikkerhetsproblemer i Microsoft ISA Server og Forefront Threat Management Gateway (Medium Business Edition) kan forårsake tjenestenekt (961759)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-0237">CVE-2009-0237</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Tilgjengeliggjøring av informasjon er mulig. Kjøring av kode er svært usannsynlig.</td>
</tr>
</tbody>
</table>


\*Disse to sikkerhetsproblemene, som er tildelt samme CVE-nummer, er omtalt i to sikkerhetsoppdateringer. Du finner mer informasjon i de respektive bulletinene.

\*\*Disse to sikkerhetsproblemene, som er tildelt samme CVE-nummer, er omtalt i to sikkerhetsoppdateringer. Du finner mer informasjon i de respektive bulletinene.

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
  </tr>
                <tr><th colspan="7">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>(Ingen alvorlighetsgrad)</td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=552d322a-5282-42c7-9c1e-1d8c494a7318">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(KB923561)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39d5468e-5733-4c3e-9e75-3adac8ac8cb9">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ec5b7c7-13d3-467a-b24e-3cc6fb47adf6">DirectX 8,1</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b98ed5c-a3ab-45a7-a61e-349eae304bc6">DirectX 9.0</a>***<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7799fd05-5b26-449f-8a14-50227c9164d1">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87f0c380-5c31-4099-a6a9-c12f9d69b03b">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52b756e7-636f-4d9e-8a17-dbf467bfbe4d">Microsoft Windows 2000 Service Pack 4</a><br />(KB952004)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4e408d7-6716-4a12-ad3a-8029667f5c84">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Ingen alvorlighetsgrad)</td></tr>
              
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50a8519a-503e-43dd-a78a-c1bc764fd213">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(KB923561)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35af4151-1858-4c9a-85e4-9ff45feca1a4">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feb5d821-f210-40e8-b1aa-2ca3170df8df">DirectX 9.0</a>***<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=052c29fc-e8df-402c-9ab1-1079bc738e1b">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55d6729a-9f96-4da4-b564-676c0a0c9390">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90fe715e-8190-43e9-9c43-df5be564d923">Windows XP Service Pack 2 og Windows XP Service Pack 3</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73d2324f-be59-4b0c-b1ac-9876a13c2c03">Windows XP Service Pack 2 og Windows XP Service Pack 3</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3de0684d-605c-489b-bdc7-08bce9b2d4f6">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB923561)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49b16f0f-f6c3-4ca8-8041-392f4f7b5bbb">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1be8b7c-4874-4342-99b3-76ff725fbb9a">DirectX 9.0</a>***<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84c62211-2e82-4ccc-9f9b-26462b026d86">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=191c2f20-89ae-4e1c-bdd4-24b4abfe6b6c">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a794c32a-9a0c-47d9-9c57-ff5d4a8e4944">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b2f12ae5-0e46-47e1-ac5b-93550d030189">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b743a7fe-7bf4-420d-a72e-39471e5659fa">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2233a4d2-7c8a-4c89-b020-100d9afb43c8">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(KB923561)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42509f5a-d0f9-444a-9445-5eabdb555011">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1b4cd76-1dd6-43fa-bb9a-20c428985bfd">DirectX 9.0</a>***<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f73a3669-c17f-4b18-8456-96cb7d52ed86">Microsoft Internet Explorer 6</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a45dbd0-0520-4d9b-b76e-3f5109dd310d">Windows Internet Explorer 7</a><br />(Viktig)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25adec10-db8c-4cac-bf74-2c784678150a">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=42aba890-8b76-4c5a-8fb6-609797d19831">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=992bb0cd-fbc7-4a7c-9088-f7f9d9a3ead0">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=323f4211-5add-4e02-bce1-e5a1b489982c">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB923561)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7373ea32-bc2e-49f1-8b9f-4eeda5acc74c">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0e1e1db-94a5-451c-ab11-6b431fa065f1">DirectX 9.0</a>***<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03a9d581-2bd5-4151-9826-17b96e16f606">Microsoft Internet Explorer 6</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60ccc1d6-ea31-420c-b630-d7878a8dc527">Windows Internet Explorer 7</a><br />(Viktig)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b014c399-f404-4cb2-8f9d-864df382efeb">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0609f65-82d9-4d82-9f48-f3266e8de123">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f0a58e8c-7d63-4d7d-ba95-b3787cf408f0">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e840b9cb-f1f4-482a-aa07-eb6b42b477c4">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a>
                    <br />(KB923561)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05e33cc5-cff6-4c71-be71-285f66a95e01">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f36c215-fa8a-40c2-b680-6b1fece03b8d">DirectX 9.0</a>***<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53d13c07-80b0-4f05-b372-a2dac17e6157">Microsoft Internet Explorer 6</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0abaa2fb-7c4f-4149-993d-1575888bfc84">Windows Internet Explorer 7</a><br />(Viktig)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ada372b-ba17-433e-b022-d2c57b35af8a">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fda8837c-e5d2-4489-9b44-4c24a1102e77">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=00c6479d-f81f-445d-b8e4-7b71d77d540a">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Vista og Windows Vista Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f071d770-3b6b-4040-9911-d4de8cde4c68">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d743849d-f3b5-4114-adef-ade2716d55ac">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f111b99a-e555-4f29-8d1f-e9ec03d5cf1f">Windows Vista og Windows Vista Service Pack 1</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0ea1598-45cb-4c79-8945-caae98969675">Windows Vista og Windows Vista Service Pack 1</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b672d45-f33b-4edc-9f22-2f2c8c726a8b">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ceef2d0-f316-48d1-aecc-d74f91cc5e1f">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d191c8dc-a965-4a6a-b6d8-1470505eb55f">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa153bdc-6b48-4df2-9e5e-abacd6da782c">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dd82f4b-bb33-41ec-90a7-9ef91329b240">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7576e7d5-5bb1-4a53-b568-1ee0500ce721">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139852">
                      <strong>MS09-013</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139107">
                      <strong>MS09-011</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146659">
                      <strong>MS09-014</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=132587">
                      <strong>MS09-012</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=146803">
                      <strong>MS09-015</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-biters systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c36548f-c8c9-4318-91e2-9e0501339548">Windows Server 2008 for 32-biters systemer</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2c6313c-3ba9-4f7c-b259-b4582a390146">Windows Internet Explorer 7</a>**<br />(Viktig)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e3c7b52-65a7-42fb-beb5-1b374934737f">Windows Server 2008 for 32-biters systemer</a>*<br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d58702af-bbf8-4f1b-ae72-ced9ef23d581">Windows Server 2008 for 32-biters systemer</a>*<br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b73cf5e-66fe-4b7d-95fc-91a1c262c1e5">Windows Server 2008 for 32-biters systemer</a>*<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-baserte systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1c3f0997-a8a9-4340-ae0c-2c4d6792c65c">Windows Server 2008 for x64-baserte systemer</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebbade9d-704c-440b-8796-6d64225ac01a">Windows Internet Explorer 7</a>**<br />(Viktig)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eebb4d4d-29d2-4247-8cbb-63a3b17585ec">Windows Server 2008 for x64-baserte systemer</a>*<br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20bf4e9b-909b-4bc3-ae43-322d74a4f1c3">Windows Server 2008 for x64-baserte systemer</a>*<br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e60847c-b341-4c38-bc25-2e3cf2d4ae14">Windows Server 2008 for x64-baserte systemer</a>*<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0885b3b0-b78e-4980-902d-dff3886bcaac">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b04aa6f-b787-4122-bf82-0d150618fe7a">Windows Internet Explorer 7</a>
                    <br />(Viktig)</td><td>Oppdatering av MSDTC-transaksjonsverktøy:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc383c24-b0f6-47c1-9e89-6a378b09e82f">Windows Server 2008 for Itanium-based Systems</a><br />(KB952004)<br />(Viktig)<br /><br />Oppdatering av Windows-tjenesteisolering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bcc2b18f-67db-4109-a9f4-764f985423ee">Windows Server 2008 for Itanium-based Systems</a><br />(KB956572)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de1c2b4b-af47-4b9a-8363-720e5527573c">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Moderat)</td></tr>
              </table>


**Merknader for Windows Server 2008**

**\*Server Core-installasjonen av Windows Server 2008 berørt.** For støttede versjoner av Windows Server 2008 gjelder denne oppdateringen (med samme alvorlighetsgrad) enten Windows Server 2008 ble installert med installasjonsalternativet for Server Core eller ikke. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen av Windows Server 2008 ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 hvis Windows Server 2008 ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS09-010**

Se også delen **Microsoft Office-serier og -programvare** hvis du vil ha mer informasjon om flere oppdateringsfiler. Denne bulletinen dekker både Windows-operativsystemer og -komponenter og Microsoft Office-serier og -programvare.

**Merknad for MS09-011**

\*\*Oppdateringen for DirectX 9.0 gjelder også for DirectX 9.0a, DirectX 9.0b og DirectX 9.0c.

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Office-serier, -systemer og -komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143568">
                      <strong>MS09-009</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95876927-e612-414c-bdec-3632a3100415">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB921606)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3dc8b670-25a5-4f46-b7de-12bc693b628a">Microsoft Office Excel 2000 Service Pack 3</a>
                    <br />(KB959964)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1db55c6-78fb-498d-89a5-9ad54d971546">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB933399)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a52bf4b-05f6-4b73-94b9-28ed7e20f86c">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB959988)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9dbfa63-c0cb-4c84-9b8a-6e52568045b0">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB959995)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50d8630b-1365-4007-81a0-18c0d6d4b86e">Microsoft Office Excel 2007 Service Pack 1</a>*<br />(KB959997)<br />(Viktig)<br /></td></tr>
              
                <tr><th colspan="3">Microsoft Office for Mac</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143568">
                      <strong>MS09-009</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2004 for Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=52271140-89be-4b9c-baa2-cea09097d703">Microsoft Office 2004 for Mac</a>
                    <br />(KB968695)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6e407eb-11a5-433f-8006-4b822953ca98">Microsoft Office 2008 for Mac</a>
                    <br />(KB968694)<br />(Viktig)</td></tr>
              
                <tr><th colspan="3">Annen Office-programvare</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139849">
                      <strong>MS09-010</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143568">
                      <strong>MS09-009</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office Excel Viewer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72e6087-b48f-4d2d-8366-01d9f5ff6b6c">Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    <br />(KB959993)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58b3929c-5373-47a4-aa97-66d179758792">Microsoft Office Excel Viewer</a><br />(KB960000)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05f7c517-e551-4dcd-b24a-5d548f2d09cf">Microsoft Office Compatibility Pack for Word, Excel og PowerPoint 2007 File Formats Service Pack 1</a>
                    <br />(KB960003)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office Converter Pack</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d763fae3-b2af-47f9-a554-ec786766b3c3">Microsoft Office Converter Pack</a>
                    <br />(KB960476)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              </table>


**Merknad for MS09-010**

Se også delen **Operativsystemer og komponenter for Windows** for flere oppdateringsfiler. Denne bulletinen dekker både Windows-operativsystemer og -komponenter og Microsoft-serverprogramvare.

**Merknad for MS09-009**

\*For Microsoft Office Excel 2007 Service Pack 1 må kundene også installere sikkerhetsoppdateringen for Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007 Service Pack 1 for å være beskyttet mot sikkerhetsproblemene som er beskrevet i denne bulletinen.

#### Microsoft-server og -sikkerhetsprogramvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Forefront</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141639">
                      <strong>MS09-016</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Forefront Threat Management Gateway</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6abf9fb4-42d0-4c67-935f-8dc67850148b">Microsoft Forefront Threat Management Gateway, Medium Business Edition</a>*<br />(KB968075)<br />(Viktig)</td></tr>
              
                <tr><th colspan="2">Internet Security and Acceleration Server 2006</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141639">
                      <strong>MS09-016</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Internet Security and Acceleration (ISA) Server 2004</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=adf623fa-2d74-4f2a-9835-4b8debdb0e1b">Microsoft Internet Security and Acceleration Server 2004 Standard Edition Service Pack 3</a>**<br />(KB960995)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1d55ab6-3de5-4811-9693-8d43f49f5fe8">Microsoft Internet Security and Acceleration Server 2004 Enterprise Edition Service Pack 3</a><br />(KB960995)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Internet Security and Acceleration Server 2006</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770">Microsoft Internet Security and Acceleration Server 2006</a>
                    <br />(KB968078)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770">Microsoft Internet Security and Acceleration Server 2006 Supportability Update</a><br />(KB968078)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eda30bcc-0582-4f60-a4c5-ea5000b7c770">Microsoft Internet Security and Acceleration Server 2006 Service Pack 1</a><br />(KB968078)<br />(Viktig)</td></tr>
              </table>


**Note for MS09-016**

\*Microsoft Forefront Threat Management Gateway, Medium Business Edition leveres både som et frittstående produkt og en komponent i Windows Essential Business Server 2008.

\*\*Microsoft ISA Server 2004 Standard Edition leveres som et frittstående produkt. Microsoft ISA Server 2004 Standard Edition leveres også som en komponent i Windows Small Business Server 2003 Enterprise Edition Service Pack 1 og Windows Small Business Server 2003 R2 Enterprise Edition.

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer er tilgjengelig fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) og [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Veiledning for søking og distribusjon**

Microsoft har gjort tilgjengelig en veiledning for søking og distribusjon for denne månedens sikkerhetsoppdateringer. Veiledningen vil også hjelpe IT-ansvarlige til å forstå hvordan de kan bruke ulike verktøy til å distribuere sikkerhetsoppdateringen, for eksempel Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office-søkeverktøyet, Microsoft Systems Management Server (SMS) og Extended Security Update Inventory Tool (ESUIT). Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Med Windows Server Update Services (WSUS) kan administratorer raskt og effektivt distribuere de nyeste viktige oppdateringene og sikkerhetsoppdateringene for Windows 2000 og nyere operativsystemer, Office XP og nyere, Exchange Server 2003 og SQL Server 2000, til Windows 2000 og nyere operativsystemer.

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne. Den neste versjonen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du gå til [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Brukere av SMS 2.0 kan også bruke [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) for å få hjelp til å distribuere sikkerhetsoppdateringer. Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer og Microsoft Office-søkeverktøyet til å utøve omfattende støtte for oppdaging og distribusjon av sikkerhetsbulletiner. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validere Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Innholdet i beskrivelsen av Software Update Services og Windows Server Update Services endres. Omfatter alt Windows-innhold.
  - [Nye, reviderte og utgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/dd573344,aspx)

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

  - Haifei Li hos [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-009
  - Sean Larsson og Jun Mao hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-010
  - En forsker hos [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-010
  - En forsker hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-010
  - Piotr Bania hos [Kryptos Logic](http://www.kryptoslogic.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-011
  - Cesar Cerrudo ved [Argeniss](http://www.argeniss.com/) for rapporten om mange sikkerhetsproblemer som beskrives i MS09-012
  - Greg MacManus hos [iSIGHT Partners Labs](http://www.isightpartners.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-013.
  - Wan-Teh Chang og Cem Paya hos [Google Inc.](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-013
  - [Aviv Raff](http://aviv.raffon.net/) for rapporten om et problem som beskrives i MS09-014
  - Michal Zalewski hos [Google Inc.](http://www.google.com/) for rapporten om et problem beskrevet i MS09-014
  - Ivan Fratric hos [iSIGHT Partners Labs](http://www.isightpartners.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-014
  - Skylined hos [Google Inc.](http://www.google.com/) for rapporten om et problem beskrevet i MS09-014
  - ADLab hos [VenusTech](http://www.venustech.com.cn/) for rapporten om et sikkerhetsproblem som beskrives i MS09-014
  - [Aviv Raff](http://aviv.raffon.net/) for rapporten om et problem som beskrives i MS09-015
  - New York States informasjonsleder/teknologileder for rapporten om et problem som beskrives i MS09-016

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (14. april 2009): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (16. april 2009): Utnyttelsesindeksen er oppdatert: fjernet viktige merknader for CVE-2009-0089 og endret viktige merknader for CVE-2008-2540 i MS09-014 og MS09-015.

*Built at 2014-04-18T01:50:00Z-07:00*

