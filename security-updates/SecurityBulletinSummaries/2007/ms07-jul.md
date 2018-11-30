---
title: Sammendrag av Microsofts sikkerhetsbulletiner for juli 2007
TOCTitle: MS07-JUL
ms:assetid: ms07-jul
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms07-jul(v=Security.10)
ms:contentKeyID: 61315181
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for juli 2007

Publisert: 10. juli 2007

**Versjon:** 1.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i juli 2007.

I forbindelse med utgivelsen av bulletinene for juli 2007 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 5. juli 2007. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 11. juli 2007 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for juli på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032343783&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (3)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-036</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=93447"><strong>Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (936542)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne kritiske oppdateringen løser et offentlig sikkerhetsproblem og to personlig rapporterte sikkerhetsproblemer, i tillegg til andre sikkerhetsproblemer som ble oppdaget under undersøkelsen. Disse sikkerhetsproblemene kan tillate kjøring av ekstern kode hvis en bruker åpner en spesiallaget Excel-fil. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever ikke omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Office, Excel</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-039</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=93365"><strong>Sikkerhetsproblem i Windows Active Directory kan tillate ekstern kjøring av kode (926122)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i implementeringer av Active Directory på Windows 2000 Server og Windows Server 2003 som kan tillate ekstern kjøring av kode eller føre til tjenestenekt. Angrep som forsøker å utnytte disse sikkerhetsproblemene, vil mest sannsynlig føre til en situasjon med tjenestenekt (denial of service). Ekstern kjøring av kode kan imidlertid være mulig. På Windows Server 2003 må en angriper ha gyldig påloggingsinformasjon for å kunne utnytte dette sikkerhetsproblemet. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data eller opprette nye kontoer.</td>
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
<td style="border:1px solid black;"><strong>Windows</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-040</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=91233"><strong>Sikkerhetsproblemer i .NET Framework kan tillate ekstern kjøring av kode (931212)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne oppdateringen løser tre personlig rapporterte sikkerhetsproblemer. To av disse sikkerhetsproblemene kan tillate ekstern kjøring av kode på klientsystemer som har installert .NET Framework, og ett kan tillate tilgjengeliggjøring av informasjon på webservere som kjører ASP.NET. I alle tilfeller av ekstern kjøring av kode er brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;"><strong>.NET Framework</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig\! (2)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-037</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=93448"><strong>Sikkerhetsproblem i Microsoft Office Publisher kan tillate ekstern kjøring av kode (936548)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser ett publisert sikkerhetsproblem. Dette sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Microsoft Office Publisher-fil. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Det kreves samhandling med bruker for å utnytte dette sikkerhetsproblemet.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Oppdateringen krever ikke omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Office, Publisher</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-041</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=93706"><strong>Sikkerhetsproblem i Microsoft Internet Information Services kan tillate ekstern kjøring av kode (939373)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Dette sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en angriper sender en spesiallaget URL-forespørsel til en webside som Internet Information Services (IIS) 5.1 på Windows XP Professional Service Pack 2 er vert for. IIS 5.1 er ikke en del av en standardinstallasjon av Windows XP Professional Service Pack 2. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over det berørte systemet.</td>
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
<td style="border:1px solid black;"><strong>Windows XP Professional</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Moderat (1)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsofts sikkerhetsbulletin MS07-038</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=91033"><strong>Sikkerhetsproblem i Windows Vista-brannmuren kan tillate tilgjengeliggjøring av informasjon (935807)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne moderate sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Dette sikkerhetsproblemet kan føre til at inngående uoppfordret nettverkstrafikk får tilgang til et nettverksgrensesnitt. En angriper kan samle inn informasjon om den berørte verten.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows</strong> <strong>Vista</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
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
  </tr>
            <tr><td style="border:1px solid black;">
                <strong>Bulletinidentifikator</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=93447">
                  <strong>MS07-036</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=93448">
                  <strong>MS07-037</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91033">
                  <strong>MS07-038</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=93365">
                  <strong>MS07-039</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91233">
                  <strong>MS07-040</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=93706">
                  <strong>MS07-041</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">
                <strong>Maksimal alvorlighetsgrad</strong>
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
                  <strong>Moderat</strong>
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
              </td></tr>
          
            <tr><th colspan="7" style="border:1px solid black;">Berørt programvare for Windows</th></tr>
          
            <tr><td style="border:1px solid black;">Windows 2000 Service Pack 4</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows 2000 Server Service Pack 4</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=812e62c5-6e19-4b3b-8a10-861b871e1b41">Kritisk</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows XP Service Pack 2</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional Service Pack 2</td><td /><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fccbfe90-f838-47df-8310-352e2fb47132">Viktig</a>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28e84603-8159-4429-aaff-a1020531e84f">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=107902f9-be94-457f-a936-519efbd64779">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 SP1 for Itanium-based Systems</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 SP2 for Itanium-based Systems</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5e5b425-fe7d-49d5-973f-f3fd7a1e04eb">Viktig</a>
              </td><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Vista</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9b64746-6afa-4a30-833d-e058e000c821">Moderat</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0df5d190-3ad7-42d5-8629-43c47ec450cb">Moderat</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="7" style="border:1px solid black;">Berørte operativsystemkomponenter for Windows</th></tr>
          
            <tr><td style="border:1px solid black;">Microsoft .NET Framework 1.0<br />(KB928367)</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91d7afe4-069b-4ce8-976e-9a01345a8603">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Microsoft .NET Framework 1.0<br />(KB930494)</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=829a2c5b-11ec-4ed7-91ab-6961034147bc">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Microsoft .NET Framework 1.1<br />(KB928366)</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=281fb2cd-c715-4f05-a01f-0455d2d9ebfb">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Microsoft .NET Framework 1.1<br />(KB933854)</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2495e656-1e0a-4b83-90da-821e68067a71">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Microsoft .NET Framework 1.1<br />(KB929729)</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7eea368d-7b82-4583-8537-30351718a4e9">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Microsoft .NET Framework 2.0<br />(KB928365)</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba3ceb78-8e1b-4c38-adfd-e8bc95ae548d">Kritisk</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Microsoft .NET Framework 2.0<br />(KB929916)</td><td /><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cbc9f3cf-c3c3-45c4-82e3-e11398bc2cd2">Kritisk</a>
              </td><td /></tr>
          
            <tr><th colspan="7" style="border:1px solid black;">Berørt Office-programvare:</th></tr>
          
            <tr class="alternateRow"><td style="border:1px solid black;">Excel 2000 Service Pack 3</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=83d94d8e-dda6-4d74-b40d-476c2f0a3af4">Kritisk</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">Excel 2003 Service Pack 2</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d93c0ce-5124-4234-ba84-3c27005e010f">Viktig</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Excel 2003 Viewer</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11f42977-8828-494a-a183-d1aba827b708">Viktig</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">Excel 2007</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9ab28283-0320-4527-b033-5e80ef32cd34">Viktig</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Office Compatibility Pack for Word-, Excel- og PowerPoint 2007-filformater</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e592ae5b-09ac-4f5b-b457-a54c9850ad4a">Viktig</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td style="border:1px solid black;">Publisher 2007</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=25d272e7-f2dd-4342-92be-7ebc2e770b44">Viktig</a>
              </td><td /><td /><td /><td /></tr>
          </table>


