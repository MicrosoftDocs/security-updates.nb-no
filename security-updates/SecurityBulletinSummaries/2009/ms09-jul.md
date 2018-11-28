---
title: Sammendrag av Microsofts sikkerhetsbulletiner for juli 2009
TOCTitle: MS09-JUL
ms:assetid: ms09-jul
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms09-jul(v=Security.10)
ms:contentKeyID: 61315205
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for juli 2009

Publisert: 14. juli 2009 | Oppdatert: 9. mars 2010

**Versjon:** 8.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i juli 2009.

I forbindelse med utgivelsen av bulletinene for juli 2009 erstatter dette sammendraget forhåndsvarslingen for bulletiner som ble utstedt 9. juli 2009, og forhåndsvarslingen for bulletiner utenfor vanlig sendefrekvens som ble utstedt 24. juli 2009. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holdt en webcast for å svare på spørsmål fra kundene om de regelmessige, planlagte bulletinene 15. juli 2009 kl. 11.00, stillehavstid (USA og Canada). Denne webcasten er nå tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft holder to webcast-arrangementer for sikkerhetsbulletinene utenfor vanlig sendefrekvens som er lagt til i versjon 2.0 av dette bulletinsammendraget, MS09-034 og MS09-035, for å svare på spørsmål fra kunder angående disse bulletinene 28. juli 2009 kl 13.00 stillehavstid (USA og Canada) og kl 16.00 stillehavstid (USA og Canada). Registrer deg nå for [webcasten 28. juli kl 13.00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422339&culture=en-us) og [webcasten 28. juli kl 16.00](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032422341&culture=en-us). Senere vil disse webcast-arrangementene være tilgjengelige på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

## Kortfattede sammendrag

Følgende tabell viser et sammendrag av sikkerhetsbulletinene for denne måneden etter alvorlighetsgrad.

Hvis du vil ha informasjon om berørt programvare, kan du se den neste delen, **Berørt programvare og nedlastingssteder**.

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Bulletintittel og kortfattet sammendrag</th>
<th>Maksimal alvorlighetsgrad og følger av sikkerhetsproblemet</th>
<th>Krav om omstart</th>
<th>Berørt programvare</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td><strong>Sikkerhetsproblemer i motoren for innebygde OpenType-skrifter kan tillate ekstern kjøring av kode (961371)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i motoren for innebygde OpenType-skrifter (EOT) i Microsoft Windows. Sikkerhetsproblemene kan tillate ekstern kjøring av kode. En angriper som klarer å utnytte et av disse sikkerhetsproblemene, kan få full kontroll over et berørt system eksternt. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft DirectShow kan tillate ekstern kjøring av kode (971633)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ett offentliggjort sikkerhetsproblem og to personlig rapporterte sikkerhetsproblemer i Microsoft DirectShow. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget QuickTime-mediefil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering av kill bits for ActiveX (973346)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem som for øyeblikket utnyttes. Sikkerhetsproblemet i Microsoft Video ActiveX-kontrollen kan tillate ekstern kjøring av kode hvis en bruker viser en spesiallaget webside i Internet Explorer og dermed starter ActiveX-kontrollen. Det var aldri meningen at denne ActiveX-kontrollen skulle starte i Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (972260)</strong><br />
<br />
Denne sikkerhetsoppdateringen publiseres utenfor vanlig sendefrekvens i forbindelse med Microsofts sikkerhetsbulletin MS09-035, som beskriver sikkerhetsproblemer i komponenter og kontroller som er utviklet ved hjelp av sårbare versjoner av Microsoft Active Template Library (ATL). Som en beskyttelse i dybden bidrar denne sikkerhetsoppdateringen for Internet Explorer til å begrense kjente angrepsvektorer i Internet Explorer for de komponentene og kontrollene som er utviklet med sårbare versjoner av ATL, slik det beskrives i Microsofts sikkerhetsveiledning (973882) og Microsofts sikkerhetsbulletin MS09-035.<br />
<br />
Denne sikkerhetsoppdateringen løser tre personlig rapporterte sikkerhetsproblemer i Internet Explorer. Sikkerhetsproblemene kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td><strong>Sikkerhetsproblem i Virtual PC og Virtual Server som kan tillate rettighetsutvidelse (969856)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Virtual PC og Microsoft Virtual Server. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan kjøre vilkårlig kode og få full kontroll over det berørte gjesteoperativsystemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Virtual PC, Virtual Server</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td><strong>Sikkerhetsproblem i Microsoft ISA Server 2006 kan forårsake rettighetsutvidelse (970953)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Internet Security and Acceleration (ISA) Server 2006. Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper klarer å utgi seg for å være en brukerkonto med administrative rettigheter for en ISA Server som er konfigurert for Radius OTP-godkjenning (One Time Password) og godkjenningsdelegering med Kerberos Constrained Delegation.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft ISA Server</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Office Publisher kan tillate ekstern kjøring av kode (969516)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Office Publisher som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Publisher-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td><strong>Sikkerhetsproblemer i Visual Studio Active Template Library kan tillate ekstern kjøring av kode (969706)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser flere personlig rapporterte sikkerhetsproblemer i de offentlige versjonene av Microsoft Active Template Library (ATL) som følger med Visual Studio. Denne sikkerhetsoppdateringen er ment spesifikt for utviklere av komponenter og kontroller. Utviklere som bygger og redistribuerer komponenter og kontroller ved hjelp av ATL, bør installere oppdateringen som er oppgitt i denne bulletinen, og følge veiledningen som er gitt, for å lage og distribuere komponenter og kontroller som ikke er utsatt for sikkerhetsproblemet som beskrives i denne sikkerhetsbulletinen, til kundene sine.<br />
<br />
Denne sikkerhetsbulletinen omtaler sikkerhetsproblemer som kan tillate ekstern kjøring av kode hvis en bruker laster en komponent eller kontroll som er bygd med de sårbare versjonene av ATL.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Visual Studio</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført etter bulletin-ID og CVE-ID.

