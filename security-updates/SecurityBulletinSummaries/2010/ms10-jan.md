---
title: Sammendrag av Microsofts sikkerhetsbulletiner for januar 2010
TOCTitle: MS10-JAN
ms:assetid: ms10-jan
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms10-jan(v=Security.10)
ms:contentKeyID: 61315216
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for januar 2010

Publisert: 12. januar 2010 | Oppdatert: 21. januar 2010

**Versjon:** 2.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i januar 2010.

I forbindelse med utgivelsen av bulletinene for januar 2010 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 20. januar 2010. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 13. januar 2010 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for januar på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427677&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft holder en webcast 21. januar 2010 kl. 13.00 stillehavstid (USA og Canada) for å svare på spørsmål fra kundene om sikkerhetsbulletinen utenfor vanlig sendefrekvens som er lagt til i versjon 2.0 av dette bulletinsammendraget, MS10-002. [Registrer deg nå for å følge webcasten 21. januar kl. 13.00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032440627&culture=en-us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<th style="border:1px solid black;">Maksimal alvorlighetsgrad og følger av sikkerhetsproblemet</th>
<th style="border:1px solid black;">Krav om omstart</th>
<th style="border:1px solid black;">Berørt programvare</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169348">MS10-001</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i motoren for innebygde OpenType-skrifter kan tillate ekstern kjøring av kode (972270)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker viser innhold gjengitt i en spesiallaget innebygd OpenType-skrift (EOT) i klientprogrammer som kan gjengi EOT-skrifter, for eksempel Microsoft Internet Explorer, Microsoft Office PowerPoint eller Microsoft Office Word. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (978207)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser sju personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem i Internet Explorer. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
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
<th style="border:1px solid black;">Tittel på sikkerhetsproblem</th>
<th style="border:1px solid black;">CVE-ID</th>
<th style="border:1px solid black;">Utnyttelsesindeksvurdering</th>
<th style="border:1px solid black;">Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169348">MS10-001</a></td>
<td style="border:1px solid black;">Heltallsfeil i skrifter som er komprimert med Microtype Express, i sikkerhetsproblemet i LZCOMP-dekomprimeringsprogrammet</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0018">CVE-2010-0018</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Denne utnyttelsesindeksvurderingen gjelder for systemer som kjører Microsoft Windows 2000. Utnyttelse av systemer som kjører Windows XP og nyere operativsystemer, er usannsynlig.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i behandling av XSS-filterskript</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-4047">CVE-2009-4047</a></td>
<td style="border:1px solid black;">Ingen</td>
<td style="border:1px solid black;">Kjøring av kode er ikke mulig med dette sikkerhetsproblemet.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med URL-validering</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0027">CVE-2010-0027</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0244">CVE-2010-0244</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0245">CVE-2010-0245</a></td>
<td style="border:1px solid black;">Ingen</td>
<td style="border:1px solid black;">Kunder som har tatt i bruk <a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a>, er beskyttet fordi dette sikkerhetsproblemet blokkeres av endringene som var inkludert i MS09-072-oppdateringen.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0246">CVE-2010-0246</a></td>
<td style="border:1px solid black;">Ingen</td>
<td style="border:1px solid black;">Kunder som har tatt i bruk <a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a>, er beskyttet fordi dette sikkerhetsproblemet blokkeres av endringene som var inkludert i MS09-072-oppdateringen.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0247">CVE-2010-0247</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0248">CVE-2010-0248</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=179104">MS10-002</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0249">CVE-2010-0249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
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
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Windows 2000</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169348">
                      <strong>MS10-001</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179104">
                      <strong>MS10-002</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Windows 2000 Service Pack 4</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47f85cbd-282e-4c92-9809-68bba49e0a12">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51e99e4f-1670-4b12-a9fe-e0ccf50cdabc">Internet Explorer 5.01 Service Pack 4 når installert på Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a38aa9d0-c3fe-4d41-8805-7d5370263c1b">Internet Explorer 6 Service Pack 1 når det er installert på Microsoft Windows 2000 Service Pack 4</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169348">
                      <strong>MS10-001</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179104">
                      <strong>MS10-002</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=793a6b3f-7660-40be-b7d5-7b0eec55e1cd">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=207eecad-6e84-48e6-ae18-6794a3618ee0">Internet Explorer 6 for Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3510c7d8-7e8f-479e-b6f9-5745a845664d">Internet Explorer 7 for Windows XP Service Pack 2 og Windows XP Service Pack 3</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c2948fb-f486-4801-bc21-bbf40d5a78c2">Internet Explorer 8 for Windows XP Service Pack 2 og Windows XP Service Pack 3</a><br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=31609ce9-656a-4f7d-a501-709a31ca34c3">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb2d8055-4d50-4f83-82b8-055c7b8f5422">Internet Explorer 6 for Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc5aea0b-e553-4f7f-a2cc-cba41bb87ae7">Internet Explorer 7 for Windows XP Professional x64 Edition Service Pack 2</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41b83fad-948b-4a9c-80ed-9c5a60bd35b4">Internet Explorer 8 for Windows XP Professional x64 Edition Service Pack 2</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169348">
                      <strong>MS10-001</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179104">
                      <strong>MS10-002</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1d6e338-dea9-458e-b35d-796e069d74d7">Windows Server 2003 Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fea91227-44ad-4549-8732-497a8ceff870">Internet Explorer 6 for Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14726445-3ff4-463c-9fc1-c9b758079aca">Internet Explorer 7 for Windows Server 2003 Service Pack 2</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d480c87-2ca9-4505-a59d-a6d73d001fa5">Internet Explorer 8 for Windows Server 2003 Service Pack 2</a><br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ddbcf231-9fde-4dc2-ad04-a01b69d1a980">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=633e63f4-605b-43c4-8a4b-2730312a1c72">Internet Explorer 6 for Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8742230-16d8-4b2f-bd3e-8834c759856b">Internet Explorer 7 for Windows Server 2003 x64 Edition Service Pack 2</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e2e740b-8417-4758-8468-15221249ec71">Internet Explorer 8 for Windows Server 2003 x64 Edition Service Pack 2</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 SP2 for Itanium-based Systems</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c71a13cf-7e2f-4b02-8684-1a4e4b46ddda">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9308d50-ca66-43ff-9dc5-d05c90baa764">Internet Explorer 6 for Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5622f223-df9c-4a6a-bdf0-feebaf9920fd">Internet Explorer 7 for Windows Server 2003 med SP2 for Itanium-based Systems</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169348">
                      <strong>MS10-001</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179104">
                      <strong>MS10-002</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6387228c-eedc-4511-b3c6-8922606f4c84">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92495551-dedd-43d4-bb3a-51028bc5c6d6">Internet Explorer 7 i Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e2cbd7d-f64f-49e5-a159-1965ebfe2a92">Internet Explorer 8 i Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b4f5089-13b1-421b-a00b-22632bba4229">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3cb139b3-59f4-44ef-9911-4dd4e3b83e7d">Internet Explorer 7 i Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7a7e8e7-f4c5-459d-ab6c-05a192e1e3f9">Internet Explorer 8 i Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169348">
                      <strong>MS10-001</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179104">
                      <strong>MS10-002</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e175c436-37e0-497f-8b7f-6cacaa25ad7c">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8c4c91ec-1b2b-4176-bd77-45245b590329">Internet Explorer 7 i Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer Service Pack 2</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f5ce8582-af63-4870-bee3-0abeeefa1458">Internet Explorer 8 i Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer Service Pack 2</a>**<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b10a177-fd45-406f-8edc-b8d4b84881b7">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f9975b8-3f91-4116-9200-ef55ece75854">Internet Explorer 7 i Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer Service Pack 2</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=be11981c-d286-4e3c-94bf-d4e67a975d5a">Internet Explorer 8 i Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer Service Pack 2</a>**<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8bc9a24-a794-4827-a6bb-785c6b2189f4">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9395547f-b620-4cbd-9ff5-11b76cd73859">Internet Explorer 7 i Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems Service Pack 2</a>
                    <br />(Kritisk)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169348">
                      <strong>MS10-001</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179104">
                      <strong>MS10-002</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 for 32-biters systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75491ad0-40a6-4efb-9574-d82210f6d0da">Windows 7 for 32-biters systemer</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=278443c1-15dc-436b-893b-ffea6d29d16d">Internet Explorer 8 i Windows 7 for 32-biters systemer</a>
                    <br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 for x64-baserte systemer</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8a53f0e9-0616-440e-90f2-a12524e1bee4">Windows 7 for x64-baserte systemer</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a584cd0f-2e05-4e36-8858-0ffead637162">Internet Explorer 8 i Windows 7 for x64-baserte systemer</a>
                    <br />(Kritisk)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=169348">
                      <strong>MS10-001</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=179104">
                      <strong>MS10-002</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 for x64-baserte systemer </td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=308166e4-571b-4d6c-bd9f-3ed4afa4eafe">Windows Server 2008 R2 for x64-baserte systemer</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3386793-a594-4bc5-8308-28b561d43087">Internet Explorer 8 i Windows Server 2008 R2 for x64-baserte systemer</a>**<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 for Itanium-based Systems</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1d0da42b-9755-4fd2-afd1-0d023d187133">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d137bab-8312-4240-af74-c65ba652fde0">Internet Explorer 8 i Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Kritisk)</td></tr>
              </table>