**Merknader**

**\[1\]** Det finnes en sikkerhetsoppdatering for dette operativsystemet. Hvis du vil ha mer informasjon, ser du etter den berørte programvaren eller komponenten i tabellen og i den aktuelle sikkerhetsbulletinen. 

****

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer er tilgjengelig fra [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) og [Office Update](http://go.microsoft.com/fwlink/?linkid=21135). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering". Sist men ikke minst kan sikkerhetsoppdateringer lastes ned fra Windows Update-katalogen. Du finner mer informasjon om Windows Update-katalogen i [Microsoft Knowledge Base-artikkel 323166](http://support.microsoft.com/kb/323166).

**Veiledning for søking og distribusjon**

Microsoft har gjort tilgjengelig en veiledning for søking og distribusjon for denne månedens sikkerhetsoppdateringer. Veiledningen vil også hjelpe IT-ansvarlige til å forstå hvordan de kan bruke ulike verktøy til å distribuere sikkerhetsoppdateringen, for eksempel Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office-søkeverktøyet, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool og Enterprise Update Scan Tool (EST). Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer og** **Enterprise** **Update Scan Tool**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

Når MBSA 1.2.1 ikke finner en oppdatering for en spesifikk sikkerhetsoppdatering, utgir Microsoft en versjon av Enterprise Update Scan Tool (EST) for den sikkerhetsoppdateringen. Du finner mer informasjon om EST ved å gå til [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Obs\!** Etter 9. oktober 2007 oppdateres ikke lenger MSSecure.XML-filen som brukes av MBSA 1.2.1. Etter denne datoen blir det ikke lagt til nye sikkerhetsoppdateringer til MSSecure.XML-filen som brukes av MBSA 1.2.1, og det blir ikke utgitt flere versjoner av Enterprise Scan Tool. Du finner mer informasjon på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Software Update Services**

Med Microsoft Software Update Services (SUS) kan administratorer raskt og effektivt distribuere de nyeste og viktige oppdateringene og sikkerhetsoppdateringene til Windows 2000- og Windows Server 2003-baserte servere samt til stasjonære systemer som kjører Windows 2000 Professional eller Windows XP Professional.

Hvis du vil ha mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen med Software Update Services, går du til webområdet [Software Update Services](http://go.microsoft.com/fwlink/?linkid=21133).

**Windows Server Update Services**

Med Windows Server Update Services (WSUS) kan administratorer raskt og effektivt distribuere de nyeste viktige oppdateringene og sikkerhetsoppdateringene for Windows 2000 og nyere operativsystemer, Office XP og nyere, Exchange Server 2003 og SQL Server 2000, til Windows 2000 og nyere operativsystemer.

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 for å distribuere sikkerhetsoppdateringer, kan du gå til [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Brukere av SMS 2.0 kan også bruke [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) for å få hjelp til å distribuere sikkerhetsoppdateringer. Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer og Microsoft Office-søkeverktøyet til å utøve omfattende støtte for oppdaging og distribusjon av sikkerhetsbulletiner. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til å installere disse oppdateringene.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

Vær oppmerksom på at dette verktøyet **ikke** distribueres ved hjelp av Software Update Services (SUS).

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU, WSUS og SUS

For denne måneden:

  - Microsoft har utgitt fire **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har utgitt én **ikke-sikkerhetsrelatert**, høyt prioritert oppdatering for Windows på Windows Update (WU) og Software Update Services (SUS).

Vær oppmerksom på at denne informasjonen **bare** gjelder **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update, Windows Update, Windows Server Update Services og Software Update Services som ble utgitt samme dag som sammendraget av sikkerhetsbulletinen. Det gis **ikke** informasjon om **ikke-sikkerhetsrelaterte** oppdateringer som utgis andre dager.

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

  - Dinis Cruz hos [OWASP](http://www.owasp.org/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Paul Craig hos [Security Assessment](http://www.smsiinc.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Jeroen Frijters hos [Sumatra](http://www.sumatra.nl/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - [ProCheckUp](http://www.procheckup.com/) i samarbeid med [UK CPNI](http://www.cpni.gov.uk/) for den første rapporten om et problem som beskrives i [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Ferruh T. Mavituna hos [Portcullis Computer Security Ltd.](http://www.portcullis-security.com/) for å ha samarbeidet med Microsoft og gitt ytterligere informasjon om et problem som er beskrevet i [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Johannes Gumbel hos [TrueSec](http://www.truesec.com/) for å ha samarbeidet med Microsoft og gitt ytterligere informasjon om et problem som er beskrevet i [MS07-040](http://go.microsoft.com/fwlink/?linkid=91233).
  - Peter Winter-Smith hos [NGS Software](http://www.nextgenss.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-039](http://go.microsoft.com/fwlink/?linkid=93365).
  - Neel Mehta hos [IBM Internet Security Systems x-Force](http://xforce.iss.net/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-039](http://go.microsoft.com/fwlink/?linkid=93365).
  - [eEye](http://www.eeye.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-037](http://go.microsoft.com/fwlink/?linkid=93488).
  - Jim Hoagland og Ollie Whitehouse hos [Symantec](http://www.symantec.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-038](http://go.microsoft.com/fwlink/?linkid=91033).
  - Jonathan Afek og Adi Sharabani hos [Watchfire](http://www.watchfire.com/) for å ha samarbeidet med Microsoft og gitt ytterligere informasjon om et problem som er beskrevet i [MS07-041](http://go.microsoft.com/fwlink/?linkid=93706).
  - Peter Winter-Smith hos [NGSSoftware](http://www.nextgenss.com/) for å ha samarbeidet med Microsoft og gitt ytterligere informasjon om et problem som er beskrevet i [MS07-041](http://go.microsoft.com/fwlink/?linkid=93706).

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (10. juli 2007): Publisert sammendrag av sikkerhetsbulletin.

*Built at 2014-04-18T01:50:00Z-07:00*

