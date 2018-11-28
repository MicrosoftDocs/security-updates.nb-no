---
title: Sammendrag av Microsofts sikkerhetsbulletiner for april 2008
TOCTitle: MS08-APR
ms:assetid: ms08-apr
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms08-apr(v=Security.10)
ms:contentKeyID: 61315188
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for april 2008

Publisert: 8. april 2008 | Oppdatert: 18. februar 2009

**Versjon:** 1.3

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i april 2008.

I forbindelse med utgivelsen av bulletinene for april 2008 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 3. april 2008. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 9. april 2008 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for april på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357219&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (5)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-018</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115454"><strong>Sikkerhetsproblem i Microsoft Project kan tillate ekstern kjøring av kode (950183)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Project som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Project-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Office.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-021</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>Sikkerhetsproblemer i GDI kan tillate ekstern kjøring av kode (948590)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i GDI. Utnyttelse av noen av disse sikkerhetsproblemene kan føre til ekstern kjøring av kode hvis en bruker åpner en spesiallaget EMF- eller WMF-bildefil. En angriper som klarer å utnytte disse sikkerhetsproblemene, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-022</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>Sikkerhetsproblem i skriptmotorer for VBScript og JScript kan tillate ekstern kjøring av kode (944338)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i skriptmotorene for VBScript og JScript i Windows. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-023</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>Sikkerhetsoppdatering av kill bits for ActiveX (948881)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem for et Microsoft-produkt. Oppdateringen inneholder også en kill bit for produktet Yahoo! Music Jukebox. Dette sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen kan kreve en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows, Internet Explorer.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-024</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (947864)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Dette sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows, Internet Explorer.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig (3)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-020</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>Sikkerhetsproblem i måten DNS-klienter kan tillate etterligningsangrep på (945553)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Dette sikkerhetsproblemet som kan tillate etterligningsangrep, finnes i Windows DNS-klienter og kan gjøre det mulig for en angriper å sende spesiallagde svar på DNS-forespørsler og dermed etterligne eller omdirigere Internett-trafikken fra legitime plasseringer.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Etterligningsangrep</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-025</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>Sikkerhetsproblem i Windows-kjernen kan tillate rettighetsutvidelse (941693)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows-kjernen. En lokal angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data eller opprette nye kontoer.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Rettighetsutvidelse</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-019</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115455"><strong>Sikkerhetsproblemer i Microsoft Visio kan tillate ekstern kjøring av kode (949032)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser personlig rapporterte sikkerhetsproblemer i Microsoft Office Visio som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Visio-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Office.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

**Hvordan bruker jeg denne tabellen?**

Bruk tabellen til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det finnes nødvendige sikkerhetsoppdateringer. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

