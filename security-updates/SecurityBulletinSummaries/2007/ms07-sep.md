---
title: Sammendrag av Microsofts sikkerhetsbulletiner for september 2007
TOCTitle: MS07-SEP
ms:assetid: ms07-sep
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms07-sep(v=Security.10)
ms:contentKeyID: 61315187
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for september 2007

Publisert: 11. september 2007 | Oppdatert: 12. september 2007

**Versjon:** 1.1

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i september 2007.

I forbindelse med utgivelsen av bulletinene for september 2007 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 6. september 2007. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 12. september 2007 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for september på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344690&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (1)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsoft Security Bulletin MS07-051</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=94667"><strong>Sikkerhetsproblem i Microsoft Agent kan tillate ekstern kjøring av kode (938827)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne kritiske sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Et sikkerhetsproblem som kan forårsake ekstern kjøring av kode, finnes i Microsoft Agent på grunn av måten koden håndterer spesiallagde URL-adresser på. Sikkerhetsproblemet kan tillate at en angriper kjører kode eksternt på det berørte systemet. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;"><strong>Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig (3)

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsoft Security Bulletin MS07-052</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=98460"><strong>Sikkerhetsproblem i Crystal Reports for Visual Studio kan tillate ekstern kjøring av kode (941522)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser et publisert sikkerhetsproblem. Dette sikkerhetsproblemet kan tillate kjøring av ekstern kode hvis en bruker åpner en spesiallaget RPT-fil. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen kan kreve en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Visual Studio.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsoft Security Bulletin MS07-053</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=94467"><strong>Sikkerhetsproblem i Crystal Reports for Visual Studio kan tillate ekstern kjøring av kode (941522)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne viktige sikkerhetsoppdateringen løser ett personlig rapportert sikkerhetsproblem. Det finnes et sikkerhetsproblem i Windows Services for UNIX 3.0, Windows Services for UNIX 3.5 og Subsystem for UNIX-based Applications der kjøring av visse setuid-binærfiler kan gi en angriper rettighetsutvidelse.</td>
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
<td style="border:1px solid black;">Microsoft Baseline Security Analyzer og Enterprise Update Scan Tool kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>Windows Services for UNIX, Subsystem for UNIX-based Applications.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletinidentifikator</th>
<th style="border:1px solid black;">Microsoft Security Bulletin MS07-054</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Bulletintittel</strong></td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=100148"><strong>Sikkerhetsproblem i MSN Messenger og Windows Live Messenger kan tillate ekstern kjøring av kode (942099)</strong></a></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Kortfattet sammendrag</strong></td>
<td style="border:1px solid black;">Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i MSN Messenger og Windows Live Messenger. Sikkerhetsproblemet kan tillate ekstern kjøring av kode når en bruker godtar en webkamera- eller videosamtaleinvitasjon fra en angriper. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over det berørte systemet. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td style="border:1px solid black;">Disse produktene har innebygde mekanismer for automatisk gjenkjenning og distribusjon av oppdateringer. Denne oppdateringen kan kreve en omstart.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>Berørt programvare</strong></td>
<td style="border:1px solid black;"><strong>MSN Messenger, Windows Live Messenger.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
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
  </tr>
            <tr><td style="border:1px solid black;">
                <strong>Bulletinidentifikator</strong>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=94667">
                  <strong>MS07-051</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=98460">
                  <strong>MS07-052</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=94467">
                  <strong>MS07-053</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=100148">
                  <strong>MS07-054</strong>
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
                  <strong>Viktig</strong>
                </a>
              </td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Viktig</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="5" style="border:1px solid black;">Windows-operativsystem:</th></tr>
          
            <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cd248ed-d154-4dce-89ef-ceefd2700965">Kritisk</a>
              </td><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 1</td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition</td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Vista</td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition</td><td /><td /><td style="border:1px solid black;">
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="5" style="border:1px solid black;">Operativsystemkomponenter for Windows</th></tr>
          
            <tr><td style="border:1px solid black;">Windows Services for UNIX 3.0 på Windows 2000 Service Pack 4</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Services for UNIX 3.5 på Windows 2000 Service Pack 4</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Viktig</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Services for UNIX 3.0 på Windows XP Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Services for UNIX 3.5 på Windows XP Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Viktig</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Windows Services for UNIX 3.0 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=557f89fc-c5d9-4405-9007-1654abf92277">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Windows Services for UNIX 3.5 på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ae23c2-3ae8-4ea6-ba8d-8ac7e4f82663">Viktig</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Subsystem for UNIX-based Applications på Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ab5cc43-0b9c-45eb-aa51-47568ab6ce3f">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Subsystem for UNIX-based Applications på Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d21e3e8-b5f6-4044-9db6-054af836492b">Viktig</a>
              </td><td /></tr>
            <tr><td style="border:1px solid black;">Subsystem for UNIX-based Applications på Windows Vista</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d52e4f4-2888-42df-8163-85c648e65b29">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Subsystem for UNIX-based Applications på Windows Vista x64 Edition</td><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4be667cc-c239-480b-a9a0-939bcd27f0de">Viktig</a>
              </td><td /></tr>
          
            <tr><th colspan="5" style="border:1px solid black;">Utviklingsverktøy og -plattformer</th></tr>
          
            <tr><td style="border:1px solid black;">Visual Studio .NET 2002 Service Pack 1<br />(KB937057)</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2608c83b-e1b2-4449-9a0e-1e566aac3d76">Viktig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Visual Studio .NET 2003<br />(KB937058)</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d612ad41-5a0d-4e13-99ea-d6a5589786d6">Viktig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Visual Studio .NET 2003 Service Pack 1<br />(KB937059)</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b10b04b-932c-4bff-9cbc-b3eeb15064b1">Viktig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">Visual Studio 2005<br />(KB937060)</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=21073cc2-919c-40df-8ebb-aa3db06050d2">Viktig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
            <tr><td style="border:1px solid black;">Visual Studio 2005 Service Pack 1<br />(KB937061)</td><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=967d43c8-efba-4221-beb0-981e7deef33a">Viktig</a>
                <strong>[2]</strong>
              </td><td /><td /></tr>
          
            <tr><th colspan="5" style="border:1px solid black;">Annen berørt programvare</th></tr>
          
            <tr class="alternateRow"><td style="border:1px solid black;">MSN Messenger 6.2 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&amp;displaylang=en">Viktig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">MSN Messenger 7.0 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf49c56c-8b3e-4eae-9904-9505f47bed45&amp;displaylang=en">Viktig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">MSN Messenger 6.2 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Viktig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">MSN Messenger 7.0 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Viktig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr class="alternateRow"><td style="border:1px solid black;">MSN Messenger 7.5 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Viktig</a>
                <strong>[3]</strong>
              </td></tr>
            <tr><td style="border:1px solid black;">Windows Live Messenger 8.0 på Windows XP Service Pack 2, Windows XP Professional x64 Edition, Windows XP Professional x64 Edition Service Pack 2, Windows Server 2003 Service Pack 1, Windows Server 2003 Service Pack 2, Windows Server 2003 x64 Edition, Windows Server 2003 x64 Edition Service Pack 2, Windows Vista og Windows Vista x64 Edition</td><td /><td /><td /><td style="border:1px solid black;">
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d78f2ff1-79ea-4066-8ba0-ddbed94864fc&amp;displaylang=en">Viktig</a>
                <strong>[3]</strong>
              </td></tr>
          </table>


