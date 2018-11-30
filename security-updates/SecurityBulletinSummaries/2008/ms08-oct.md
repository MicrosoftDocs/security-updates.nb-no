---
title: Sammendrag av Microsofts sikkerhetsbulletiner for oktober 2008
TOCTitle: MS08-OCT
ms:assetid: ms08-oct
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms08-oct(v=Security.10)
ms:contentKeyID: 61315198
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for oktober 2008

Publisert: 14. oktober 2008 | Oppdatert: 23. oktober 2008

**Versjon:** 3.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i oktober 2008.

I forbindelse med utgivelsen av bulletinene for oktober 2008 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 9. oktober 2008. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 15. oktober 2008 kl 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for oktober på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374639). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (5)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-067</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130719"><strong>Sikkerhetsproblem i servertjenesten kan tillate ekstern kjøring av kode (958644)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i servertjenesten. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker mottar en spesiallaget RPC-forespørsel på et berørt system. På systemene Microsoft Windows 2000, Windows XP og Windows Server 2003 kan en angriper uten godkjenning utnytte dette sikkerhetsproblemet for å kjøre vilkårlig kode. Det er mulig at dette sikkerhetsproblemet kan brukes til å lage et ormbasert angrep. Gode fremgangsmåter for brannmurer og vanlige standard brannmurkonfigurasjoner kan bidra til å beskytte nettverksressurser mot angrep fra andre steder enn innenfor virksomheten.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-060</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128125"><strong>Sikkerhetsproblem i Active Directory kan tillate ekstern kjøring av kode (957280)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i implementeringene av Active Directory på Microsoft Windows 2000 Server. Sikkerhetsproblemet kan tillate kjøring av ekstern kode hvis en angriper får tilgang til et berørt nettverk. Dette sikkerhetsproblemet berører bare Microsoft Windows 2000-servere som er konfigurert til å være domenekontrollere. Hvis en Microsoft Windows 2000-server ikke har blitt forfremmet til en domenekontroller, lytter den ikke til LDAP-spørringer (Lightweight Directory Access Protocol) eller LDAP over SSL-spørringer (LDAPS), og den berøres ikke av dette sikkerhetsproblemet.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-058</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (956390)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem. Sikkerhetsproblemene kan potensielt tillate tilgjengeliggjøring av informasjon eller ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows, Internet Explorer.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-059</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125712"><strong>Sikkerhetsproblem i RPC-tjenesten for Host Integration Server som kan tillate ekstern kjøring av kode (956695)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Host Integration Server. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper sender en spesiallaget RPC-forespørsel (Remote Procedure Call) til et berørt system. Kunder som følger anbefalte fremgangsmåter og konfigurerer SNA RPC-tjenestekontoen slik at den får færre brukerrettigheter på systemet, kan bli mindre berørt enn kunder som konfigurerer SNA RPC-tjenestekontoen slik at den får administrative brukerrettigheter.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen kan kreve en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Host Integration Server.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-057</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=124653"><strong>Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (956416)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser tre personlig rapporterte sikkerhetsproblemer i Microsoft Office Excel som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-fil. En angriper som klarer å utnytte disse sikkerhetsproblemene, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Office.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig (6)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-066</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125709"><strong>Sikkerhetsproblem i Microsofts tilleggsfunksjonsdriver kan føre til rettighetsutvidelse (956803)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsofts tilleggsfunksjonsdriver. En lokal angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Rettighetsutvidelse</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-061</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=121738"><strong>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (954211)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser ett publisert sikkerhetsproblem og to personlig rapporterte sikkerhetsproblemer i Windows-kjernen. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. Sikkerhetsproblemene kan ikke utnyttes eksternt eller av anonyme brukere.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Rettighetsutvidelse</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-062</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=120829"><strong>Sikkerhetsproblem i Internett-utskriftstjeneste i Windows kan tillate ekstern kjøring av kode (953155)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne oppdateringen løser et personlig rapportert sikkerhetsproblem i Internett-utskriftstjenesten i Windows som kan føre til ekstern kjøring av kode. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data eller opprette nye kontoer.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-063</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=127994"><strong>Sikkerhetsproblem i SMB kan tillate ekstern kjøring av kode (957095)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i protokollen for Microsoft-servermeldingsblokken (SMB). Sikkerhetsproblemet kan tillate ekstern kjøring av kode på en server som deler filer eller mapper. En angriper som utnytter disse sikkerhetsproblemene, kan installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-064</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128103"><strong>Sikkerhetsproblem i manipuleringen av Virtual Address Descriptor som kan tillate rettighetsutvidelse (956841)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Virtual Address Descriptor. Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en bruker kjører et spesiallaget program. En godkjent angriper som utnytter dette sikkerhetsproblemet, kan få rettighetsutvidelse på et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fulle administrative rettigheter.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Rettighetsutvidelse</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-065</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128102"><strong>Sikkerhetsproblem i Message Queuing kan føre til ekstern kjøring av kode (951071)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Message Queuing-tjenesten (MSMQ) på Microsoft Windows 2000-systemer. Sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode på Microsoft Windows 2000-systemer som har MSMQ-tjenesten aktivert.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Ekstern kjøring av kode</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Moderat (1)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS08-056</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128145"><strong>Sikkerhetsproblem i Microsoft Office kan tillate tilgjengeliggjøring av informasjon (957699)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Office. Dette sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en bruker klikker en spesiallaget CDO-URL-adresse. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan sette inn et klientsideskript i brukerens webleser. Dette skriptet kan forfalske innhold, oppgi informasjon eller utføre alle typer handlinger som brukeren kan utføre, på det berørte webområdet.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Microsoft Office.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