<table>
<caption>Microsoft Windows 2000</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletinidentifikator</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Windows 2000 Service Pack 4</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=caac000a-22b6-48cb-aa00-1a0bfe886de2">Microsoft Windows 2000 Service Pack 4</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.1 og JScript 5.1</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=8e3ff44f-145b-4a68-9ad4-4a55d74b216e">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0395451f-b719-4f71-a7b4-403d0c7e8fcc">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=ba6d3aeb-e35a-47cc-bace-7bd9d58a9d3f">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b051ae04-fe81-440d-9136-d6b239ca954e">Microsoft Internet Explorer 5.01 Service Pack 4</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75d2dc78-e3a4-4ff6-9e2d-bf1935003e8e">Microsoft Internet Explorer 6 Service Pack 1</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=41326ade-96b6-47ce-9291-d4e3039471c4">Microsoft Windows 2000 Service Pack 4</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8db9f328-da0e-4fb8-96c4-6d368b47c224">Microsoft Windows 2000 Service Pack 4</a><br />
(Viktig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows XP</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletinidentifikator</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows XP Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c2763dd8-a03e-4a48-aa86-a7ec00250a7a">Windows XP Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=c0124698-3b94-4474-9473-22a2f39a4a56">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9dbf002f-fe53-4cc7-a430-35f45c520d10">Windows XP Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=36c641ad-953f-4b09-ba1c-9c383295e180">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=e771efe8-8881-4f23-b5b0-15651a390ba9">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=893f4cef-0395-4c44-ba28-7a10b6e7dd48">Windows XP Service Pack 2</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0e937f65-abd0-46dd-8883-5bfd70ea1178">Windows XP Service Pack 2</a><br />
(Viktig)</td>
</tr>
<tr class="even">
<td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=166f2ab5-913c-47a9-86fe-b814797b751e">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=87b80ae3-e299-4d15-a135-3b1bcf943652">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=01400970-df68-4daf-aa39-2fc4f969974c">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=85beacc0-8ca2-4ded-9c24-23348d05c735">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9364bf81-6505-4788-958d-a4bd29dc98ad">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8fdd1207-6e93-4c43-bacc-fe3623a6ebe7">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=a29bbd13-761f-44fa-8948-e1a8c244bd7a">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a><br />
(Viktig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2003</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletinidentifikator</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=bee91d80-d49a-4d3d-82d6-d5aa63f54979">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=88518aa6-e334-4529-aa63-0bf2ef417ce3">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ad384fea-53be-4be3-8acb-1cd23a7f5405">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Moderat)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0444b76e-93fa-43c2-b1bc-a5c054529eb5">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=9acd2a03-5530-49c8-9ea1-0bfaf259700d">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=214bd8f5-6eb2-414c-b013-c516a306d692">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d3b855a6-4648-4771-826d-11a151828eac">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a><br />
(Viktig)</td>
</tr>
<tr class="even">
<td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e3dde449-e062-4ce0-a9f4-433bff23e224">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=12cefefc-8553-4dca-9850-c653371de61e">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc5c893-cb24-4875-b0a7-6d5c7aa4d642">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Moderat)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5ebb5ef9-615f-4cab-bac5-6f45f1b94952">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=a9e406aa-33e2-49b8-ab54-4a7328e46147">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fd123394-a5d6-4b55-be74-2938f52ce922">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=320fd100-35e1-4345-9399-796393235cbc">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a><br />
(Viktig)</td>
</tr>
<tr class="odd">
<td>Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=7886a802-f2b5-489c-b14b-631f4c4c0742">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fe22a828-cca4-4b51-bbd5-995c65fead21">VBScript 5.6 og JScript 5.6</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=94cf78d3-b6c3-41bc-993e-3af3be0d70f1">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a><br />
(Moderat)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=63da8040-fda2-42c7-8543-26ad6f9811f2">Microsoft Internet Explorer 6</a><br />
(Kritisk)<br />
<br />
<a href="http://www.microsoft.com/downloads/details.aspx?familyid=75a05d3a-92a0-4a00-95d4-e2b2f6755180">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e0e63f03-904d-47ee-94fc-51a8dea668eb">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=126426a7-be38-4327-89db-02d99d76589d">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a><br />
(Viktig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Vista</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletinidentifikator</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Vista og Windows Vista Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9b51deb8-3873-4146-977f-7e3d0840a4c5">Windows Vista og Windows Vista Service Pack 1</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d7f14001-7f42-4ca0-9193-cdf061179b59">Windows Vista og Windows Vista Service Pack 1</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d4e24966-6530-463a-9ee2-f6a9d000f998">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8203d303-c855-4579-9bbf-b06ddf5c1b87">Windows Vista</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=9640cd8b-d749-4ddd-8af9-b298cebed969">Windows Vista og Windows Vista Service Pack 1</a><br />
(Viktig)</td>
</tr>
<tr class="even">
<td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4ad6dcd1-6ea5-43bf-8bee-a5f507beadc6">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d33462b6-7391-482d-babe-fb4cd0beaa21">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=295cf8f2-265e-4570-b708-21033337fe05">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=73f3a234-3973-4467-be7e-69efa7ee978c">Windows Vista x64 Edition</a><br />
(Viktig)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=d56bb4fe-304e-45e0-95f2-fde2f47b2a04">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a><br />
(Viktig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Windows Server 2008</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletinidentifikator</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111955"><strong>MS08-021</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108169"><strong>MS08-022</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=112366"><strong>MS08-023</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=110557"><strong>MS08-024</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108231"><strong>MS08-020</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=111956"><strong>MS08-025</strong></a></td>
</tr>
<tr class="even">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
</tr>
<tr class="odd">
<td>Windows Server 2008 for 32-biters systemer</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=006d5c47-53e6-4ee1-932c-497611804938">Windows Server 2008 for 32-biters systemer</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=95691924-2813-4a86-9e11-99d853f8e606">Windows Server 2008 for 32-biters systemer</a><br />
(Lav)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=e57b4d94-19ad-4818-8311-a3f94be01a4b">Windows Internet Explorer 7</a>*<br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=4497333c-9418-4b91-83dc-0155735421c0">Windows Server 2008 for 32-biters systemer</a><br />
(Viktig)</td>
</tr>
<tr class="even">
<td>Windows Server 2008 for x64-baserte systemer</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=8909f144-655b-4f07-916f-fd967f1efb2b">Windows Server 2008 for x64-baserte systemer</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=920ae29b-19d0-4089-ac79-f2da824a2256">Windows Server 2008 for x64-baserte systemer</a><br />
(Lav)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=93e9f52a-c7d0-4033-9c12-740665a219af">Windows Internet Explorer 7</a>*<br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=5aefc7a6-79a4-45a2-b534-35d0ec400dda">Windows Server 2008 for x64-baserte systemer</a><br />
(Viktig)</td>
</tr>
<tr class="odd">
<td>Windows Server 2008 for Itanium-based Systems</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=b7771a4a-4e4f-48d1-8551-bb8b778ca5a7">Windows Server 2008 for Itanium-based Systems</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=66df79ac-8364-4922-9688-ebc7ec76d89f">Windows Server 2008 for Itanium-based Systems</a><br />
(Lav)</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=acf948e8-c4a9-40da-b282-f5e584e77b05">Windows Internet Explorer 7</a><br />
(Kritisk)</td>
<td>Ingen</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=3080c26b-7456-41ef-8668-28f15bc7b8ce">Windows Server 2008 for Itanium-based Systems</a><br />
(Viktig)</td>
</tr>
</tbody>
</table>


**\*Server Core-installasjonen av Windows Server 2008 ikke berørt.** Sikkerhetsproblemene som løses av disse oppdateringene, berører ikke støttede versjoner av Windows Server 2008 hvis Windows Server 2008 ble installert via installasjonsalternativet Server Core, selv om filer som er berørt av disse sikkerhetsproblemene, kan være til stede i systemet. Brukere blir imidlertid fortsatt tilbudt denne oppdateringen fordi oppdateringsfilene er nyere (med høyere versjonsnumre) enn filene som finnes på systemet. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office-serier og -programvare

<table>
<caption>Microsoft Project</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletinidentifikator</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115454"><strong>MS08-018</strong></a></td>
</tr>
<tr class="even">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Kritisk</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Project 2000 Service Release 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=fbe46241-b9da-40c6-803d-42eb6234be77">Project 2000 Service Release 1</a><br />
(KB949043)<br />
(Kritisk)</td>
</tr>
<tr class="even">
<td>Microsoft Project 2002 Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=07a90718-6597-426d-9dca-a336d60c01b8">Project 2002 Service Pack 1</a><br />
(KB949005)<br />
(Viktig)</td>
</tr>
<tr class="odd">
<td>Microsoft Project 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=aaba07d6-e972-4e85-bccd-406aa2c4a4f4">Project 2003 Service Pack 2</a><br />
(KB948962)<br />
(Viktig)</td>
</tr>
</tbody>
</table>


<table>
<caption>Microsoft Visio</caption>
<tbody>
<tr class="odd">
<td><strong>Bulletinidentifikator</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=115455"><strong>MS08-019</strong></a></td>
</tr>
<tr class="even">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140"><strong>Viktig</strong></a></td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2002 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0056a936-def5-40fa-bcfc-0ab0dd5c3964">Visio 2002 Service Pack 2</a><br />
(KB947896)<br />
(Viktig)</td>
</tr>
<tr class="even">
<td>Microsoft Visio 2003 Service Pack 2</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 2</a><br />
(KB947650)<br />
(Viktig)</td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2003 Service Pack 3</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=18af0ce6-99a0-4471-8d26-9700a8a8e631">Visio 2003 Service Pack 3</a><br />
(KB947650)<br />
(Viktig)</td>
</tr>
<tr class="even">
<td>Microsoft Visio 2007</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007</a><br />
(KB947590)<br />
(Viktig)</td>
</tr>
<tr class="odd">
<td>Microsoft Visio 2007 Service Pack 1</td>
<td><a href="http://www.microsoft.com/downloads/details.aspx?familyid=0510a1bb-b464-452c-900f-7f4e58ed9c7e">Visio 2007 Service Pack 1</a><br />
(KB947590)<br />
(Viktig)</td>
</tr>
</tbody>
</table>


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

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Beskrivelse av innholdsendringer for Software Update Services og Windows Server Update Services 2008. Inkluderer alt Windows-innhold.
  - [Nye, reviderte og utgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)

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

  - [National Cyber Security Center](http://www.ncsc.go.kr/eng/), The Republic of Korea for rapporten om et sikkerhetsproblem som beskrives i MS08-018
  - En anonym person for rapporten om et sikkerhetsproblem som beskrives i MS08-019
  - En anonym person for rapporten om et annet sikkerhetsproblem som beskrives i MS08-019
  - Amit Klein hos [Trusteer](http://www.trusteer.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-020
  - Alla Berzroutchko hos [Scanit](http://www.scanit.be/) for rapporten om et sikkerhetsproblem som beskrives i MS08-020
  - Roy Arends hos [Nominet UK](http://www.nominet.org.uk/) for rapporten om et sikkerhetsproblem som beskrives i MS08-020
  - Jun Mao hos [iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-021
  - Sebastian Apelt hos [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-021
  - Thomas Garnier hos [SkyRecon](http://www.skyrecon.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-021
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om sikkerhetsproblemet som beskrives i MS08-021
  - Peter Ferrie hos [Symantec](http://www.symantec.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-022
  - En anonym forsker i samarbeid med [iDefense VCP](http://labs.idefense.com/vcp/) for rapporten om et sikkerhetsproblem som beskrives i MS08-023
  - Carsten Eiram hos [Secunia](http://secunia.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-024
  - Thomas Garnier hos [SkyRecon](http://www.skyrecon.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-025

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (8. april 2008): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (9. april 2008): Kortfattet sammendrag for Microsofts sikkerhetsbulletin MS08-018 er oppdatert.
  - V1.2 (16. april 2008): Informasjon om oppdageren av problemet for MS08-021 oppdatert, og klargjøring lagt til om berørt programvare for Microsoft Office-serier og -programvare.
  - V1.3 (18. februar 2009): Lagt til en notasjon om serverkjerne som ikke berøres, for Windows Server 2008 for 32-biters systemer og Windows Server 2008 for x64-baserte systemer for MS08-024.

*Built at 2014-04-18T01:50:00Z-07:00*