**Merknader**

**\[1\]** Det finnes en sikkerhetsoppdatering for dette operativsystemet. Hvis du vil ha mer informasjon, ser du etter den berørte programvaren eller komponenten i tabellen og i den aktuelle sikkerhetsbulletinen. 

**\[2\]** Ikke alle versjoner av Visual Studio er berørt. Se den aktuelle sikkerhetsbulletinen hvis du vil ha en nøyaktig liste over berørte versjoner. 

**\[3\]** Et alternativ for å utføre online-oppgradering fra MSN Messenger- eller Windows Live Messenger-tjenesten er også tilgjengelig for denne programvaren. Se den aktuelle sikkerhetsbulletinen hvis du vil ha mer informasjon.

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

  - Microsoft har utgitt null **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har utgitt null **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer for Windows på Windows Update (WU).

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

  - Vulnerability Research-teamet hos [Assurent Secure Technologies](http://www.assurent.com/) for rapporten om sikkerhetsproblemet som beskrives i [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667)
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om sikkerhetsproblemet som beskrives i [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667)
  - En anonym forsker i samarbeid med [iDefense VCP](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-051](http://go.microsoft.com/fwlink/?linkid=94667).
  - Brian A. Reiter hos WolfeReiter for samarbeidet i forbindelse med et sikkerhetsproblem som beskrives i [MS07-053](http://go.microsoft.com/fwlink/?linkid=94467)
  - Woo Shi hos [team 509](http://www.team509.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-054](http://go.microsoft.com/fwlink/?linkid=100148)

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (11. september 2007): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (12. september 2007): Krav om omstart fremsatt på nytt og nedlastingskoblinger lagt til for MS07-045.

*Built at 2014-04-18T01:50:00Z-07:00*