**Hvordan bruker jeg denne tabellen?**  

Bruk denne tabellen til å lære mer om sannsynligheten for at fungerende skadelig kode blir utgitt for hver av sikkerhetsoppdateringene du kanskje må installere. Du bør se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploit Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-ID</th>
<th style="border:1px solid black;">Bulletintittel</th>
<th style="border:1px solid black;">CVE-ID</th>
<th style="border:1px solid black;">Utnyttelsesindeksvurdering</th>
<th style="border:1px solid black;">Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128145">MS08-056</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128145">Sikkerhetsproblem i Microsoft Office kan tillate tilgjengeliggjøring av informasjon (957699)</a></td>
<td style="border:1px solid black;">CVE-2008-4020</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;">Fungerende skadelig kode kan bli laget. Alvorlighetsgraden er imidlertid begrenset, siden sikkerhetsproblemet bare tillater etterligningsangrep i en dialog i spesifikke webprogramscenarioer. Resultatet er at angripere vil vise dette liten oppmerksomhet.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=124653">Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (956416)</a></td>
<td style="border:1px solid black;">CVE-2008-4019</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=124653">Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (956416)</a></td>
<td style="border:1px solid black;">CVE-2008-3471</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=124653">MS08-057</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=124653">Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (956416)</a></td>
<td style="border:1px solid black;">CVE-2008-3477</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">Kumulativ sikkerhetsoppdatering for Internet Explorer (956390)</a></td>
<td style="border:1px solid black;">CVE-2008-2947</td>
<td style="border:1px solid black;">(Offentlig ved utgivelse av bulletin)</td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">Kumulativ sikkerhetsoppdatering for Internet Explorer (956390)</a></td>
<td style="border:1px solid black;">CVE-2008-3472</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">Kumulativ sikkerhetsoppdatering for Internet Explorer (956390)</a></td>
<td style="border:1px solid black;">CVE-2008-3473</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">Kumulativ sikkerhetsoppdatering for Internet Explorer (956390)</a></td>
<td style="border:1px solid black;">CVE-2008-3475</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">Kumulativ sikkerhetsoppdatering for Internet Explorer (956390)</a></td>
<td style="border:1px solid black;">CVE-2008-3474</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 – Fungerende skadelig kode er usannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">MS08-058</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128060">Kumulativ sikkerhetsoppdatering for Internet Explorer (956390)</a></td>
<td style="border:1px solid black;">CVE-2008-3476</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 – Fungerende skadelig kode er usannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125712">MS08-059</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125712">Sikkerhetsproblem i RPC-tjenesten for Host Integration Server kan tillate ekstern kjøring av kode (956695)</a></td>
<td style="border:1px solid black;">CVE-2008-3466</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;">Selv om det sannsynligvis bare er enkelte typer bedriftskunder som vil installere Host Integration Server, er det sannsynlig at fungerende skadelig kode lages.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128125">MS08-060</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128125">Sikkerhetsproblem i Active Directory kan tillate ekstern kjøring av kode (957280)</a></td>
<td style="border:1px solid black;">CVE-2008-4023</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;">Det er sannsynlig at sikkerhetsproblemet utløses for å forårsake en situasjon med tjenestenekt. Oppretting av fungerende skadelig kode for å utnytte ekstern kjøring av kode er imidlertid vanskelig på grunn av mangelen på kontroll over en nødvendig skriveadresse.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=121738">Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (954211)</a></td>
<td style="border:1px solid black;">CVE-2008-2250</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=121738">Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (954211)</a></td>
<td style="border:1px solid black;">CVE-2008-2252</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;">Fungerende skadelig kode lages mest sannsynlig for systemer med flere prosessorer.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=121738">MS08-061</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=121738">Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (954211)</a></td>
<td style="border:1px solid black;">CVE-2008-2251</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 – Fungerende skadelig kode er usannsynlig</a></td>
<td style="border:1px solid black;">Det er mulig å utløse sikkerhetsproblemet, men det er svært vanskelig å lage vellykket, fungerende skadelig kode.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=120829">MS08-062</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=120829">Sikkerhetsproblem i Internett-utskriftstjeneste i Windows kan tillate ekstern kjøring av kode (953155)</a></td>
<td style="border:1px solid black;">CVE-2008-1446</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;">Konsekvent skadelig kode er funnet i begrensede, målrettede angrep. Selv om IPP-tjenesten (Internett-utskriftsprotokoll) er aktivert som standard, krever tilgang til denne tjenesten via IIS også godkjenning som standard på alle plattformer.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=127994">MS08-063</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=127994">Sikkerhetsproblem i SMB kan tillate ekstern kjøring av kode (957095)</a></td>
<td style="border:1px solid black;">CVE-2008-4038</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128103">MS08-064</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128103">Sikkerhetsproblem i manipuleringen av Virtual Address Descriptor kan tillate rettighetsutvidelse (956841)</a></td>
<td style="border:1px solid black;">CVE-2008-4036</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128102">MS08-065</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128102">Sikkerhetsproblem i Message Queuing kan tillate ekstern kjøring av kode (951071)</a></td>
<td style="border:1px solid black;">CVE-2008-3479</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3 – Fungerende skadelig kode er usannsynlig</a></td>
<td style="border:1px solid black;">Selv om tilgjengeliggjøring av informasjon er mulig, er det ikke alltid mulig å hente nyttig innhold fra minnet. Problemet med minnefeil kan utløses, men det er vanskelig å oppnå ekstern kjøring av kode.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125709">MS08-066</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=125709">Sikkerhetsproblem i Microsofts tilleggsfunksjonsdriver kan føre til rettighetsutvidelse (956803)</a></td>
<td style="border:1px solid black;">CVE-2008-3464</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;"></td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130719">MS08-067</a></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=130719">Sikkerhetsproblem i servertjenesten kan tillate ekstern kjøring av kode (958644)</a></td>
<td style="border:1px solid black;">CVE-2008-4250</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td style="border:1px solid black;">Konsekvent skadelig kode er funnet i begrensede, målrettede angrep, noe som berører Windows XP. Selv om denne tjenesten er aktivert som standard på alle berørte plattformer, er det mest sannsynlig at sikkerhetsproblemet kan utnyttes på Microsoft Windows 2000, Windows XP og Windows Server 2003. Plattformene Windows Vista, Windows Server 2008 og Windows 7 Beta krever godkjenning, og selv etter godkjenning er det vanskeligere å utnytte dette sikkerhetsproblemet på grunn av forbedringer av ASLR og DEP.</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

