---
title: Sammendrag av Microsofts sikkerhetsbulletiner for oktober 2007
TOCTitle: MS07-OCT
ms:assetid: ms07-oct
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms07-oct(v=Security.10)
ms:contentKeyID: 61315186
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for oktober 2007

Publisert: 9. oktober 2007

**Versjon:** 1.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i oktober 2007.

I forbindelse med utgivelsen av bulletinene for oktober 2007 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 4. oktober 2007. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 10. oktober 2007 kl 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for oktober på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344692&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (4)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-055</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=94668"><strong>Sikkerhetsproblem i Kodak Image Viewer kan tillate ekstern kjøring av kode (923810)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Det er oppdaget et sikkerhetsproblem som kan forårsake ekstern kjøring av kode, på grunn av måten Kodak Image Viewer, som tidligere ble kalt Wang Image Viewer, behandler spesiallagde bildefiler på. Sikkerhetsproblemet kan tillate at en angriper kjører kode eksternt på det berørte systemet. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-056</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=96629"><strong>Sikkerhetsoppdatering for Outlook Express og Windows Mail (941202)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Sikkerhetsproblemet kan tillate ekstern kjøring av kode på grunn av at et NNTP-svar håndteres feilaktig. En angriper kan utnytte dette sikkerhetsproblemet ved å opprette en spesiallaget webside.</td>
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
<td>Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke en omstart, unntatt i enkelte situasjoner og for Windows Vista.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows, Outlook Express, Windows Mail.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-057</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=95045"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (939653)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser tre personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem. Sikkerhetsproblemet med mest alvorlige sikkerhetspåvirkning kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows, Internet Explorer.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-060</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=101656"><strong>Sikkerhetsproblem i Microsoft Word kan tillate ekstern kjøring av kode (942695)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Word som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Word-fil med en misformet streng. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td><strong>Office.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig\! (2)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-058</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91031"><strong>Sikkerhetsproblem i RPC kan føre til tjenestenekt (933729)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne viktige oppdateringen løser et personlig rapportert sikkerhetsproblem. Det finnes et sikkerhetsproblem som kan forårsake tjenestenekt i RPC-fasiliteten (Remote Procedure Call) på grunn av en svikt i kommunikasjonen med NTLM-sikkerhetsleverandøren under godkjenning av RPC-forespørsler.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Tjenestenekt</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-059</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=95631"><strong>Sikkerhetsproblem i Windows SharePoint Services 3.0 og Office SharePoint Server 2007 kan føre til rettighetsutvidelse på SharePoint-området (942017)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et offentlig rapportert sikkerhetsproblem i Microsoft Windows SharePoint Services 3.0 og Microsoft Office SharePoint Server 2007. Sikkerhetsproblemet kan tillate at en angriper kjører vilkårlig skript som kan resultere i rettighetsutvidelse på SharePoint-området, i motsetning til rettighetsutvidelse i arbeidsstasjons- eller servermiljøet. Dette sikkerhetsproblemet kan også tillate at en angriper kjører vilkårlig skript for å endre en brukers hurtigbuffer, som kan føre til tilgjengeliggjøring av informasjon ved arbeidsstasjonen.</td>
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
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke en omstart, unntatt i enkelte situasjoner.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows, Office.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

**Hvordan bruker jeg denne tabellen?**

Bruk tabellen til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det finnes nødvendige sikkerhetsoppdateringer. Hvis et program eller en programvarekomponent er oppført, vil virkningen av sikkerhetsproblemet også være oppført i tillegg til en hyperkobling til den tilgjengelige programvareoppdateringen.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

