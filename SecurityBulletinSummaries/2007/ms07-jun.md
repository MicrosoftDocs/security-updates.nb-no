---
title: Sammendrag av Microsofts sikkerhetsbulletiner for juni 2007
TOCTitle: MS07-JUN
ms:assetid: ms07-jun
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms07-jun(v=Security.10)
ms:contentKeyID: 61315182
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for juni 2007

Publisert: 12. juni 2007

**Versjon:** 1.0

Denne sammendragsbulletinen inneholder en liste over sikkerhetsbulletinene som utgis i juni 2007.

I forbindelse med utgivelsen av bulletinene for juni 2007 erstatter dette bulletinsammendraget forhåndsvarslingen for bulletiner som ble utstedt 7. juni 2007. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletin, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil motta beskjed automatisk når Microsoft-sikkerhetsbulletiner publiseres, må du abonnere på [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene onsdag 13. juni 2007 kl 11:00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for juni på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032327013&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (4)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-031</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91396"><strong>Sikkerhetsproblem i Schannel-sikkerhetspakken i Windows kan tillate ekstern kjøring av kode (935840)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Secure Channel-sikkerhetspakken (Schannel) i Windows. Schannel-sikkerhetspakken implementerer Internet Standard-godkjenningsprotokollene Secure Sockets Layer (SSL) og Transport Layer Security (TLS). Dette sikkerhetsproblemet kan tillate kjøring av ekstern kode hvis en bruker åpner en spesiallaget webside via en webleser eller bruker et program som bruker SSL/TLS. Men forsøk på å utnytte dette sikkerhetsproblemet vil mest sannsynlig føre til at webleseren eller programmet avsluttes. Systemet kan ikke koble til webområder eller ressurser via SSL eller TLS før datamaskinen er startet på nytt.</td>
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
<td><strong>Windows</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-033</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=83835"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (933566)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem. Alle disse sikkerhetsproblemene unntatt ett kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Et sikkerhetsproblem kan tillate etterligningsangrep, og det omfatter også en spesiallaget webside. I alle tilfeller av ekstern kjøring av kode er brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, mindre utsatt enn brukere som har administrative rettigheter. Det kreves brukermedvirkning for å kunne utnytte etterligningsangrep.</td>
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
<td><strong>Windows, Internet Explorer</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-034</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=88627"><strong>Kumulativ sikkerhetsoppdatering for Outlook Express og Windows Mail (929123)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser to personlig rapporterte og to offentliggjorte sikkerhetsproblemer. Et av disse sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker viser en spesiallaget e-postmelding ved hjelp av Windows Mail i Windows Vista. De andre sikkerhetsproblemene kan føre til tilgjengeliggjøring av informasjon hvis en bruker besøker en spesiallaget webside ved hjelp av Internet Explorer, og kan ikke utnyttes direkte i Outlook Express. Når det gjelder sikkerhetsproblemene som kan føre til tilgjengeliggjøring av informasjon, er brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td>Microsoft Baseline Security Analyzer og Enterprise Scan Tool kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen kan kreve en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows, Outlook Express, Windows Mail</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-035</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=91397"><strong>Sikkerhetsproblem i Win32 API kan tillate ekstern kjøring av kode (935839)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i en Win32 API. Dette sikkerhetsproblemet kan tillate ekstern kjøring av kode eller rettighetsutvidelse hvis den berørte APIen brukes lokalt av et spesiallaget program. Programmer som bruker denne komponenten av Win32 API, kan derfor brukes som en vektor for dette sikkerhetsproblemet. For eksempel bruker Internet Explorer denne Win32 API-funksjonen ved analysering av spesiallagede websider.</td>
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
<td><strong>Windows</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig (1)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-030</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=76089"><strong>Sikkerhetsproblemer i Microsoft Visio kan tillate ekstern kjøring av kode (927051)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne viktige sikkerhetsoppdateringen løser to personlig oppdagede sikkerhetsproblemer, som ble rapportert på en ansvarlig måte, i tillegg til to andre sikkerhetsproblemer som ble oppdaget under undersøkelsen. De personlig rapporterte sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Visio-fil. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Brukermedvirkning er nødvendig for å utnytte disse sikkerhetsproblemene.</td>
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
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen kan kreve en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Office, Visio</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Moderat (1)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS07-032</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=84693"><strong>Sikkerhetsproblem i Windows Vista kan tillate tilgjengeliggjøring av informasjon (931213)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne moderate sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem. Dette sikkerhetsproblemet kan tillate at brukere uten rettigheter får tilgang til datalagre med lokale brukeropplysninger, inkludert administratorpassord i registret og i det lokale filsystemet.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a></td>
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
<td><strong>Windows</strong>. Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
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
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=76089">
                  <strong>MS07-030</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91396">
                  <strong>MS07-031</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=84693">
                  <strong>MS07-032</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=83835">
                  <strong>MS07-033</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=88627">
                  <strong>MS07-034</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=91397">
                  <strong>MS07-035</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Maksimal alvorlighetsgrad</strong>
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
                  <strong>Kritisk</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="7">Berørt programvare for Windows</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b8e728c-cb9f-4176-93a0-bf42d6387f93">Moderat</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3918ac76-ebb6-4886-9a9e-808eafb96b1b">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8615e6f3-415b-4c23-ba52-7eef70a11d77">Kritisk</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27c7f1b9-2d1d-40cb-ad7e-bfedb6156a9c">Kritisk</a>
              </td></tr>
            <tr><td>Windows XP Professional x64 Edition</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a">Kritisk</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e994340-c616-4f66-845b-7eaf095e968a">Kritisk</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ba12191-1e6f-443b-9150-7ab8b2deb7c2">Kritisk</a>
              </td></tr>
            <tr><td>Windows Server 2003 Service Pack 1</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f">Viktig</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39e6c6d2-7e6f-4992-a731-36f44fe2d87f">Viktig</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d554dff4-bcfb-4bbc-8fa0-af2f939d2610">Kritisk</a>
              </td></tr>
            <tr><td>Windows Server 2003 x64 Edition</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79">Viktig</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da424772-079c-4351-9759-8886e0f1ba79">Viktig</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=170473d8-6bb1-4fbd-8494-a059dbfdf182">Kritisk</a>
              </td></tr>
            <tr><td>Windows Server 2003 SP1 for Itanium-based Systems</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4">Viktig</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99">Kritisk</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 SP2 for Itanium-based Systems</td><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=028592ff-2b69-472e-b186-bd2cc76bdfa4">Viktig</a>
              </td><td /><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5e45e3c-4cac-41a5-99f7-42c2c2c73e99">Kritisk</a>
              </td></tr>
            <tr><td>Windows Vista</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdf79d00-6f34-404b-8ad5-a2801ff35443">Moderat</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista x64 Edition</td><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89dde3f4-4123-4c97-86d8-00a83462c34b">Moderat</a>
              </td><td>
                <strong>[1]</strong>
              </td><td>
                <strong>[1]</strong>
              </td><td /></tr>
          
            <tr><th colspan="7">Berørte operativsystemkomponenter for Windows</th></tr>
          
            <tr><td>Internet Explorer 5.01 Service Pack 4 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b49f1ed-abe3-4dbd-a91d-973415658f6b">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5c958650-28d2-4dd0-96a8-dbfe79ce3f68">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td>Internet Explorer 6 for Windows XP Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60fb294e-a8e1-405e-a289-2d2723edf7ee">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 for Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=086d6d6e-4703-4c6c-a7af-b6dafeeede5d">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td>Internet Explorer 6 for Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ed19127-5c2d-48e4-a8d1-090dc69fd68b">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 6 for Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1449eb5d-6e4c-4332-8cb6-ab9ee59c9a95">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td>Internet Explorer 6 for Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b628a3cc-a70c-478a-a10c-eee254ee34ab">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 for Windows XP Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2191703-8cbd-4959-9f84-e13f21173926">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td>Internet Explorer 7 for Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=69c526b8-8b07-42bc-9bed-e18deae21c8e">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 for Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a074d9c0-1fed-4753-845e-073cfce99f45">Moderat</a>
              </td><td /><td /></tr>
            <tr><td>Internet Explorer 7 for Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=744acb43-64da-48cc-ae69-9386b597eabc">Moderat</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 for Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=069c1560-b5e5-4dfe-a18d-e0507d406028">Moderat</a>
              </td><td /><td /></tr>
            <tr><td>Internet Explorer 7 i Windows Vista</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7">Kritisk</a>
              </td><td /><td /></tr>
            <tr class="alternateRow"><td>Internet Explorer 7 i Windows Vista x64 Edition</td><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77287386-48eb-4aa9-9537-626a3093aaf7">Kritisk</a>
              </td><td /><td /></tr>
            <tr><td>Outlook Express 6 for Windows XP Service Pack 2</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27cca556-0872-4803-b610-4c895ceb99aa">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 for Windows XP Professional x64 Edition</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7">Viktig</a>
              </td><td /></tr>
            <tr><td>Outlook Express 6 for Windows XP Professional x64 Edition Service Pack 2</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ea813bf-bddb-40f0-8960-b9debc8413e7">Viktig</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 for Windows Server 2003 Service Pack 1</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be">Lav</a>
              </td><td /></tr>
            <tr><td>Outlook Express 6 for Windows Server 2003 Service Pack 2</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93808a74-035c-4ab7-9283-c693d7bd82be">Lav</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 for Windows Server 2003 x64 Edition</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3">Moderat</a>
              </td><td /></tr>
            <tr><td>Outlook Express 6 for Windows Server 2003 x64 Edition Service Pack 2</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f63323a9-e285-45e5-84bd-71ae9da126e3">Moderat</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Outlook Express 6 for Windows Server 2003 med SP1 for Itanium-based Systems</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025">Lav</a>
              </td><td /></tr>
            <tr><td>Outlook Express 6 for Windows Server 2003 med SP2 for Itanium-based Systems</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e62e96e-6571-437d-a612-99175ac39025">Lav</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Mail i Windows Vista</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57de19-44ea-48f2-ae28-e76fd2018633">Kritisk</a>
              </td><td /></tr>
            <tr><td>Windows Mail i Windows Vista x64 Edition</td><td /><td /><td /><td /><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=343db20f-7794-4423-b11d-885329fbdf78">Kritisk</a>
              </td><td /></tr>
          
            <tr><th colspan="7">Berørt Office-programvare:</th></tr>
          
            <tr class="alternateRow"><td>Visio 2002 Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fc1d0483-27e8-4541-b81d-4a47973bea30">Viktig</a>
              </td><td /><td /><td /><td /><td /></tr>
            <tr><td>Visio 2003 Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c47f432e-8538-42fd-92c9-7e0f1d643e8e">Viktig</a>
              </td><td /><td /><td /><td /><td /></tr>
          </table>


**Merknader**

**\[1\]** Det finnes en sikkerhetsoppdatering for dette operativsystemet. Hvis du vil ha mer informasjon, ser du etter den berørte programvaren eller komponenten i tabellen og i den aktuelle sikkerhetsbulletinen.

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

  - Microsoft har utgitt sju **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har ikke utgitt noen **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer for Windows på Windows Update (WU) og Software Update Services (SUS).

Vær oppmerksom på at denne informasjonen **bare** gjelder **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update, Windows Update, Windows Server Update Services og Software Update Services som ble utgitt samme dag som sammendraget av sikkerhetsbulletinen. Det gis **ikke** informasjon om **ikke-sikkerhetsrelaterte** oppdateringer som utgis andre dager.

#### Sikkerhetsstrategier og -sone

**Strategier for behandling av oppdateringer**

På webområdet [Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) finner du mer informasjon om Microsofts anbefalinger for gode fremgangsmåter for å bruke sikkerhetsdata.

**Få tak i andre sikkerhetsoppdateringer**

Oppdateringer for andre sikkerhetsproblemer finnes på følgende steder:

  - Sikkerhetsoppdateringer finnes på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".
  - Oppdateringer for forbrukerplattformer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan få sikkerhetsoppdateringene som tilbys på Windows Update denne måneden, fra Download Center på Security and Critical Releases ISO CD Image-filer. Hvis du vil ha mer informasjon, kan du se [Microsoft Knowledge Base-artikkel 913086](http://support.microsoft.com/kb/913086).

**Sikkerhetssone for IT-eksperter**

Lær hvordan du kan forbedre sikkerheten og optimalisere IT-infrastrukturen, og delta sammen med andre IT-eksperter i diskusjoner om sikkerhet i [sikkerhetssonen for IT-eksperter](http://go.microsoft.com/fwlink/?linkid=21164).

#### Takk til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for samarbeidet med å beskytte kundene:

  - En anonym forsker i samarbeid med [iDefense VCP](http://idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Tom Cross hos [ISS](http://www.iss.net/) for samarbeidet med Microsoft i forbindelse med et sikkerhetsproblem som beskrives i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - En anonym forsker i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Sam Thomas i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Will Dormann hos [CERT/CC](http://www.cert.org/certcc.html) for rapporten om et problem som beskrives i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - cocoruder hos [Fortinet Security Research](http://www.fortinet.com/) for samarbeidet med Microsoft i forbindelse med et problem som beskrives i [MS07-033](http://go.microsoft.com/fwlink/?linkid=83835).
  - Billy Rios for rapporten om et problem som beskrives i [MS07-035](http://go.microsoft.com/fwlink/?linkid=91397).
  - Thomas Lim hos [COSEINC](http://www.coseinc.com/) for rapporten om et problem som beskrives i [MS07-031](http://go.microsoft.com/fwlink/?linkid=91396).
  - [SANS ISC](http://isc.sans.org/) for samarbeidet om et problem som beskrives i [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627).
  - Yosuke Hasegawa hos [WebAppSec.JP](https://www.webappsec.jp/) or rapporten om et problem som beskrives i [MS07-034](http://go.microsoft.com/fwlink/?linkid=88627).
  - Robbie Sohlman for rapporten om et problem som beskrives i [MS07-032](http://go.microsoft.com/fwlink/?linkid=84693).

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (12. juni 2007): Publisert sammendrag av sikkerhetsbulletin.

*Built at 2014-04-18T01:50:00Z-07:00*