**Hvordan bruker jeg denne tabellen?**

Bruk denne tabellen til å få mer informasjon om sannsynligheten for at fungerende skadelig kode blir utgitt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Du bør se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Bulletintittel</th>
<th>CVE-ID</th>
<th>Utnyttelsesindeksvurdering</th>
<th>Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td>Sikkerhetsproblemer i Microsoft DirectShow kan tillate ekstern kjøring av kode (971633)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1537">CVE-2009-1537</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td>Sikkerhetsproblemer i Microsoft DirectShow kan tillate ekstern kjøring av kode (971633)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1538">CVE-2009-1538</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=152887">MS09-028</a></td>
<td>Sikkerhetsproblemer i Microsoft DirectShow kan tillate ekstern kjøring av kode (971633)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1539">CVE-2009-1539</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td>Sikkerhetsproblemer i motoren for innebygde OpenType-skrifter kan tillate ekstern kjøring av kode (961371)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0231">CVE-2009-0231</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=139788">MS09-029</a></td>
<td>Sikkerhetsproblemer i motoren for innebygde OpenType-skrifter kan tillate ekstern kjøring av kode (961371)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0232">CVE-2009-0232</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147424">MS09-030</a></td>
<td>Sikkerhetsproblem i Microsoft Office Publisher kan tillate ekstern kjøring av kode (969516)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0566">CVE-2009-0566</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=154993">MS09-031</a></td>
<td>Sikkerhetsproblem i Microsoft ISA Server 2006 kan forårsake rettighetsutvidelse (970953)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1135">CVE-2009-1135</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=157386">MS09-032</a></td>
<td>Kumulativ sikkerhetsoppdatering av kill bits for ActiveX (973346)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-0015">CVE-2008-0015</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett.</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=153891">MS09-033</a></td>
<td>Sikkerhetsproblem i Virtual PC og Virtual Server som kan tillate rettighetsutvidelse (969856)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1542">CVE-2009-1542</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>Kjøring av funksjonell kode er mulig med inkonsekvente utnyttelsesresultater.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (972260)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1917">CVE-2009-1917</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Kjøring av funksjonell kode er enkelt og pålitelig.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (972260)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1918">CVE-2009-1918</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>Kjøring av funksjonell kode er mulig med inkonsekvente utnyttelsesresultater.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158199">MS09-034</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (972260)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1919">CVE-2009-1919</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>Kjøring av funksjonell kode er mulig med inkonsekvente utnyttelsesresultater.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td>Sikkerhetsproblemer i Visual Studio Active Template Library kan tillate ekstern kjøring av kode (969706)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0901">CVE-2009-0901</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Kjøring av funksjonell kode er enkelt og pålitelig.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td>Sikkerhetsproblemer i Visual Studio Active Template Library kan tillate ekstern kjøring av kode (969706)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493">CVE-2009-2493</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Kjøring av funksjonell kode er enkelt og pålitelig.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=158131">MS09-035</a></td>
<td>Sikkerhetsproblemer i Visual Studio Active Template Library kan tillate ekstern kjøring av kode (969706)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2495">CVE-2009-2495</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon uten mulighet til å kjøre kode.</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

