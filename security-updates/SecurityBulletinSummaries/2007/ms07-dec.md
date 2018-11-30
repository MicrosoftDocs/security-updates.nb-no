---
title: Sammendrag av Microsofts sikkerhetsbulletiner for desember 2007
TOCTitle: MS07-DEC
ms:assetid: ms07-dec
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms07-dec(v=Security.10)
ms:contentKeyID: 61315178
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for desember 2007

Publisert: 11. desember 2007 | Oppdatert: 16. juli 2008

**Versjon:** 2.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i desember 2007.

I forbindelse med utgivelsen av bulletinene for desember 2007 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 6. desember 2007. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 12. desember 2007 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for desember på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344696&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (3)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-064</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=104988"><strong>Sikkerhetsproblemer i DirectX kan tillate ekstern kjøring av kode (941568)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft DirectX. Disse sikkerhetsproblemene kan føre til kjøring av kode hvis en bruker åpner en spesiallaget fil brukt til direkteavspilling av media i DirectX. Hvis en bruker er logget på med administrative rettigheter, kan en angriper som klarte å utnytte dette sikkerhetsproblemet, ta kontroll over det berørte systemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke en omstart, unntatt i enkelte situasjoner.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows, DirectX, DirectShow.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-068</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=99075"><strong>Sikkerhetsproblem i Windows Media-filformater kan tillate ekstern kjøring av kode (941569 og 944275)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows Media Format. Dette sikkerhetsproblemet kan føre til ekstern kjøring av kode hvis en bruker åpner en spesiallaget fil i Windows Media Format Runtime. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke en omstart, unntatt i enkelte situasjoner.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows, Windows Media Format Runtime. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-069</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=101160"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (942615)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhetsoppdateringen løser fire personlig rapporterte sikkerhetsproblemer. Den mest alvorlige sikkerhetspåvirkningen kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows, Internet Explorer. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig (4)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-063</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=104920"><strong>Sikkerhetsproblem i SMBv2 kan tillate ekstern kjøring av kode (942624)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i SMB (servermeldingsblokk) versjon 2 (SMBv2). Sikkerhetsproblemet kan gi en angriper tilgang til å manipulere data som overføres via SMBv2, som kan tillate ekstern kjøring av kode i domenekonfigurasjoner med SMBv2.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-065</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=94666"><strong>Sikkerhetsproblem i Message Queuing kan føre til ekstern kjøring av kode (937894)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Message Queuing-tjenesten (MSMQ) som kan tillate ekstern kjøring av kode i implementeringer på Microsoft Windows 2000 Server eller rettighetsutvidelse i implementeringer på Microsoft Windows 2000 Professional og Windows XP. En angriper må ha gyldig påloggingsinformasjon for å utnytte sikkerhetsproblemet med rettighetsutvidelse på Microsoft Windows 2000 Professional og Windows XP. En angriper kan deretter installere programmer, vise, endre eller slette data eller opprette nye kontoer.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-066</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=104898"><strong>Sikkerhetsproblem i Windows-kjernen kan tillate rettighetsutvidelse (943078)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows-kjernen. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fulle administrative rettigheter.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-067</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=104987"><strong>Sikkerhetsproblem i Macrovision-driver kan føre til rettighetsutvidelse (944653)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser ett publisert sikkerhetsproblem. Det er et sikkerhetsproblem som omfatter lokal rettighetsutvidelse i den feilaktige måten Macrovision-driveren behandler konfigurasjonsparametere på. En lokal angriper som klarer å utnytte dette sikkerhetsproblemet, kan få kontroll over systemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fulle administrative rettigheter.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Maksimal alvorlighetsgrad</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Følger av sikkerhetsproblemet</strong></td>
<td style="border:1px solid black;">Lokal rettighetsutvidelse</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>Søking</strong></td>
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

**Hvordan bruker jeg denne tabellen?**  

Bruk tabellen til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det finnes nødvendige sikkerhetsoppdateringer. Hvis et program eller en programvarekomponent er oppført, vil virkningen av sikkerhetsproblemet også være oppført i tillegg til en hyperkobling til den tilgjengelige programvareoppdateringen.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

