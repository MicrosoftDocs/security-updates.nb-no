---
title: Sammendrag av Microsofts sikkerhetsbulletiner for februar 2009
TOCTitle: MS09-FEB
ms:assetid: ms09-feb
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms09-feb(v=Security.10)
ms:contentKeyID: 61315203
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for februar 2009

Publisert: 10. februar 2009 | Oppdatert: 25. februar 2009

**Versjon:** 2.1

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i februar 2009.

I forbindelse med utgivelsen av bulletinene for februar 2009 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 5. februar 2009. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 11. februar 2009 kl. 11.00, stillehavstid (USA og Canada). Registrer deg nå for å følge [sikkerhetsbulletinen for februar på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032395122). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<th style="border:1px solid black;">Maksimal alvorlighetsgrad og sikkerhetspåvirkning</th>
<th style="border:1px solid black;">Krav om omstart</th>
<th style="border:1px solid black;">Berørt programvare</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139814">MS09-002</a></td>
<td style="border:1px solid black;"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (961260)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer. Sikkerhetsproblemene kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=136636">MS09-003</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Microsoft Exchange kan tillate ekstern kjøring av kode (959239)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Exchange Server. Det første sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en spesiallaget TNEF-melding sendes til en Microsoft Exchange Server. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan ta full kontroll over det berørte systemet med rettighetene til kontoen for Exchange Server-tjenesten. Det andre sikkerhetsproblemet kan tillate tjenestenekt hvis en spesiallaget MAPI-kommando sendes til en Microsoft Exchange Server. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan forårsake at tjenesten Microsoft Exchange System Attendant og andre tjenester som bruker EMSMDB32-tjenesten, slutter å svare.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Exchange Server</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139513">MS09-004</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Microsoft SQL Server kan tillate ekstern kjøring av kode (959420)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft SQL Server. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis ikke-klarerte brukere får tilgang til et berørt system, eller hvis det forekommer et SQL-injeksjonsangrep på et berørt system. Systemer med SQL Server 7.0 Service Pack 4, SQL Server 2005 Service Pack 3 og SQL Server 2008 berøres ikke av dette problemet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft SQL Server</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128107">MS09-005</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Microsoft Office Visio kan tillate ekstern kjøring av kode (957634)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser tre personlig rapporterte sikkerhetsproblemer i Microsoft Office Visio som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Visio-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført etter bulletin-ID og CVE-ID.

**Hvordan bruker jeg denne tabellen?**  