**Hvordan bruker jeg denne tabellen?**  

Bruk tabellen til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det finnes nødvendige sikkerhetsoppdateringer. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

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
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="10" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e22eb3ae-1295-4fe2-9775-6f43c5c2aed3">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ed7bb9a-4b26-49d7-8c14-60226d2bc20d">Active Directory på Microsoft Windows 2000 Server Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=257c0478-56dd-42eb-a90e-607d01613db7">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=02390258-08e9-4b75-960d-be081b749558">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a6165a6-d7e7-4526-9291-290caf0639b4">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8163d1f6-feb5-4f39-8134-3ed42326b822">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ed29c3a-0682-4586-bbc2-a73deaa18e4c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=899e2728-2433-4ccb-a195-05b5d65e5469">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="10" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d5f9b6e-9265-44b9-a376-2067b73d6a03">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7f0f47b-b1ee-4516-9fbf-bf8e579963d0">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e73de2b-05e6-4901-9bac-46d8f469e635">Windows Internet Explorer 7</a><br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b16d9dac-c430-4dd8-a1e5-9a614801f1d9">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)<br /></td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7718bf14-c26c-43f3-be67-4c79ab5b2607">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)<br /></td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7ef571f-c9e8-4e14-95a3-3eeaec55b784">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)<br /></td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f7e5981-6eef-4f08-86c0-c6a7607ea5d0">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)<br /></td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25997b73-a640-49c1-b19e-768a18bbe22c">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)<br /></td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c16a372-7bf8-4571-b982-dac6b2992b25">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=234c05fb-988b-4e02-aab6-bb23e447df3d">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccf7a3e3-ec30-4b95-9a86-00032301513c">Windows Internet Explorer 7</a><br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b607efc-c6fb-4079-8478-e4f3262386d3">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b06d3a02-b6e4-4d40-913a-3759a31f20f3">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ae4b913-bff0-4974-b198-828ca10d2a87">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e1675eb-6b06-48e9-9765-23a2c7737bdc">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50fae854-0bde-46f8-9444-b9e0d9bfecad">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="10" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f26d395d-2459-4e40-8c92-3de1c52c390d">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae8d22d5-20aa-471d-a423-f54c9d75febe">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feaf2adf-7892-4dbf-a147-db4d5dbe52f3">Windows Internet Explorer 7</a><br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ee88ff2d-1b12-4f4c-a081-9f27a6fba074">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e696762-d652-4a8f-ab8f-622f9746c320">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=437a9b68-6a0c-48c8-9348-0d6fda48aa21">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbbebb3f-f1c7-402c-bd16-6f88da0d042c">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8ef3d5f-dd8e-4945-92cd-9d3e30b16667">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c04d2afb-f9d0-4e42-9e1f-4b944a2de400">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07fc88c4-2571-4a4d-b573-ae576798ab4c">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=319dba34-07ca-47f9-a1e9-20df2df7966b">Windows Internet Explorer 7</a><br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab4d94d3-458c-4946-ab7f-03a279629d25">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57ca28ea-e5e1-4191-a3d6-84aa90a3d668">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3df6508-a568-449d-ac97-fbf3f97b98ef">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=989ac6f1-515c-467d-a200-2aabe66d9319">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2e754f9-086a-494c-bc19-5feed7df8b65">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab590756-f11f-43c9-9dcc-a85a43077acf">Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium based Systems</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b68937af-f04a-4d1e-9d7f-ec92af5194de">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47381d91-4a14-4a09-96b3-3345155df52d">Windows Internet Explorer 7</a><br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63234f85-6e5d-4ef6-b7cf-d1d2c78a5517">Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e6c3f81-85bb-48e6-a5af-635a7e540c93">Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=748f54f1-40b9-407c-9819-909061b53743">Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91589cfb-15ba-4dd2-9e3b-107899fbcba6">Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a3832ec-3f8f-42c1-a603-b1330d527547">Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="10" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista og Windows Vista Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=18fdff67-c723-42bd-ac5c-cac7d8713b21">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4756e04b-6e1c-4d78-a3c0-17f6b4b97975">Windows Internet Explorer 7</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3483b400-cedc-441f-ba8e-594e3df89190">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b5995df-a3b8-4e81-b118-9bb057e19884">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Ingen alvorlighetsgrad)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72dd6015-25d1-45f4-a769-88ac43074b44">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b4212db5-093e-497d-b999-2e3780f9f7c2">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a976999d-264f-4e6a-9bd6-3ad9d214a4bd">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd19c72b-4f83-47ab-93be-d2c286e732c4">Windows Internet Explorer 7</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=905ab030-14a5-4a3d-aa11-e8f957f6a1ea">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a0fcf4b-eb8e-456a-b934-400ae18248ee">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Ingen alvorlighetsgrad)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f793af16-5464-4db1-a42b-1c5f17c538ed">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c20808cb-c30a-4b53-91e5-810eb6b4b2e3">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="10" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25c17b07-1efe-43d7-9b01-3dfdf1ce0bd7">Windows Server 2008 for 32-biters systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec73f416-2204-42d6-8932-c96578ac819f">Windows Internet Explorer 7</a>**<br />(Lav)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b97114a-71aa-47a2-b9e7-f4e158c18c80">Windows Server 2008 for 32-biters systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d6290d8-1745-4bc0-9ca9-eeb1ad0be4a5">Windows Server 2008 for 32-biters systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf6744e6-b54c-40f6-a78d-7ba9453133c0">Windows Server 2008 for 32-biters systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ec9eeb82-0497-4c55-94bb-9a47cb3521b4">Windows Server 2008 for 32-biters systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b12018e-0cc1-4136-a68c-be4e1633c8df">Windows Server 2008 for x64-baserte systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=baacd1c2-9764-4fea-bd4d-c49791974fef">Windows Internet Explorer 7</a>**<br />(Lav)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e641db2-90c8-458f-9795-3e46b70a5203">Windows Server 2008 for x64-baserte systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a33c833c-d5c5-4e37-8f89-7b9079f92e59">Windows Server 2008 for x64-baserte systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=223236e8-7b19-4b47-8a90-bfc35eb9318a">Windows Server 2008 for x64-baserte systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0bc178b8-f8ae-4f41-8f88-fb6a75be1bca">Windows Server 2008 for x64-baserte systemer</a>*<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for Itanium-based Systems</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bcf89ef-6446-406c-9c53-222e0f0baf7a">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=250a45dd-7eae-4440-bd10-02a703940976">Windows Internet Explorer 7</a>
                    <br />(Lav)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6546e1c-bf7b-4354-8574-6c16fa707de0">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31783e88-76e2-4bc6-b4ae-308443c6d223">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Ingen alvorlighetsgrad)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=077b697c-04a0-45bd-b08c-331d5c30cb47">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0af72663-4945-4916-8c55-090ba4d82793">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="10" style="border:1px solid black;">Windows 7 Beta</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=130719">
                      <strong>MS08-067</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128125">
                      <strong>MS08-060</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128060">
                      <strong>MS08-058</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125709">
                      <strong>MS08-066</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=121738">
                      <strong>MS08-061</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120829">
                      <strong>MS08-062</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=127994">
                      <strong>MS08-063</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128103">
                      <strong>MS08-064</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128102">
                      <strong>MS08-065</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 Beta for 32-biters systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e877d9c1-3e7c-4551-a899-c3fcc5175bb6">Windows 7 Beta for 32-biters systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 Beta for x64-baserte systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0fa96b25-90e3-46ab-bcd5-051f4b2b881b">Windows 7 Beta x64 Edition</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 Beta for Itanium-based Systems</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66646156-f3e6-48d7-be22-de1772dd1884">Windows 7 Beta for Itanium-based Systems</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**\*Server Core-installasjonen av Windows Server 2008 berørt.** For støttede versjoner av Windows Server 2008 gjelder denne oppdateringen (med samme alvorlighetsgrad) enten Windows Server 2008 ble installert med installasjonsalternativet for Server Core eller ikke. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen av Windows Server 2008 ikke berørt.** Sikkerhetsproblemet som løses i disse oppdateringene, berører ikke støttede versjoner av Windows Server 2008 hvis Windows Server 2008 ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office-serier og -programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office-serier, -systemer og -komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2000 Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2740e0-ecdd-48ca-84e0-eb187c31eb16">Excel 2000 Service Pack 3</a>
                    <br />(KB955461)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office XP Service  Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27cedef1-c47c-472c-a343-cd9b4ebc2bba">Excel 2002 Service Pack 3</a>
                    <br />(KB955464)<br />(Viktig)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1aee2d5-bfa0-40e3-91b6-98bf65524e8c">Microsoft Office XP Service Pack 3</a>
                    <br />(KB956464)<br />(Moderat)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 2 og Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368">Excel 2003 Service Pack 2</a>
                    <br />(KB955466)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4df27e8a-d803-483b-a700-0177d71bf368">Excel 2003 Service Pack 3</a><br />(KB955466)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">2007 Microsoft Office System og 2007 Microsoft Office System Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f">Excel 2007</a>
                    <br />(KB955470)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2765bbc0-ea2e-4b6e-822c-222ee8e5021f">Excel 2007 Service Pack 1</a><br />(KB955470)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office for Mac</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2004 for Mac</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba4fa21a-7e01-4ef8-9b9f-9d51d00ef094">Microsoft Office 2004 for Mac</a>
                    <br />(KB958312)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2008 for Mac</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e70c5ae0-2858-46de-81f8-dcd1786656b7">Microsoft Office 2008 for Mac</a>
                    <br />(KB958267)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Open XML File Format Converter for Mac</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a8d9a3b-b8a4-43b6-82a6-a2e7d16ae11d">Open XML File Format Converter for Mac</a>
                    <br />(KB958304)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Annen Office-programvare</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124653">
                      <strong>MS08-057</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128145">
                      <strong>MS08-056</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Excel Viewer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b">Microsoft Office Excel Viewer 2003</a>
                    <br />(KB955468)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9769ce08-5207-4c63-b7b9-536266ad6b2b">Microsoft Office Excel Viewer 2003 Service Pack 3</a><br />(KB955468)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83c88444-75b8-44d1-b280-3671394ade45">Microsoft Office Excel Viewer</a><br />(KB955935)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9">Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB955936)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7be004-5903-4101-90c5-c0d5f8722af9">Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007 Service Pack 1</a><br />(KB955936)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office SharePoint Server 2007</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535">Microsoft Office SharePoint Server 2007</a>*<br />(KB955937)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c29e646-504c-4455-9d35-9a1bed6d7535">Microsoft Office SharePoint Server 2007 Service Pack 1</a>*<br />(KB955937)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f">Microsoft Office SharePoint Server 2007 x64 Edition</a>*<br />(KB955937)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c21c405-2c9e-45d0-be4d-8ccd093af31f">Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1</a>*<br />(KB955937)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


