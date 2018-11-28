---
title: Sammendrag av Microsofts sikkerhetsbulletiner for august 2008
TOCTitle: MS08-AUG
ms:assetid: ms08-aug
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms08-aug(v=Security.10)
ms:contentKeyID: 61315189
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for august 2008

Publisert: 12. august 2008 | Oppdatert: 15. oktober 2008

**Versjon:** 3.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i august 2008.

I forbindelse med utgivelsen av bulletinene for august 2008 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 7. august 2008. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 13. august 2008 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for august på webcast](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032374631&culture=en-us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (6)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-046</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120576"><strong>Et sikkerhetsproblem i Microsoft Windows Image Color Management System kan føre til ekstern kjøring av kode (952954)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne oppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft ICM-systemet (Image Color Management) som kan føre til ekstern kjøring av kode i omgivelsene til den gjeldende brukeren. Hvis en bruker er logget på med administrative rettigheter, kan en angriper som klarte å utnytte dette sikkerhetsproblemet, ta kontroll over det berørte systemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<th>Microsofts sikkerhetsbulletin MS08-045</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=122772"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (953838)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem. Alle sikkerhetsproblemene kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-041</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=122912"><strong>Sikkerhetsproblem i ActiveX-kontrollen for Snapshot Viewer for Microsoft Access som kan tillate ekstern kjøring av kode (955617)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i ActiveX-kontrollen for Snapshot Viewer for Microsoft Access. En angriper kan utnytte dette sikkerhetsproblemet ved å opprette en spesiallaget webside. Når en bruker viser websiden, kan sikkerhetsproblemet tillate ekstern kjøring av kode. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den påloggede brukeren.</td>
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
<th>Microsofts sikkerhetsbulletin MS08-043</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=124306"><strong>Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (954066)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser fire personlig rapporterte sikkerhetsproblemer i Microsoft Office Excel som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-fil. En angriper som klarer å utnytte disse sikkerhetsproblemene, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<th>Microsofts sikkerhetsbulletin MS08-051</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120394"><strong>Sikkerhetsproblemer i Microsoft PowerPoint kan tillate ekstern kjøring av kode (949785)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser tre personlige rapporterte sikkerhetsproblemer i Microsoft Office PowerPoint og Microsoft Office PowerPoint Viewer som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget PowerPoint-fil. En angriper som klarer å utnytte et av disse sikkerhetsproblemene, kan få full kontroll over det berørte systemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<th>Microsofts sikkerhetsbulletin MS08-044</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120819"><strong>Sikkerhetsproblemer i Microsoft Office-filtre kan tillate ekstern kjøring av kode (924090)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer. Disse sikkerhetsproblemene kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget bildefil via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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


## Viktig (5)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-047</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=120577"><strong>Sikkerhetsproblem med behandling av IPsec-policy kan føre til tilgjengeliggjøring av informasjon (953733)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne oppdateringen løser et personlig rapportert sikkerhetsproblem i måten som enkelte regler for Windows Internet Protocol-sikkerhet (IPsec) brukes. Dette sikkerhetsproblemet kan føre til at systemer ignorerer IPsec-policyer og overfører nettverkstrafikk i klartekst. Det kan igjen føre til at informasjon som skulle vært kryptert i et nettverk, tilgjengeliggjøres. En angriper som ser på trafikken i nettverket, kan vise og muligens endre innholdet i trafikken. Legg merke til at dette sikkerhetsproblemet ikke gjør det mulig for en angriper å kjøre kode eller utvide egne brukerrettigheter direkte. Det kan brukes til å samle inn nyttig informasjon som senere kan brukes til å skade det berørte systemet eller nettverket ytterligere.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Tilgjengeliggjøring av informasjon</td>
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
<th>Microsofts sikkerhetsbulletin MS08-049</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104923"><strong>Sikkerhetsproblemer i Event System kan føre til ekstern kjøring av kode (950974)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne oppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Windows Event System som kan føre til kjøring av ekstern kode. En angriper som klarer å utnytte disse sikkerhetsproblemene, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fulle administrative rettigheter.</td>
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
<th>Microsofts sikkerhetsbulletin MS08-048</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=117705"><strong>Sikkerhetsoppdatering for Outlook Express og Windows Mail (951066)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Outlook Express og Windows Mail. Dette sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen kan kreve en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows, Outlook Express og Windows Mail.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsoft Security Bulletin MS08-050</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=108245"><strong>Sikkerhetsproblem i Windows Messenger kan tillate tilgjengeliggjøring av informasjon (955702)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem for støttede versjoner av Windows Messenger. Som et resultat av dette sikkerhetsproblemet kan skripting av en ActiveX-kontroll tillate tilgjengeliggjøring i omgivelsene til den påloggede brukeren. En angriper kan endre status, innhente kontaktinformasjon og opprette lyd- og videosamtaleøkter uten at den påloggede brukeren er klar over det. En angriper kan også få tak i brukerens påloggings-ID, logge seg på dennes Messenger-klient eksternt og gi seg ut for å være brukeren.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen bare for Windows Messenger 4.7 på støttede versjoner av Windows XP. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows, Windows Messenger.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-042</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=123160"><strong>Sikkerhetsproblem i Microsoft Word kan tillate ekstern kjøring av kode (955048)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et offentlig rapportert sikkerhetsproblem i Microsoft Word. Dette sikkerhetsproblemet kan tillate kjøring av ekstern kode hvis en bruker åpner en spesiallaget Word-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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

#### Windows-operativsystem:

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=db455d17-435f-46d7-b2dd-5babb5a1eeb3">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1557b93b-ecba-4f42-b89d-db0ee067d65b">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa780735-5928-4c46-89a4-63a814954796">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b2ad648-7dc9-407a-99f6-f39922746027">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6257bfae-35f0-4c0e-b960-bca7aa6f86f7">Microsoft Outlook Express 5.5 Service Pack 2</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab178f7-c282-41f4-acb1-a86e6aa4c91b">Microsoft Outlook Express 6 Service Pack 1</a><br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5.1</a>
                    <br />(KB899283)<br />(Viktig)</td></tr>
              
                <tr><th colspan="7">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d313f42c-f43f-48ea-82ef-3bc33077c7fa">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69af2f30-138e-4b15-ab8d-4fce44cc0bc2">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e2125c7-52cb-4052-82a3-2d3c6a953752">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01a34aa4-a456-4efc-a93a-c3c682b0181c">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91469f2f-461c-4a67-8738-d42520427f6b">Microsoft Outlook Express 6</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f588f7e-c4ed-42a0-b157-54b1eda60474">Windows Messenger 4.7</a>
                    <br />(KB946648)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5.1</a><br />(KB899283)<br />(Viktig)</td></tr>
                <tr><td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3150c6b8-f50b-4b84-a7ce-c8daf77c080c">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4780b89e-9735-4d3f-8def-34e7337ff604">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39b41e4b-3237-409d-a818-ab0517c5e7cf">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=246b2686-e330-47a2-b4d4-68f218ad4021">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2220aece-79d2-426f-90ec-24a17470567a">Microsoft Outlook Express 6</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a5fc5457-832f-4ee8-be60-4cc8518d1c10">Windows Messenger 4.7</a>
                    <br />(KB946648)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5.1</a><br />(KB899283)<br />(Viktig)</td></tr>
              
                <tr><th colspan="7">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=828d8fdc-8534-4621-85a5-08aec255496f">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0617a5dd-dce9-4de0-b0a0-ce38efe13524">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3c2e2fd-1cb9-491b-937c-053dd59a65bf">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92a3d08f-c117-4b24-bc78-2b913d270df6">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30f2244a-f6fd-4fc1-a871-abf6958cb660">Microsoft Outlook Express 6</a>
                    <br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=302315a8-ccb2-47c2-9104-b8e1d1f49aa0">Windows Messenger 4.7</a>
                    <br />(KB954723)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5.1</a><br />(KB899283)<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a13776f-d543-41df-b904-d51e368c81cc">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=32a63f52-9fe6-48e3-bb4e-7d4dda5e0a90">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88a26b76-f7df-45c9-8ed0-7d3cd71c1987">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6bfbb6d8-5106-4adf-83cb-35ffc6e8eaf8">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3287f006-cbb2-4c6d-820c-32833e08035a">Microsoft Outlook Express 6</a>
                    <br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be94d138-7d7b-489e-baa6-e214950be6b9">Windows Messenger 4.7</a>
                    <br />(KB954723)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5.1</a><br />(KB899283)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9566493f-4260-4072-947a-527887d2cd63">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1855997e-a3be-46b1-a0bc-bb55eb0045fe">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97d0d37d-5d76-4bc3-8cbd-1e3976c82acf">Windows Internet Explorer 7</a><br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45356565-697f-41b3-9879-3edd11dbcb7e">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8570e40-355b-4a9b-933d-53ae021cbda5">Microsoft Outlook Express 6</a>
                    <br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e4b72618-536b-4a21-bd91-d91be9ca24e5">Windows Messenger 4.7</a>
                    <br />(KB954723)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8d9eb73-5f8c-4b9a-940f-9157a3b3d774">Windows Messenger 5.1</a><br />(KB899283)<br />(Moderat)</td></tr>
              
                <tr><th colspan="7">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Vista og Windows Vista Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13cba012-dd20-48f9-8e44-e4cb104c4cad">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f21a8a2-9861-4fef-9d1e-caf5f7822c1a">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6418c78f-f008-4028-beb1-5a5ea8e797a1">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3851bcf8-f971-4d38-b27f-97396854aac0">Windows Mail</a>
                    <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ead919c2-d548-47b7-9cd6-80f991266428">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa04a754-fbfb-42a7-89d2-14373e3f4742">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e03ccfb0-3ea3-4c59-adcf-9882d7086013">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bf7eb8a-b347-4661-be2d-682adc713769">Windows Mail</a>
                    <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="7">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120576">
                      <strong>MS08-046</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122772">
                      <strong>MS08-045</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120577">
                      <strong>MS08-047</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104923">
                      <strong>MS08-049</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=117705">
                      <strong>MS08-048</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=108245">
                      <strong>MS08-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-biters systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b52ff2f-d2f5-4c20-b6cf-86d86c56b0f8">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3363df6-39dc-4910-9ce5-66553155378e">Windows Server 2008 for 32-biters systemer</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0640f95e-1eee-4dd1-b4dd-2b82b7e984b9">Windows Server 2008 for 32-biters systemer</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc3c4b63-acd3-4469-8d47-e0562d99ee65">Windows Mail</a>**<br />(Lav)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-baserte systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df9814a6-5be0-4ac1-a767-a0eae8d5ee5d">Windows Internet Explorer 7</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39dd1722-412b-469d-a475-b6513764838c">Windows Server 2008 for x64-baserte systemer</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51a93538-5e94-4f81-a6e0-d497a7b4899d">Windows Server 2008 for x64-baserte systemer</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f973f54-2322-4b41-8c1a-3e712c0da8ae">Windows Mail</a>**<br />(Lav)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc3cfcb-73fe-4a6d-9595-e9d7a5b3d3f7">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9c6cd46-30ad-46ee-9c8b-d0b446e660c4">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=390da130-749d-4890-aad7-be91e15b32bb">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9226cd85-1445-4976-a126-757c5d142ffd">Windows Mail</a>
                    <br />(Lav)</td><td>Ikke relevant</td></tr>
              </table>


**\*Server Core-installasjonen av Windows Server 2008 berørt.** For støttede versjoner av Windows Server 2008 gjelder denne oppdateringen (med samme alvorlighetsgrad) enten Windows Server 2008 ble installert med installasjonsalternativet for Server Core eller ikke. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen av Windows Server 2008 ikke berørt.** Sikkerhetsproblemet som løses i denne oppdateringen berører ikke støttede versjoner av Windows Server 2008 hvis Windows Server 2008 ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="6">Microsoft Office-serier, -systemer og -komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122912">
                      <strong>MS08-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124306">
                      <strong>MS08-043</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120394">
                      <strong>MS08-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120819">
                      <strong>MS08-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=123160">
                      <strong>MS08-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Works 8</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=458985c3-9c6f-4049-81cd-0d0389c81f11">Microsoft Works 8</a>
                    <br />(KB955428)<br />(Viktig)</td><td>Ikke relevant </td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54e4031d-298f-480c-88d5-0ad3b2b62ba9">Microsoft Office Access 2000 Service Pack 3</a>
                    <br />(KB955441)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4bf8688e-e5b9-4e53-a1a1-8cf1acfdb80b">Excel 2000 Service Pack 3</a>
                    <br />(KB951582)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7c044d8-778a-4985-b25b-4f7f6e4abadd">Microsoft Office PowerPoint 2000 Service Pack 3</a>
                    <br />(KB949007)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ab323ec-9f92-453c-b7c7-9a95a9efcaea">Microsoft Office 2000 Service Pack 3</a>
                    <br />(KB921595)<br />(Kritisk)</td><td>Ikke relevant </td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34b655f8-1922-4246-94ca-ed381c3e3b13">Microsoft Office Access 2002 Service Pack 3</a>
                    <br />(KB955440)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9bbf7550-f5c4-4b9b-bd86-1e7be6c42eb5">Excel 2002 Service Pack 3</a>
                    <br />(KB951551)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8921074-7985-4d42-ac2b-d2f3b1d466ba">Microsoft Office PowerPoint 2002 Service Pack 3</a>
                    <br />(KB948995)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79">Microsoft Office XP Service Pack 3</a>
                    <br />(KB921596)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7146dfc-e1be-4d13-877b-1d9bcacc4a64">Microsoft Word 2002 Service Pack 3</a>
                    <br />(KB954463)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 2 og Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd698517-a504-427d-9e5f-fde8f102142c">Microsoft Office Access 2003 Service Pack 2 og Microsoft Office Access 2003 Service Pack 3</a>
                    <br />(KB955439)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0">Excel 2003 Service Pack 2</a>
                    <br />(KB951548)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc612e9a-bdf3-4952-8ada-0de5a50973f0">Excel 2003 Service Pack 3</a><br />(KB951548)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f">Microsoft Office PowerPoint 2003 Service Pack 2</a>**<br />(KB948988)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a7c21f0-5e0e-4dee-9710-1ce3d565913f">Microsoft Office PowerPoint 2003 Service Pack 3</a>**<br />(KB948988)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0df2f6e-1102-461d-829f-5f3e2d7eb4b3">Microsoft Office 2003 Service Pack 2</a>
                    <br />(KB921598)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a37b76-9fec-426f-8176-3c95f934efe0">Microsoft Word 2003 Service Pack 2</a>
                    <br />(KB954464)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a37b76-9fec-426f-8176-3c95f934efe0">Microsoft Word 2003 Service Pack 3</a><br />(KB954464)<br />(Viktig)</td></tr>
                <tr><td>2007 Microsoft Office System og 2007 Microsoft Office System Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd">Excel 2007</a>
                    <br />(KB951546)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2753e8d6-e156-49ef-af2d-4c521c808ffd">Excel 2007 Service Pack 1</a><br />(KB951546)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1">Microsoft Office PowerPoint 2007</a>
                    <br />(KB951338)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd618a-e9c5-4f1e-b9a5-b2e47ec98ef1">Microsoft Office PowerPoint 2007 Service Pack 1</a><br />(KB951338)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Annen Office-programvare</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122912">
                      <strong>MS08-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124306">
                      <strong>MS08-043</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120394">
                      <strong>MS08-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120819">
                      <strong>MS08-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=123160">
                      <strong>MS08-042</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Project 2002 Service Pack 1</td><td>Ikke relevant </td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf566ce6-23da-45e5-9c2b-c47331d30e79">Microsoft Office Project 2002 Service Pack 1</a>
                    <br />(KB921596)<br />(Viktig)</td><td>Ikke relevant </td></tr>
                <tr><td>SnapShot Viewer for Microsoft Access</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c22bb32-7ce3-4ff2-8366-ba2eb5135833">SnapShot Viewer for Microsoft Access</a>
                    <br />(KB957198) <br />(Kritisk)<br /></td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office PowerPoint Viewer 2003</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=911c8872-dec8-4b8e-9708-93dcabd3e036">Microsoft Office PowerPoint Viewer 2003</a>
                    <br />(KB949041)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Excel Viewer 2003 og Microsoft Office Excel Viewer 2003 Service Pack 3</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1">Microsoft Office Excel Viewer 2003</a>
                    <br />(KB951589)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7ed9e75-15f2-4950-98b3-93023ba0f4c1">Microsoft Office Excel Viewer 2003 Service Pack 3</a><br />(KB951589)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b574d906-7f09-49b0-80bf-e84dee8c4583">Microsoft Office Excel Viewer</a>
                    <br />(KB955472)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Converter Pack</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=199b08c7-6d79-4930-8f0c-31034629c485">Microsoft Office Converter Pack</a>
                    <br />(KB925256)<br />(Viktig)</td><td>Ikke relevant </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007, Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007 Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9">Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB951596)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7afdae9b-9c74-4af7-9844-0e54221ea3b9">Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007 Service Pack 1</a><br />(KB951596)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84ce5d58-0010-4945-bce9-67a41f898f2f">Microsoft Office Compatibility Pack for filformater for Word, Excel, og PowerPoint 2007</a> (KB954038)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=84ce5d58-0010-4945-bce9-67a41f898f2f">Microsoft Office Compatibility Pack Service Pack 1 for filformater for Word, Excel og PowerPoint 2007</a> (KB954038)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007 og Microsoft Office SharePoint Server 2007 Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7731749-b026-4765-808a-e151b990f0e1">Microsoft Office SharePoint Server 2007</a>*<br />(KB953397)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7731749-b026-4765-808a-e151b990f0e1">Microsoft Office SharePoint Server 2007 Service Pack 1</a>*<br />(KB953397)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 x64 Edition og Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b">Microsoft Office SharePoint Server 2007 x64 Edition</a>*<br />(KB953397)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc95ab88-2d31-44e1-a702-7cb10e83695b">Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1</a>*<br />(KB953397)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Microsoft Office for Mac</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=122912">
                      <strong>MS08-041</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=124306">
                      <strong>MS08-043</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120394">
                      <strong>MS08-051</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=120819">
                      <strong>MS08-044</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=123160">
                      <strong>MS08-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Maksimal alvorlighetsgrad for bulletin</strong>
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
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2004 for Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5">Microsoft Office 2004 for Mac</a>
                    <br />(KB956343)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebd3af0c-3f62-4d18-bf45-881655683bd5">Microsoft Office 2004 for Mac</a>
                    <br />(KB956343)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9515c70d-be80-4ade-856a-ea542f7d84e1">Microsoft Office 2008 for Mac</a>
                    <br />(KB956344)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              </table>


**\*Merknad for Microsoft Office SharePoint Server 2007, Microsoft Office SharePoint Server 2007 Service Pack 1, Microsoft Office SharePoint Server 2007 x64 Edition og Microsoft Office SharePoint Server 2007 x64 Edition Service Pack 1 (MS08-043):** Oppdateringen som er inkludert i sikkerhetsbulletinen MS08-043 gjelder for servere som har Excel Services installert, for eksempel standardkonfigurasjonen til Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 for Internett-områder. Microsoft Office SharePoint Server 2007 Standard inkluderer ikke Excel Services.

**\*\*Merknad for Microsoft Office PowerPoint 2003 Service Pack 2 og Microsoft Office PowerPoint 2003 Service Pack 3 (MS08-051):** Microsoft har publisert nye oppdateringspakker, merket versjon 2, på Microsoft Download Center. Kunder som har installert versjon 1 av denne oppdateringen fra Microsoft Download Center manuelt, må installere versjon 2 av denne oppdateringen på nytt. Kunder som har installert denne oppdateringen ved hjelp av Microsoft Update eller Office Update, trenger ikke å installere på nytt. Hvis du vil ha mer informasjon, inkludert informasjon om installasjon og andre midlertidige løsninger, kan du se bulletin [MS08-051](http://go.microsoft.com/fwlink/?linkid=120394).

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

  - [ISC/SANS](http://isc.sans.org/) for rapporten om et sikkerhetsproblem som beskrives i MS08-042
  - [VeriSign iDefense VCP](http://www.idefense.com/vcp) for rapporten om et sikkerhetsproblem som beskrives i MS08-043
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-043
  - Jeremy Funk for rapporten om et sikkerhetsproblem som beskrives i MS08-043
  - Shaun Colley hos [NGS Software](http://www.nextgenss.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-044
  - Damian Put i samarbeid med [Zero Day Initiative (ZDI)](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-044
  - En anonym forsker i samarbeid med [iDefense VCP](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-044
  - Damian Put i samarbeid med [iDefense VCP](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-044
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-045
  - Tavis Ormandy hos [Google Security Team](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-045
  - Sam Thomas i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-045
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-045
  - Jun Mao hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-046
  - Jorge Luis Alvarez Medina hos [Core Security Technologies](http://www.coresecurity.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-048
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-049
  - Haifei Li hos [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com) for rapporten om et sikkerhetsproblem som beskrives i MS08-050
  - Vadim Pogulievsky hos Finjan's [Malicious Code Research Center](http://www.finjan.com/securitylab.aspx?id=547) for rapporten om et sikkerhetsproblem som beskrives i MS08-050
  - Ruben Santamarta hos [Reversemode.com](http://reversemode.com/), i samarbeid med [iDefense Labs](http://labs.idefense.com/), for rapporten om et sikkerhetsproblem som beskrives i MS08-051
  - ADLab hos [Venustech](http://www.venustech.com.cn/) for rapporten om et sikkerhetsproblem som beskrives i MS08-051

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (12. august 2008): Publisert sammendrag av sikkerhetsbulletin.
  - V2.0 (20. august 2008): Lagt til merknad til MS08-043 under Berørt programvare og nedlastingssteder for å informere om at denne oppdateringen gjelder for servere som har Excel Services installert, for eksempel standardkonfigurasjonen til Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 for Internett-områder. Microsoft Office SharePoint Server 2007 Standard inkluderer ikke Excel Services. Det er også lagt til en merknad til MS08-051 under Berørt programvare og nedlastingssteder om at Microsoft har publisert nye oppdateringspakker, merket versjon 2, for Microsoft Office PowerPoint 2003 Service Pack 2 og Microsoft Office PowerPoint 2003 Service Pack 3 på Microsoft Download Center. Kunder som har installert versjon 1 av denne oppdateringen fra Microsoft Download Center manuelt, må installere versjon 2 av denne oppdateringen på nytt. Kunder som har installert denne oppdateringen ved hjelp av Microsoft Update eller Office Update, trenger ikke å installere på nytt.
  - V3.0 (15. oktober 2008): Inkludert oppdateringen for Snapshot Viewer for Microsoft Access (MS08-041). Brukere som har installert oppdateringen for Microsoft Office 2000 Service Pack 3, Office XP Service Pack 2 eller Office 2003 Service Pack 2 eller Office 2003 Service Pack 3, trenger ikke å installere oppdateringen på nytt for den frittstående Snapshot Viewer for Microsoft Access.

*Built at 2014-04-18T01:50:00Z-07:00*