Bruk denne tabellen til å få mer informasjon om sannsynligheten for at fungerende skadelig kode blir utgitt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Du bør se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139814">MS09-002</a></td>
<td style="border:1px solid black;">Kumulativ sikkerhetsoppdatering for Internet Explorer (961260)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0075">CVE-2009-0075</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Konsekvent skadelig kode kan enkelt lages.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139814">MS09-002</a></td>
<td style="border:1px solid black;">Kumulativ sikkerhetsoppdatering for Internet Explorer (961260)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0076">CVE-2009-0076</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Konsekvent skadelig kode kan enkelt lages.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=136636">MS09-003</a></td>
<td style="border:1px solid black;">Sikkerhetsproblemer i Microsoft Exchange kan tillate ekstern kjøring av kode (959239)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0098">CVE-2009-0098</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=136636">MS09-003</a></td>
<td style="border:1px solid black;">Sikkerhetsproblemer i Microsoft Exchange kan tillate ekstern kjøring av kode (959239)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0099">CVE-2009-0099</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan forårsake tjenestenekt. Angrep som utnytter dette sikkerhetsproblemet, vil sannsynligvis bare føre til tjenestenekt, ikke ekstern kjøring av kode. </td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=139513">MS09-004</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Microsoft SQL Server kan tillate ekstern kjøring av kode (959420)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-5416">CVE-2008-5416</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Funksjonell skadelig kode er publisert etter godkjenning.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128107">MS09-005</a></td>
<td style="border:1px solid black;">Sikkerhetsproblemer i Microsoft Office Visio kan tillate ekstern kjøring av kode (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0095">CVE-2009-0095</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128107">MS09-005</a></td>
<td style="border:1px solid black;">Sikkerhetsproblemer i Microsoft Office Visio kan tillate ekstern kjøring av kode (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0096">CVE-2009-0096</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=128107">MS09-005</a></td>
<td style="border:1px solid black;">Sikkerhetsproblemer i Microsoft Office Visio kan tillate ekstern kjøring av kode (957634)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0097">CVE-2009-0097</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

Følgende tabeller viser bulletinene etter store programvarekategorier og alvorlighetsgrad.

**Hvordan bruker jeg disse tabellene?**  

Bruk disse tabellene til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det kommer noen sikkerhetsoppdateringer som angår installasjonen din. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139814">
                      <strong>MS09-002</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139513">
                      <strong>MS09-004</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8cd902ec-e018-4b61-80f9-825d973f998e">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd3e2236-9cc0-478e-a46c-981ef685c0e3">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139814">
                      <strong>MS09-002</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139513">
                      <strong>MS09-004</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e52aa1fd-e694-4322-b3ff-6abc1b4a16fe">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=218809d6-a9fb-408b-a34d-ab2ac786994c">Microsoft SQL Server 2000 Desktop Engine (WMSDE)</a>
                    <br />(KB960082)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e">Windows Internal Database (WYukon) Service Pack 2</a><br />(KB960089)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=edbf1566-b96b-4c7d-98fe-b15f8e766792">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87183155-6770-4ea2-acca-191de4d40d27">Microsoft SQL Server 2000 Desktop Engine (WMSDE)</a>
                    <br />(KB960082)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67">Windows Internal Database (WYukon) x64 Edition Service Pack 2</a><br />(KB960089)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ce78797-d1c0-40d4-84e1-1004389833be">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139814">
                      <strong>MS09-002</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139513">
                      <strong>MS09-004</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista og Windows Vista Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f9fa4b6-85a4-43bc-b84f-6bd847799650">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9a8c94b-b9d2-4d64-855f-b5f02ce3dfb5">Windows Internet Explorer 7</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139814">
                      <strong>MS09-002</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139513">
                      <strong>MS09-004</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2491dbf2-7cd3-44f1-bfad-77e6f760a25c">Windows Internet Explorer 7</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16925be5-98d0-446b-9bbc-d9a2d335c69e">Windows Internal Database (WYukon) Service Pack 2</a>*<br />(KB960089)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=794373cc-2dce-4ef5-af50-7804c622c230">Windows Internet Explorer 7</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=05c5c265-cfd7-4364-b323-77650b7f1e67">Windows Internal Database (WYukon) x64 Edition Service Pack 2</a>*<br />(KB960089)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for Itanium-based Systems</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=11985325-4b33-4077-82cf-6afc7a71c510">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Merknader for Windows Server 2008**

**\*Server Core-installasjonen av Windows Server 2008 berørt.** For støttede versjoner av Windows Server 2008 gjelder denne oppdateringen (med samme alvorlighetsgrad) enten Windows Server 2008 ble installert med installasjonsalternativet for Server Core eller ikke. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen av Windows Server 2008 ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 hvis Windows Server 2008 ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS09-004**

Se også delen **Microsoft Server-programvare** hvis du vil ha mer informasjon om flere oppdateringsfiler. Denne bulletinen dekker både Windows-operativsystemer og -komponenter og Microsoft-serverprogramvare.

#### Microsoft Server-programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="" style="border:1px solid black;">Microsoft Exchange Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=136636">
                      <strong>MS09-003</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Exchange 2000 Server </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=805dc856-ea60-477d-be40-6ac535a7e7e5">Microsoft Exchange 2000 Server Service Pack 3 med samleoppdateringen fra august 2004</a>
                    <br />(KB959897)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Exchange Server 2003</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d9f0956-88bd-4e13-a86b-b1c8d4782f71">Microsoft Exchange Server 2003 Service Pack 2</a>*<br />(KB959897)<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Exchange Server 2007</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93cb3f66-ae72-4356-bdbf-35029cff6df1">Microsoft Exchange Server 2007 Service Pack 1</a>**<br />(KB959241)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Exchange Server MAPI Client og Collaboration Data Objects 1.2.1</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e17e7f31-079a-43a9-bff2-0a110307611e">Microsoft Exchange Server MAPI Client og Collaboration Data Objects 1.2.1</a>***<br />(Kritisk)</td></tr>
              </table>


**Merknader for MS09-003**

\*Inkluderer Microsoft Exchange System Management-verktøyene for Exchange Server 2003 hvis serveren allerede kjører en aktiv forekomst av Exchange-tjenesten.

\*\*Inkluderer 32-biters og x64-baserte versjoner

\*\*\*Microsoft Exchange Server MAPI Client inneholder den utsatte koden. Kunder som vil beskytte seg mot sikkerhetsproblemene beskrevet i MS09-003, og som kjører Microsoft Exchange Server MAPI Client, må oppdatere til versjon 6.5.8069 av MAPI-klienten. 

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="" style="border:1px solid black;">Microsoft SQL Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139513">
                      <strong>MS09-004</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2000 Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c">SQL Server 2000 Service Pack 4</a><br />(KB960082)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a">SQL Server 2000 Service Pack 4</a><br />(KB960083)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2000 Itanium-based Edition Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c">SQL Server 2000 Itanium-based Edition Service Pack 4</a><br />(KB960082)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a">SQL Server 2000 Itanium-based Edition Service Pack 4</a><br />(KB960083)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 Service Pack 2</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e">SQL Server 2005 Service Pack 2</a><br />(KB960089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a">SQL Server 2005 Service Pack 2</a><br />(KB960090)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 x64 Edition Service Pack 2</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e">SQL Server 2005 x64 Edition Service Pack 2</a><br />(KB960089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a">SQL Server 2005 x64 Edition Service Pack 2</a><br />(KB960090)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 med SP2 for Itanium-based Systems</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e">SQL Server 2005 med SP2 for Itanium-based Systems</a><br />(KB960089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a">SQL Server 2005 med SP2 for Itanium-based Systems</a><br />(KB960090)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5bb816a-6e1a-47cb-92be-51c565ee184c">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</a><br />(KB960082)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a93f3cfe-18c9-4218-a551-13bf415e418a">Microsoft SQL Server 2000 Desktop Engine (MSDE 2000) Service Pack 4</a><br />(KB960083)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 Express Edition Service Pack 2</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e">SQL Server 2005 Express Edition Service Pack 2</a><br />(KB960089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a">SQL Server 2005 Express Edition Service Pack 2</a><br />(KB960090)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 Express Edition med Advanced Services Service Pack 2</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5dfb7998-0316-40e5-9fc5-7a1afc18e15e">SQL Server 2005 Express Edition med Advanced Services Service Pack 2</a><br />(KB960089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa2b82ca-e94e-4491-8639-f0749b1a0f3a">SQL Server 2005 Express Edition med Advanced Services Service Pack 2</a><br />(KB960090)<br />(Viktig)</td></tr>
              </table>


**Merknad for MS09-004**

Se også delen **Operativsystemer og komponenter for Windows** for flere oppdateringsfiler. Denne bulletinen dekker både Windows-operativsystemer og -komponenter og Microsoft-serverprogramvare.

#### Microsoft Office-serier og -programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="" style="border:1px solid black;">Microsoft Office Visio</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128107">
                      <strong>MS09-005</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Visio 2002</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a30cef3f-9eaf-45bd-9a25-4b65302362cb">Microsoft Office Visio 2002 Service Pack 2</a>
                    <br />(KB955654)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Visio 2003</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9cb589e-1a37-485d-8402-7f42bcd7a1a9">Microsoft Office Visio 2003 Service Pack 3</a>
                    <br />(KB955655)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office Visio 2007</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b711e89-8de2-4f17-8afc-691e0604ff82">Microsoft Office Visio 2007 Service Pack 1</a>
                    <br />(KB957831)<br />(Viktig)</td></tr>
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

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validere Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Innholdet i beskrivelsen av Software Update Services og Windows Server Update Services endres. Omfatter alt Windows-innhold.
  - [Nye, reviderte og utgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/bb466214.aspx)

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

  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-002
  - Sam Thomas (<http://eshu.co.uk/>), i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS09-002
  - Bogdan Materna hos [VoIPshield Systems](http://www.voipshield.com) for rapporten om et sikkerhetsproblem som beskrives i MS09-003
  - Bernhard Mueller hos [SEC Consult Vulnerability Lab](http://www.sec-consult.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-004
  - Bing Liu hos Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for rapporten om flere sikkerhetsproblemer som beskrives i MS09-005

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (10. februar 2009): Publisert sammendrag av sikkerhetsbulletin.
  - V2.0 (16. februar 2009): Microsoft Exchange Server MAPI Client er lagt til som berørt programvare for MS09-003.
  - V2.1 (25. februar 2009): Lagt til en merknad vedrørende Exchange System Management-verktøyene for Exchange Server 2003 for MS09-003.

*Built at 2014-04-18T01:50:00Z-07:00*