\*Denne oppdateringen gjelder for servere som har Excel Services installert, for eksempel standardkonfigurasjonen til Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 for Internett-områder. Microsoft Office SharePoint Server 2007 Standard inkluderer ikke Excel Services.

#### Microsoft Server-programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="" style="border:1px solid black;">Microsoft Host Integration Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=125712">
                      <strong>MS08-059</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Host Integration Server 2000</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11cca58b-59a4-4e93-9eb1-19b07c290a10">Microsoft Host Integration Server 2000 Service Pack 2 (Server)</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41b49291-1231-4e23-aef7-818207453d56">Microsoft Host Integration Server 2000 Administrator Client</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Host Integration Server 2004</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ca255ed-9334-4848-af94-49ef3078cdc0">Microsoft Host Integration Server 2004 (Server)</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eca756a1-ca56-4481-b23c-53c159a4e08c">Microsoft Host Integration Server 2004 Service Pack 1 (Server)</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92cb54e7-f4ff-40a4-99cb-6257c4d8d4cd">Microsoft Host Integration Server 2004 (Client)</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d776515c-09aa-4a04-876d-606bfc26a006">Microsoft Host Integration Server 2004 Service Pack 1 (Client)</a><br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Host Integration Server 2006</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ae79da3-ec17-4d4b-8011-d777a237ac93">Microsoft Host Integration Server 2006 for 32-biters systemer</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05da4540-4976-458a-a612-7385d78695a2">Microsoft Host Integration Server 2006 for x64-baserte systemer</a><br />(Kritisk)</td></tr>
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