**Merknad for Windows Server 2008 og Windows Server 2008 R2**

**Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet, kan du se MSDN-artiklene [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Obs\!**  Fra og med 1. august 2009 tilbyr ikke lenger Microsoft støtte for Office Update og Office Update Inventory Tool. Hvis du vil fortsette å få de nyeste oppdateringene for Microsoft Office-produkter, kan du bruke [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Hvis du vil ha mer informasjon, kan du se [Om Microsoft Office Update: Vanlige spørsmål](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Veiledning for søking og distribusjon**

Microsoft tilbyr veiledning for søking etter og distribusjon av sikkerhetsoppdateringer. Denne veiledningen inneholder anbefalinger og informasjon som kan hjelpe IT-eksperter med å forstå hvordan ulike verktøy for søking etter og distribusjon av sikkerhetsoppdateringer skal brukes. Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Med Windows Server Update Services (WSUS) kan administratorer raskt og trygt distribuere de nyeste kritiske oppdateringene og sikkerhetsoppdateringene for Microsoft Windows 2000 og nyere operativsystemer, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne. Den neste versjonen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du gå til [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). SMS 2.0-brukere kan også bruke Security Update Inventory Tool (SUIT) som en hjelp til å distribuere sikkerhetsoppdateringer. Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer for å gi bred støtte i forbindelse med søking etter og distribusjon av sikkerhetsbulletinoppdateringer. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validering av Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Innholdet i beskrivelsen av Software Update Services og Windows Server Update Services endres. Omfatter alt Windows-innhold.
  - [Oppdateringer de siste månedene for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Vis alle nye, reviderte og nyutgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows.

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

  - Tavis Ormandy hos [Google Inc.](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-001
  - [David Lindsay "thornmaker"](http://p42.us/) og [Eduardo A. Vela Nava "sirdarckcat"](http://www.sirdarckcat.net/) for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Lostmon Lords for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Brett Moore, i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Wushi hos [team509](http://www.team509.com/), i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Sam Thomas hos eshu.co.uk, i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Sam Thomas hos eshu.co.uk, i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Haifei Li hos Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Peter Vreugdenhil hos [Verisign iDefense Labs](http://labs.idefense.com/), i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-002
  - Meron Sellem hos [BugSec](http://www.bugsec.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-002

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende selskaper for å ha samarbeidet med oss og for å ha gitt oss informasjon om et sikkerhetsproblem som beskrives i MS10-002:

  - [Google Inc.](http://www.google.com/) og [MANDIANT](http://www.mandiant.com/)
  - [Adobe](http://www.adobe.com/)
  - [McAfee](http://www.mcafee.com/)

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (12. januar 2010): Publisert sammendrag av sikkerhetsbulletin.
  - V2.0 (21. januar 2010): Lagt til Microsofts sikkerhetsbulletin **MS10-002, kumulativ oppdatering for Internet Explorer (978207)**. Det er også lagt til en kobling til webcast om bulletinen for denne sikkerhetsbulletinen utenfor vanlig sendefrekvens.

*Built at 2014-04-18T01:50:00Z-07:00*