**Berørt programvare og nedlastingssteder**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Detaljer        </th>
    <th>Detaljer        </th>
    <th>Detaljer        </th>
    <th>Detaljer        </th>
    <th>Detaljer        </th>
    <th>Detaljer        </th>
  </tr>
            <tr><td>
                <strong>Bulletinidentifikator</strong>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=94668">
                  <strong>MS07-055</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=96629">
                  <strong>MS07-056</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=95045">
                  <strong>MS07-057</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=101656">
                  <strong>MS07-060</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91031">
                  <strong>MS07-058</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=95631">
                  <strong>MS07-059</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Maksimal alvorlighetsgrad</strong>
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
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Viktig</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="7">Windows-operativsystem:</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29763117-c2dc-4746-b31e-0b27350118e6">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7fb9a8-1d8d-4307-b5c6-bc6c28ee09de">Lav</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be52f740-e9c9-4228-95c0-00995213bbd0">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1fee539c-ab86-4298-b6f4-22ce31ee7b8b">Viktig</a>
              </td><td /></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td /><td /><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac7bd100-0a03-426b-adc8-0516c602a280">Viktig</a>
              </td><td /></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b">Viktig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a5c9e5d-4908-48bf-9346-745b4c6f6d4e">Kritisk</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=011593a0-f37e-4578-bee1-a985639b521b">Viktig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Server 2003 x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859">Viktig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9bb8df5-f39e-4473-9d0c-e84430c7f859">Viktig</a>
              </td><td>
                <strong>[1]</strong>
              </td></tr>
            <tr><td>Windows Server 2003 SP1 for Itanium-based Systems</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Server 2003 SP2 for Itanium-based Systems</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492ae87c-047c-45c1-ad04-ee36352de85b">Viktig</a>
              </td><td /></tr>
            <tr><td>Windows Vista</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ceca7f8c-7b56-48fc-8c17-87ffadf25629">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7625f5a4-2921-41ce-986d-4cc0c264135c">Viktig</a>
              </td><td /></tr>
          
            <tr><th colspan="7">Operativsystemkomponenter for Windows</th></tr>
          
            <tr><td>Outlook Express 5.5 Service Pack 2 på Microsoft Windows 2000 Service Pack 4</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5aa009c9-4edc-4f34-989b-0493549649e8">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b537115d-611c-4486-960c-08d2df450579">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Outlook Express 6 på Windows XP Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ed7f466-78c7-4251-ba24-8ae71ad54e18">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 på Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6468a552-2194-4866-97d5-ff77ae205eea">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Outlook Express 6 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=708926e4-f8af-4533-8747-22d6536ebd66">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 på Windows Server 2003 x64 Edition og Outlook Express 6 på Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26720f5a-d7e9-44b9-9330-2e9faa4af0d9">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Internet Explorer 6 på Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8844fbb-5b2c-41f3-80f1-dce563aa7cb7">Kritisk</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows Mail i Windows Vista</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6ac8d93-adc3-4ec3-bad1-4990bd7d52b4">Viktig</a>
              </td><td /><td /><td /><td /></tr>
            <tr><td>Windows Mail i Windows Vista x64 Edition</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34aaf9dd-4d63-43e2-b631-bbf492d56a26">Viktig</a>
              </td><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 5.01 Service Pack 4 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=95827f3f-a984-4e34-a949-d16a0614121a">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 6 Service Pack 1 når det er installert på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=df3ba596-7c5b-4151-9884-6957aa884aab">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 for Windows XP Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=513a8320-6d36-4fc9-a38a-867192b55b53">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 6 for Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae8a26d8-1910-4b8c-8a73-6e2fa6b5b29f">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 for Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aefaa38-8757-4e6e-8924-57cabd1c2fc3">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 6 for Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88aba9dd-653b-4cdf-a513-cca32a7d7e41">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 for Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=309a8f10-c7ea-4961-a969-092b0c4d7bbc">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 for Windows XP Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ca0ac93-bf51-40fe-a1ba-cb3e0a36d8b5">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 for Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbd284d0-2664-42a4-ad16-a0535244c81c">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 for Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a31c451-32f4-4551-ae45-d600f8b3b11b">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 for Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1915633-d181-4ca1-a4f0-7ca0f865aa72">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 for Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=093a2250-3be3-494f-80e0-89ca7217030f">Moderat</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 i Windows Vista</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=86392e8d-098c-427f-a233-699cdb9375ae">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr><td>Internet Explorer 7 i Windows Vista x64 Edition</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62490e6d-0a21-4a15-90bd-63ca8f8886b6">Kritisk</a>
              </td><td /><td /><td /></tr>
            <tr class="alternateRow"><td>Windows SharePoint Services 3.0 på Windows Server 2003 Service Pack 1 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877">Viktig</a>
              </td></tr>
            <tr><td>Windows SharePoint Services 3.0 på Windows Server 2003 Service Pack 2 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=76fc2225-2802-46e5-a294-a842e3841877">Viktig</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows SharePoint Services 3.0 på Windows Server 2003 x64 Edition (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055">Viktig</a>
              </td></tr>
            <tr><td>Windows SharePoint Services 3.0 på Windows Server 2003 x64 Edition Service Pack 2 (KB934525)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=667335dd-df2e-4f14-a130-5758701be055">Viktig</a>
              </td></tr>
          
            <tr><th colspan="7">Microsoft Office</th></tr>
          
            <tr class="alternateRow"><td>Microsoft Word 2000 Service Pack 3</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b3072fb-5933-47f7-a498-13a93e268e57">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Word 2002 Service Pack 3</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6b787bb-03ff-4f67-8b69-6011fb18ba75">Viktig</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Microsoft Office 2004 for Mac</td><td /><td /><td /><td>
                <a Anchor="Office2004" Target="" runat="server" href="http://www.microsoft.com/mac/downloads.aspx">Viktig</a>
              </td><td /><td /></tr>
            <tr><td>Microsoft Office SharePoint Server 2007 (KB937832)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aaea9695-f541-4c4c-9107-81ead5cfc8c9">Viktig</a>
              </td></tr>
            <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 x64 Edition (KB937832)</td><td /><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d319164-d133-4493-be27-1aeda62362c4">Viktig</a>
              </td></tr>
          </table>