**Systems Management Server:**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne. Den neste versjonen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du gå til [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Brukere av SMS 2.0 kan også bruke [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) for å få hjelp til å distribuere sikkerhetsoppdateringer. Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer og Microsoft Office-søkeverktøyet til å gi omfattende støtte for oppdaging og distribusjon av sikkerhetsbulletiner. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validere Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Beskrivelse av innholdsendringer for Software Update Services og Windows Server Update Services 2008. Inkluderer alt Windows-innhold.
  - [Nye, reviderte og utgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

  - [NetAgent Co.,Ltd.](http://www.netagent.co.jp/) for rapporten om et sikkerhetsproblem som beskrives i MS08-056
  - Joshua J. Drake hos [iDefense](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-057
  - Wushi, i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS08-057
  - Lionel d'Hauenens hos [Labo Skopia](http://www.laboskopia.com/), i samarbeid med [iDefense VCP](http://labs.idefense.com/), for rapporten om et sikkerhetsproblem som er beskrevet i MS08-057
  - David Bloom for rapporten om et sikkerhetsproblem som beskrives i MS08-058
  - Gregory Rubin for rapporten om et sikkerhetsproblem som beskrives i MS08-058
  - [Ivan Fratric](http://ifsec.blogspot.com/), i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS08-058
  - Thierry Zoller hos [n.runs](http://www.nruns.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-058
  - Lee Dagon hos [Composica](http://www.composica.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-058
  - Stephen Fewer hos [Harmony Security](http://www.harmonysecurity.com/), i samarbeid med [iDefense VCP](http://labs.idefense.com/), for rapporten om et sikkerhetsproblem som beskrives i MS08-059
  - Paul Miseiko hos [nCircle](http://www.ncircle.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-060
  - Paul Caton hos [iShadow](http://www.ishadow.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-061
  - Thomas Garnier hos [SkyRecon](http://www.skyrecon.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-061
  - [CERT/CC](http://www.cert.org/) for rapporten om et sikkerhetsproblem som beskrives i MS08-062
  - Joshua Morin hos [Codenomicon](http://www.codenomicon.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-063
  - Cody Pierce og Aaron Portnoy hos [TippingPoint DVLabs](http://dvlabs.tippingpoint.com) for rapporten om et sikkerhetsproblem som beskrives i MS08-065
  - Fabien Le Mentec hos [SkyRecon](http://www.skyrecon.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-066

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (14. oktober 2008): Publisert sammendrag av sikkerhetsbulletin.
  - V2.0 (15. oktober 2008): Alvorlighetsgraden for Windows Server 2008 for Itanium-based Systems er fjernet (MS08-062).
  - V2.1 (16. oktober 2008): Oppdaterte Kortfattet sammendrag for Microsofts sikkerhetsbulletin MS08-062.
  - V3.0 (23. oktober 2008): La til Microsofts sikkerhetsbulletin MS08-067, Sikkerhetsproblem i servertjenesten kan føre til ekstern kjøring av kode (958644).

*Built at 2014-04-18T01:50:00Z-07:00*