Følgende tabeller viser bulletinene etter store programvarekategorier og alvorlighetsgrad.

**Hvordan bruker jeg disse tabellene?**

Bruk disse tabellene til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det kommer noen sikkerhetsoppdateringer som angår installasjonen din. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="5">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1efbbd95-cd72-43df-b1ce-7e2b0c0cb9e2">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3e54348-6548-4162-b4c0-9910ec6e18b3">DirectX 7.0</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce297c3e-8122-4276-a9c2-d1a404f8028d">DirectX 8.1</a>***<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=862db2ad-3c1f-4a26-af70-d8c4f5a69dda">DirectX 9.0</a>****<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=89d941f0-3f71-46e3-8096-716561396b72">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Ingen alvorlighetsgrad**)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50ffc8f4-7ab7-4e64-9965-5767db5f53cd">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93bd1baa-e2fb-4e8c-9dd7-738efef32282">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="5">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
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
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6914167b-6961-480c-a4d4-808cd58a035b">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09d585cb-481d-4767-875e-9c6ebe456b80">DirectX 9.0</a>****<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24701af8-b87e-4e85-9463-f50755a1b6ad">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22bed634-5227-4a22-8df5-801f3e2e232a">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c874c8f8-0449-42b1-8d8b-901040069568">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0acc8aaa-0ae1-412a-9f2b-dc7c707cae00">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3b8b019e-e6d8-4ce2-8f1f-3a6399b252d1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8cd4803-82da-467c-8cb1-520f5a6021d4">DirectX 9.0</a>****<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2cbf3699-7f79-4006-99e9-0a4c0d394c48">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35ab0c5e-df3d-4873-8139-d1d98b3ac350">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=113cc76a-c434-42ff-b594-4834989ad5ba">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29c8d9e6-2cb8-42b6-b0a6-2510fdb49eab">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="5">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=018ef53d-f78e-4084-940d-7c86bf59d83c">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=571d57c5-1ef8-4dc4-a1e5-2211a805f0cc">DirectX 9.0</a>****<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0a458d6-c34c-41c7-964a-c130cfcb0d01">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44852619-58ad-48f2-bc55-e8e1c72b1ba9">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4112c25-9e6f-473a-bdbc-3df6dd66e6af">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4ae65a7-142f-4953-a542-315dac2ac606">Windows Internet Explorer 8</a><br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f5fc902-f5d8-4a87-a73f-68632f9a0935">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1779cbc0-0c29-4fac-a3a6-8b335ffcb98e">DirectX 9.0</a>****<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b7a7bb0-80ef-4f25-bc70-3d0ac06007c5">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd7f36c6-c5c5-4f19-ab59-39f1aaba7fe2">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a594ee0d-ec8f-47df-9125-89d0bbf2115d">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bc0e17b-898b-4f29-aa29-607527e1c1cd">Windows Internet Explorer 8</a><br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7df0fce2-543c-4e82-85e6-012bfc8bf130">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48282a89-f849-405a-a31e-2676f45b5042">DirectX 9.0</a>****<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7be36edf-02af-402f-983a-f9ca8128b6b5">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdb70acf-77c3-40a4-b6a3-0fbc0fc0d7fc">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=adb6bad2-9931-4ede-856e-bb43bb0f6071">Windows Internet Explorer 7</a><br />(Moderat)</td></tr>
              
                <tr><th colspan="5">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c67d85c4-25c5-4821-8db9-91764888f893">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c90240e-c201-4dad-9835-ea71e3527b45">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Ingen alvorlighetsgrad**)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d3be9a13-1a5b-4b74-9649-449df923f573">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b05a19f7-7412-4c2b-ad11-34396e54ca43">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f8ae651-59f7-48e1-9e8c-8e07c6806964">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d2084e8d-212b-4c39-9163-a71ec6d1b1c7">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Ingen alvorlighetsgrad**)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2b23cd74-6cf1-413b-82a7-b602347e3ce6">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=900e9a05-2f71-42de-b603-47e4ac061bcb">Windows Internet Explorer 8</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="5">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=139788">
                      <strong>MS09-029</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=152887">
                      <strong>MS09-028</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=157386">
                      <strong>MS09-032</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158199">
                      <strong>MS09-034</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91f6ee68-0e39-4ec3-b4cd-45f05404e2fb">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0194f994-5821-4fb9-b9e1-ed6af248c995">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Ingen alvorlighetsgrad**)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92e3af41-71b0-4a28-afc7-123733180ead">Windows Internet Explorer 7</a>*<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30f99bda-9107-4969-90af-2a30e12acdae">Windows Internet Explorer 8</a>*<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5cdc3014-97b3-47b5-a6b7-cd0e12ec60e4">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4127b125-fdaa-489a-a80c-14b5647ac7e0">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Ingen alvorlighetsgrad**)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1958ec40-3b7b-43a9-9fdc-742735dcf516">Windows Internet Explorer 7</a>*<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=acd3667b-6676-4010-b23b-e8372dd55f93">Windows Internet Explorer 8</a>*<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03330a14-9cfa-4146-a3d3-4b7a76975d2d">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4082c776-318c-4e0c-83fc-2f3f472c039a">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Ingen alvorlighetsgrad**)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=470387ac-6d75-4b7e-8ca5-376b67a8bd4d">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td></tr>
              </table>