**Merknader**

**\[1\]** Det finnes en sikkerhetsoppdatering for dette operativsystemet. Hvis du vil ha mer informasjon, ser du etter den berørte programvaren eller komponenten i tabellen og i den aktuelle sikkerhetsbulletinen. 

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer er tilgjengelig fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) og [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Veiledning for søking og distribusjon**

Microsoft har gjort tilgjengelig en veiledning for søking og distribusjon for denne månedens sikkerhetsoppdateringer. Veiledningen vil også hjelpe IT-ansvarlige til å forstå hvordan de kan bruke ulike verktøy til å distribuere sikkerhetsoppdateringen, for eksempel Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office-søkeverktøyet, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool og Enterprise Update Scan Tool (EST). Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

Når MBSA 1.2.1 ikke finner en oppdatering for en spesifikk sikkerhetsoppdatering, utgir Microsoft en versjon av Enterprise Update Scan Tool (EST) for den sikkerhetsoppdateringen. Du finner mer informasjon om EST ved å gå til [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Obs\!** Etter 9. oktober 2007 oppdateres ikke lenger MSSecure.XML-filen som brukes av MBSA 1.2.1. Etter denne datoen blir det ikke lagt til nye sikkerhetsoppdateringer til MSSecure.XML-filen som brukes av MBSA 1.2.1, og det blir ikke utgitt flere versjoner av Enterprise Scan Tool. Du finner mer informasjon på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

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

  - Microsoft har utgitt tre **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har utgitt én **ikke-sikkerhetsrelatert**, høyt prioritert oppdatering for Windows på Windows Update (WU).

Vær oppmerksom på at denne informasjonen **bare** gjelder **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update, Windows Update og Windows Server Update Services som ble utgitt samme dag som sammendraget av sikkerhetsbulletinen. Det gis **ikke** informasjon om **ikke-sikkerhetsrelaterte** oppdateringer som utgis andre dager.

#### Sikkerhetsstrategier og -sone

**Strategier for behandling av oppdateringer**

På webområdet [Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) finner du mer informasjon om Microsofts anbefalinger for gode fremgangsmåter for å bruke sikkerhetsdata.

**Få tak i andre sikkerhetsoppdateringer**

Oppdateringer for andre sikkerhetsproblemer finnes på følgende steder:

  - Sikkerhetsoppdateringer finnes på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".
  - Oppdateringer for forbrukerplattformer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan få sikkerhetsoppdateringene som tilbys på Windows Update denne måneden, fra Download Center på Security and Critical Releases ISO CD Image-filer. Hvis du vil ha mer informasjon, kan du se [Microsoft Knowledge Base-artikkel 913086](http://support.microsoft.com/kb/913086).

**Sikkerhetsmiljø for IT-eksperter**

Lær hvordan du kan forbedre sikkerheten og optimalisere IT-infrastrukturen, og delta sammen med andre IT-eksperter i diskusjoner om sikkerhet i [sikkerhetssonen for IT-eksperter](http://go.microsoft.com/fwlink/?linkid=21164).

#### Takk til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for samarbeidet med å beskytte kundene:

  - Cu Fang for rapporten om et sikkerhetsproblem som beskrives i MS06-055.
  - Rita Schappler hos [Global 360](http://www.global360.com/products/g360_imaging/default.asp) for å ha samarbeidet med oss om et sikkerhetsproblem som beskrives i MS07-055
  - Greg MacManus hos [VeriSign iDefense Labs](http://www.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-056.
  - Pierre Geyer hos next.motion OHG for rapporten om et sikkerhetsproblem som beskrives i MS07-057
  - Carsten H. Eiram hos [Secunia Research](http://secunia.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-057
  - Jakob Balle hos [Secunia Research](http://secunia.com/) for den første rapporten om et sikkerhetsproblem som beskrives i MS07-057
  - [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS07-058
  - Liu Kun-Hao hos Information & Communication Security Technology Center for rapporten om et sikkerhetsproblem som beskrives i MS07-060

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (9. oktober 2007): Publisert sammendrag av sikkerhetsbulletin.

*Built at 2014-04-18T01:50:00Z-07:00*