**Berørt programvare og nedlastingssteder**

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;">Detaljer        </th>
    <th style="border:1px solid black;">Detaljer        </th>
    <th style="border:1px solid black;">Detaljer        </th>
    <th style="border:1px solid black;">Detaljer        </th>
    <th style="border:1px solid black;">Detaljer        </th>
    <th style="border:1px solid black;">Detaljer        </th>
    <th style="border:1px solid black;">Detaljer        </th>
  </tr>
            <tr><td style="border:1px solid black;">
                <strong>Bulletinidentifikator</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104920">
                  <strong>MS07-063</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104988">
                  <strong>MS07-064</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=94666">
                  <strong>MS07-065</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104898">
                  <strong>MS07-066</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104987">
                  <strong>MS07-067</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=99075">
                  <strong>MS07-068</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=101160">
                  <strong>MS07-069</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">
                <strong>Maksimal alvorlighetsgrad</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Viktig</strong>
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
                  <strong>Kritisk</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Kritisk</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="8" style="border:1px solid black;">Windows-operativsystem:</th></tr>
          
            <tr><td style="border:1px solid black;">Microsoft Windows 2000 Server Service Pack 4 og Microsoft Windows 2000 Professional Service Pack 4</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bda9d0b4-f7cb-4d9d-b030-043d7437734b">Viktig</a>
              </td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09d4e6ae-5d19-4f11-bb7e-60cee8263bc8">Moderat</a>
              </td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7d368d0-f7bf-4946-a4a6-3e88315e5317">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f4fa8e9-fcf2-4daf-93c0-8bb267da69aa">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f84f5e2-1dd8-4882-b796-444ab70b6b02">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f416b71-783f-4cbc-9b85-9a9be7daa0d7">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 SP1 for Itanium-based Systems</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 SP2 for Itanium-based Systems</td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td /><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Vista</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d22a9ee-cc08-4b2d-af4e-55d326f82761">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9787619f-1297-411e-8b9c-3ad3e6a99797">Viktig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05a9501c-4da3-4fa1-901e-99cb262e5e36">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f382050-8df6-43aa-82e9-8fad5ff8ecec">Viktig</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td></tr>
          
            <tr><th colspan="8" style="border:1px solid black;">Operativsystemkomponenter for Windows</th></tr>
          
            <tr><td style="border:1px solid black;">DirectX 7.0 på Microsoft Windows 2000 Service Pack 4</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06196774-5a11-4525-b53c-8cb000738949">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">DirectX 8.1 på Microsoft Windows 2000 Service Pack 4</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ccb872bd-fc06-4a3f-ac70-3c9a42d57b37">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">DirectX 9.0* på Microsoft Windows 2000 Service Pack 4</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03b14ce0-5189-4803-8151-6ac5cb6a9179">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">DirectX 9.0* på Windows XP Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04a8f8d3-69f9-4445-baab-f45616a6b9b7">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">DirectX 9.0* på Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f096c500-e765-4e75-8443-7ffec4ddf149">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">DirectX 9.0* på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d80a295a-baf9-4981-8a28-1b4207ecc5f7">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">DirectX 9.0* på Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=378086ea-60b8-409f-970a-fcfd62025150">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">DirectX 9.0* på Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e6ea4bb-9f4f-46fb-9d51-e20b15e61a89">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">DirectX 10.0 på Windows Vista</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bfa571bc-e43f-45e3-bc98-4086985c99aa">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">DirectX 10.0 på Windows Vista x64 Edition</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d8803da-108b-4b9d-a039-84932dce8e42">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 5.01 Service Pack 4 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3bd16ea-5d69-4ae3-84b3-ab773052ceeb">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 6 Service Pack 1 når det er installert på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc8edf05-262a-4d1d-b196-4fc1a844970c">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 6 for Windows XP Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e4ebafc-34c3-4dc7-b712-152c611d3f0a">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 6 for Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5a5af23-30fb-4e47-94bd-3b05b55c92f2">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 6 for Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf466060-a585-4c2e-a48d-70e080c3bbe7">Moderat</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 6 for Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=074697f2-18c8-4521-bbf7-1d0e7395d27d">Moderat</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 6 for Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b3f390a6-0361-4553-b627-5e7ad6bf5055">Moderat</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 for Windows XP Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b15a6506-02dd-43c2-aef4-e10c1c76ee97">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 7 for Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c092a6bb-8e62-4d90-bdb1-5f3a15968f75">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 for Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34759c10-16a5-42a2-974d-9d532fb5a0a7">Moderat</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 7 for Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dccce5a-7562-448b-a345-cf1cc758e35c">Moderat</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 for Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8414f3fb-216a-4d46-b590-4c1f304dff91">Moderat</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Internet Explorer 7 i Windows Vista</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26d303da-bb2e-4555-96f1-becb0e277341">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Internet Explorer 7 i Windows Vista x64 Edition</td><td /><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c5e88e0b-a4c2-4690-91d9-326800030a16">Kritisk</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Media Format Runtime 7.1 på Microsoft Windows 2000 Service Pack 4 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Media Format Runtime 9 på Microsoft Windows 2000 Service Pack 4 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eecdf2ce-9aa7-4f0c-b62b-2fa7a32f369e">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Media Format Runtime 9 på Windows XP Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Media Format Runtime 9.5 på Windows XP Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Media Format Runtime 9.5 på Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81f20b45-dfc7-4ddf-a4b4-6c0e9476ed51">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Media Format Runtime 9.5 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fea7da8-a7f3-4786-97c2-fb5ea7018159">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Media Format Runtime 9.5 på Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Media Format Runtime 9.5 x64 Edition på Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffc69c76-02f1-4b15-8ec1-dab8c7e33bd4">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Media Format Runtime 9.5 x64 Edition på Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72d2ca0e-da81-45ee-9321-4970b80f4a5a">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Media Format Runtime 11 på Windows XP Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bece702a-6e61-433e-8275-20f4e84f2c92">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Media Format Runtime 11 på Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2 (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1037b224-ac89-4efd-b189-6f3da77a88e6">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Media Format Runtime 11 på Windows Vista (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a98ef96-bc2e-42b7-9a24-c82c8fb379db">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Media Format Runtime 11 på Windows Vista x64 Edition (KB941569)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ce02c95-d695-4f14-9fb3-30c83a9cfb9c">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Media Services 9.1 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2 (KB944275)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=096711d4-ce01-45d0-9c2d-ebfa5c671b9f">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Media Services 9.1 x64 Edition på Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2 (KB944275)</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c23800-5aaa-455b-96bf-4ead4dfdd95d">Kritisk</a>
              </td><td /></tr>
          </table>


**Merknader**

**\[1\]** Det finnes en sikkerhetsoppdatering for dette operativsystemet. Hvis du vil ha mer informasjon, ser du etter den berørte programvaren eller komponenten i tabellen og i den aktuelle sikkerhetsbulletinen. 

**\***Inkluderer DirectX 9.0a, DirectX 9.0b og DirectX 9.0c

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer er tilgjengelig fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) og [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Veiledning for søking og distribusjon**

Microsoft har gjort tilgjengelig en veiledning for søking og distribusjon for denne månedens sikkerhetsoppdateringer. Veiledningen vil også hjelpe IT-ansvarlige til å forstå hvordan de kan bruke ulike verktøy til å distribuere sikkerhetsoppdateringen, for eksempel Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office-søkeverktøyet, Microsoft Systems Management Server (SMS) og Extended Security Update Inventory Tool (ESUIT). Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Obs\!** Etter 9. oktober 2007 oppdateres ikke lenger MSSecure.XML-filen som brukes av MBSA 1.2.1. Etter denne datoen blir det ikke lagt til nye sikkerhetsoppdateringer til MSSecure.XML-filen som brukes av MBSA 1.2.1, og det blir ikke utgitt flere versjoner av Enterprise Scan Tool. Dette berører ikke Security Update Inventory Tool (SUIT) eller Extended Security Update Inventory Tool (ESUIT) for SMS 2.0 og SMS 2003. Gå til [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134) hvis du vil ha mer informasjon.

**Windows Server Update Services**

Med Windows Server Update Services (WSUS) kan administratorer raskt og effektivt distribuere de nyeste viktige oppdateringene og sikkerhetsoppdateringene for Windows 2000 og nyere operativsystemer, Office XP og nyere, Exchange Server 2003 og SQL Server 2000, til Windows 2000 og nyere operativsystemer.

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 for å distribuere sikkerhetsoppdateringer, kan du gå til [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Brukere av SMS 2.0 kan også bruke [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) for å få hjelp til å distribuere sikkerhetsoppdateringer. Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer og Microsoft Office-søkeverktøyet til å utøve omfattende støtte for oppdaging og distribusjon av sikkerhetsbulletiner. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til å installere disse oppdateringene.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

For denne måneden:

  - Microsoft har utgitt tre **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer for 2007 Microsoft Office Service Pack 1 på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har utgitt tre **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer for Windows og Windows SharePoint Services 3.0 Service Pack 1 på Windows Update (WU) og WSUS.

Vær oppmerksom på at denne informasjonen **bare** gjelder **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update, Windows Update og Windows Server Update Services som ble utgitt samme dag som sammendraget av sikkerhetsbulletinen. Det gis **ikke** informasjon om **ikke-sikkerhetsrelaterte** oppdateringer som utgis andre dager.

#### Sikkerhetsstrategier og -sone

**Strategier for behandling av oppdateringer**

På webområdet [Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) finner du mer informasjon om Microsofts anbefalinger for gode fremgangsmåter for å bruke sikkerhetsdata.

**Få tak i andre sikkerhetsoppdateringer**

Oppdateringer for andre sikkerhetsproblemer finnes på følgende steder:

  - Sikkerhetsoppdateringer finnes på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".
  - Oppdateringer for forbrukerplattformer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan få sikkerhetsoppdateringene som tilbys på Windows Update denne måneden, fra Download Center på Security and Critical Releases ISO CD Image-filer. Hvis du vil ha mer informasjon, kan du se [Microsoft Knowledge Base-artikkel 913086](http://support.microsoft.com/kb/913086).

**Sikkerhetsmiljø for IT-eksperter**

Lær hvordan du kan forbedre sikkerheten og optimalisere IT-infrastrukturen, og delta sammen med andre IT-eksperter i diskusjoner om sikkerhet i [sikkerhetssonen for IT-eksperter](http://go.microsoft.com/fwlink/?linkid=21164).

#### Takk til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for samarbeidet med å beskytte kundene:

  - Jun Mao hos [VeriSign iDefense Labs](http://labs.idefense.com/) for samarbeidet i forbindelse med et problem som beskrives i MS07-064
  - Peter Winter Smith hos [NGSSoftware](http://www.ngssoftware.com/) for samarbeidet i forbindelse med et problem som beskrives i MS07-064
  - Jung-hyung Lee hos [AhnLab](http://global.ahnlab.com/) for samarbeidet i forbindelse med forandringer i dybdeforsvar for DirectX som beskrives i MS07-064
  - [Zero Day Initiative](http://www.zerodayinitiative.com/) for samarbeidet i forbindelse med et problem som beskrives i MS07-065
  - Venustech hos [ADLABS](http://www.venustech.com.cn/) for samarbeidet i forbindelse med et problem som beskrives i MS07-065
  - Thomas Garnier hos [SkyRecon](http://www.skyrecon.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-066
  - Ryan Smith hos [ISS X-Force](http://xforce.iss.net/) for samarbeidet i forbindelse med et problem som beskrives i MS07-068
  - Alex Wheeler hos [ISS X-Force](http://xforce.iss.net/) for samarbeidet i forbindelse med et problem som beskrives i MS07-068
  - Peter Vreugdenhil i samarbeid med [iDefense VCP](http://idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-069
  - En anonym forsker i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-069.
  - Sam Thomas i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-069.
  - Peter Vreugdenhil i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-069.

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (11. desember 2007): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (12. desember 2007): Bulletin oppdatert for å informere om endringer i det kortfattede sammendraget av MS07-065- og MS-07-067-bulletinene.
  - V1.2 (23. januar 2008): Bulletin oppdatert for å informere om endringer i den berørte programvaren i MS07-064-bulletinen.
  - V2.0 (16. juli 2008): Bulletin oppdatert for å informere om endringer i den berørte programvaren i MS07-064-bulletinen.

*Built at 2014-04-18T01:50:00Z-07:00*