**Merknad for Windows Server 2008**

**\*Server Core-installasjonen av Windows Server 2008 ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 hvis Windows Server 2008 ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS09-032**

**\*\***Alvorlighetsgrader gjelder ikke for denne oppdateringen fordi sikkerhetsproblemet som omtales i denne bulletinen, ikke påvirker denne programvaren. Som et ledd i en mer dyptgående beskyttelse mot eventuelle nye vektorer som kan bli avdekket senere, anbefaler imidlertid Microsoft at kunder som bruker denne programvaren, installerer denne oppdateringen.

**Merknader for MS09-028**

**\*\*\***Oppdateringen for DirectX 8.1 gjelder også for DirectX 8.1b.

**\*\*\*\***Oppdateringen for DirectX 9.0 gjelder også for DirectX 9.0a, DirectX 9.0b og DirectX 9.0c.

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Office-serier, -systemer og -komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147424">
                      <strong>MS09-030</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>2007 Microsoft Office System Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4b0665d-5744-49c7-a3c0-f231fd08d3b8">Microsoft Office Publisher 2007 Service Pack 1</a>
                    <br />(KB969693)<br />(Viktig)</td></tr>
              </table>


#### Utviklerverktøy og programvare fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Visual Studio</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=158131">
                      <strong>MS09-035</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual Studio .NET 2003</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63ce454e-f69c-44e3-89fb-eb23c2e2154e">Microsoft Visual Studio .NET 2003 Service Pack 1</a>
                    <br />(KB971089)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2005</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c8729dc-06a2-4538-a90d-ff9464dc0197">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB971090)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d7ee45b-9892-41b5-ac08-5fde9cde1b42">Microsoft Visual Studio 2005 Service Pack 1</a>*<br />(KB973673)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=43f96f2a-69c6-4c5e-b72c-0edfa35f4fc2">Microsoft Visual Studio 2005 Service Pack 1 64-bit Hosted Visual C++ Tools</a><br />(KB973830)<br />(Moderat)</td></tr>
                <tr><td>Windows Embedded CE 6.0</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99d114f8-4d95-4075-a0f1-45f498f0ade8">Windows Embedded CE 6.0</a>**<br />(KB974616)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Studio 2008</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8f9da646-94dd-469d-baea-a4306270462c">Microsoft Visual Studio 2008</a>
                    <br />(KB971091)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3bb6602-b7f4-4614-9999-77f5c6f66ccd">Microsoft Visual Studio 2008</a>*<br />(KB973674)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=294de390-3c94-49fb-a014-9a38580e64cb">Microsoft Visual Studio 2008 Service Pack 1</a><br />(KB971092)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75fbf397-5140-4961-92a9-78a88ba7228f">Microsoft Visual Studio 2008 Service Pack 1</a>*<br />(KB973675)<br />(Moderat)</td></tr>
                <tr><td>Microsoft Visual C++ 2005</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=766a6af7-ec73-40ff-b072-9112bab119c2">Microsoft Visual C++ 2005 Service Pack 1 Redistributable Package</a>
                    <br />(KB973544)<br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual C++ 2008</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b29655e-9da4-4b6b-9ac5-687ca0770f93">Microsoft Visual C++ 2008 Redistributable Package</a>
                    <br />(KB973551)<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2051a0c1-c9b5-4b0a-a8f5-770a549fd78c">Microsoft Visual C++ 2008 Service Pack 1 Redistributable Package</a><br />(KB973552)<br />(Moderat)</td></tr>
              </table>


**Merknader for MS09-035**

\*For mobile programmer som bruker ATL for Smart Devices

\*\*Installerer den månedlige oppdateringen for Windows Embedded CE 6.0 (desember 2009). Denne oppdateringspakken er bare tilgjengelig fra Microsoft Download Center.

#### Microsoft-server og -sikkerhetsprogramvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Internet Security and Acceleration Server </th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=154993">
                      <strong>MS09-031</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Internet Security and Acceleration Server 2006</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4e9b1dd-526d-407b-bc23-ebc2738b1b19">Microsoft Internet Security and Acceleration Server 2006</a>
                    <br />(KB970811)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8ccd770-a925-411c-b994-78e4cf5c3476">Microsoft Internet Security and Acceleration Server 2006 Supportability Update</a><br />(KB970811)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e536cfed-c1af-4868-b2ac-79178d6355a5">Microsoft Internet Security and Acceleration Server 2006 Service Pack 1</a><br />(KB971143)<br />(Viktig)</td></tr>
              </table>


#### Virtualiseringsprogramvare fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Virtual PC</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=153891">
                      <strong>MS09-033</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Virtual PC 2004</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=56a160e1-59b5-45bc-aecf-dfe614a7efad">Microsoft Virtual PC 2004 Service Pack 1</a>
                    <br />(KB969856)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Virtual PC 2007</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a">Microsoft Virtual PC 2007</a>
                    <br />(KB969856)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0">Microsoft Virtual PC 2007 Service Pack 1</a><br />(KB969856)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Virtual PC 2007 x64 Edition</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5318c1fa-daf1-4028-832b-eaec9906a46a">Microsoft Virtual PC 2007 x64 Edition</a>
                    <br />(KB969856)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88de1513-8d35-410f-8896-fe668f885ca0">Microsoft Virtual PC 2007 x64 Edition Service Pack 1</a><br />(KB969856)<br />(Viktig)</td></tr>
              
                <tr><th colspan="2">Microsoft Virtual Server</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=153891">
                      <strong>MS09-033</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Virtual Server 2005</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85d4f910-4c13-4229-aba7-b9d6181d78c8">Microsoft Virtual Server 2005</a>
                    <br />(KB969856)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Virtual Server 2005 R2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57">Microsoft Virtual Server 2005 R2 Service Pack 1</a>
                    <br />(KB969856)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Virtual Server 2005 R2 x64 Edition</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1481024d-b430-4d0e-be16-2f141c6a7e57">Microsoft Virtual Server 2005 R2 x64 Edition Service Pack 1</a>
                    <br />(KB969856)<br />(Viktig)</td></tr>
              </table>


## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Obs\!**  Fra og med 1. august 2009 vil ikke lenger Microsoft tilby støtte for Office Update og Office Update Inventory Tool. Hvis du vil fortsette å få de nyeste oppdateringene for Microsoft Office-produkter, kan du bruke [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747). Hvis du vil ha mer informasjon, kan du se [Om Microsoft Office Update: Vanlige spørsmål](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

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
  - [Nye, reviderte og utgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows.](http://technet.microsoft.com/en-us/wsus/dd573344,aspx)

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

  - Thomas Garnier hos [SkyRecon](http://www.skyrecon.com/) og Zheng Wenbin, Liu Qi og Song Shenlei hos [Qihoo 360 Security Center](http://www.360.cn/) for rapporten om et sikkerhetsproblem som beskrives i MS09-028
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-028
  - Aaron Portnoy hos [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) og en anonym forsker i samarbeid med TippingPoints [Zero Day Initiative](http://www.zerodayinitiative.com/), Thomas Garnier hos [SkyRecon](http://www.skyrecon.com/) og Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-028
  - [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-029
  - Thomas Garnier for rapporten om et problem som beskrives i MS09-029
  - Lionel d'Hauenens hos [Labo Skopia](http://www.laboskopia.com/), i samarbeid med [VeriSign iDefense Labs](http://www.idefense.com/), for rapporten om et sikkerhetsproblem som beskrives i MS09-030
  - Ryan Smith og Alex Wheeler hos [IBM IIS X-Force](http://www.iss.net/) for først å ha rapportert om et sikkerhetsproblem som beskrives i MS09-032
  - Julien Tinnes og Tavis Ormandy hos [Google Inc.](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-033
  - Peter Vreugdenhil hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-034
  - Wushi og Ling hos [team509](http://www.team509.com/), i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS09-034
  - Peter Vreugdenhil, i samarbeid med [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS09-034
  - David Dewey hos [IBM ISS X-Force](http://www.iss.net/) for rapporten om et sikkerhetsproblem som beskrives i MS09-035
  - Ryan Smith hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS09-035

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (14. juli 2009): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (15. juli 2009): Det kortfattede sammendraget for MS09-032 er oppdatert, omstartskrav for MS09-029 er rettet, og det er utført diverse redigeringer.
  - V2.0 (28. juli 2009): Lagt til Microsofts sikkerhetsbulletin MS09-034, kumulativ sikkerhetsoppdatering for Internet Explorer (972260) og MS09-035, sikkerhetsproblemer i Visual Studio Active Template Library kan tillate ekstern kjøring av kode (969706). Det er også lagt til koblinger til webcast om bulletinen for disse sikkerhetsbulletinene utenfor vanlig sendefrekvens.
  - V3.0 (4. august 2009): Revidert for å informere om at oppdateringen for Microsoft Internet Explorer 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4 er utgitt på nytt. Alle kunder som allerede har installert den opprinnelige oppdateringen for Internet Explorer 6 Service Pack 1 på Microsoft Windows 2000 Service Pack 4, er allerede beskyttet. Det kan imidlertid hende at kunder som har den koreanske språkversjonen av Internet Explorer 6 Service Pack 1, må installere oppdateringen for Internet Explorer 6 Service Pack 1 på Windows 2000-systemene på nytt for å ha samme beskyttelse og løse et utskriftsproblem. Se Microsofts sikkerhetsbulletin MS09-034.
  - V4.0 (11. august 2009): Revidert for å informere om nyutgivelsen av MS09-035. MS09-035 ble utgitt på nytt for å tilby nye oppdateringer for Microsoft Visual Studio 2005 Service Pack 1 (KB973673), Microsoft Visual Studio 2008 (KB973674) og Microsoft Visual Studio 2008 Service Pack 1 (KB973675) for utviklere som bruker Visual Studio til å opprette komponenter og kontroller for mobile programmer ved hjelp av ATL for Smart Devices.
  - V4.1 (13. august 2009): Krav til omstart er korrigert for MS09-035.
  - V5.0 (19. august 2009): Det er lagt til en fotnote for bulletin MS09-028 for å informere om den berørte programvaren for DirectX 8.1.
  - V6.0 (25. august 2009): Revidert for å informere om nyutgivelsen av oppdateringen for japansk for Windows XP Service Pack 2, Windows XP Service Pack 3 og Windows XP Professional x64 Edition Service Pack 2. Alle kunder som allerede har installert den opprinnelige oppdateringen, er allerede beskyttet. Kunder som har den japanske versjonen av Windows XP Service Pack 2, Windows XP Service Pack 3 eller Windows XP Professional x64 Edition Service Pack 2, bør imidlertid installere oppdateringen på nytt for å få den samme beskyttelsen og også løse et utskriftsproblem. Se Microsofts sikkerhetsbulletin MS09-029.
  - V7.0 (12. januar 2010): Revidert for å legge til Windows Embedded CE 6.0 som berørt programvare for MS09-035. Oppdateringen for Windows Embedded CE 6.0 (KB974616) er en kumulativ oppdatering som bare er tilgjengelig fra Microsoft Download Center. Kunder som bruker Windows Embedded CE 6.0-plattformen, bør vurdere å installere den kumulative oppdateringen.
  - V8.0 (9. mars 2010): Revidert for å legge til Microsoft Virtual Server 2005 som berørt programvare for MS09-033.

*Built at 2014-04-18T01:50:00Z-07:00*

