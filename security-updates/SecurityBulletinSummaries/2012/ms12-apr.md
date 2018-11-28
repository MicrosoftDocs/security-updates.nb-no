---
title: Sammendrag av Microsofts sikkerhetsbulletiner for april 2012
TOCTitle: MS12-APR
ms:assetid: ms12-apr
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms12-apr(v=Security.10)
ms:contentKeyID: 61315236
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for april 2012

Publisert: 10. april 2012 | Oppdatert: 26. april 2012

**Versjon:** 2.0

Dette sammendraget av bulletiner inneholder en liste over sikkerhetsbulletinene som utgis i april 2012.

I forbindelse med utgivelsen av sikkerhetsbulletinene for april 2012 erstatter dette sammendraget av bulletiner forhåndsvarslingen for bulletiner som ble utstedt 5. april 2012. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://go.microsoft.com/fwlink/?linkid=217213).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 11. april 2012 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for april på webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499650). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (2675157)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer i Internet Explorer. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den gjeldende brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238623">MS12-024</a></td>
<td><strong>Sikkerhetsproblem i Windows kan tillate ekstern kjøring av kode (2653956)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker kjører eller installerer en spesiallaget, signert, portabel kjørbar fil (PE) på et berørt system.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242032">MS12-025</a></td>
<td><strong>Sikkerhetsproblem i .NET Framework kan tillate ekstern kjøring av</strong> <strong>kode (2671605)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft .NET Framework. Sikkerhetsproblemet kan tillate ekstern kjøring av kode på et klientsystem hvis en bruker viser en spesiallaget webside ved hjelp av en webleser som kan kjøre XAML-leserprogrammer (XBAPer). Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Sikkerhetsproblemet kan videre tillate ekstern kjøring av kode på et serversystem som kjører IIS, hvis den serveren tillater behandling av ASP.NET-sider og en angriper lykkes i å laste opp en spesiallaget ASP.NET-side til den serveren og deretter kjører siden, slik det kan være tilfellet i et webvertscenario. Dette sikkerhetsproblemet kan også brukes av Windows .NET-programmer til å omgå kodetilgangssikkerhetsrestriksjoner (CAS). I et webleserbasert angrepsscenario kan angriperen være vert for et webområde som inneholder en webside som brukes til å utnytte dette sikkerhetsproblemet. I tillegg kan utsatte webområder og webområder som godtar eller er vert for innhold eller reklame fra brukere, ha spesiallaget innhold som kan utnytte dette sikkerhetsproblemet. Men en angriper kan ikke i noen tilfeller tvinge brukere til å gå til disse webområdene. I stedet må angriperen lokke brukere til å besøke webområdet, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246275">MS12-027</a></td>
<td><strong>Sikkerhetsproblem i Windows' vanlige kontroller kan tillate ekstern kjøring av kode (2664258)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows' vanlige kontroller. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker besøker et webområde med innhold som er spesiallaget for å utnytte sikkerhetsproblemet. En angriper kan imidlertid aldri tvinge brukere til å besøke et slikt webområde. I stedet må angriperen lokke brukere til å besøke webområdet, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde. Den skadelige filen kan også sendes som et e-postvedlegg, men angriperen må overbevise brukeren om å åpne vedlegget for å kunne utnytte sikkerhetsproblemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Server-programvare,<br />
Utviklerverktøy fra Microsoft</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238519">MS12-026</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Forefront Unified Access Gateway (UAG) kan tillate tilgjengeliggjøring av informasjon (2663860)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Forefront Unified Access Gateway (UAG). De alvorligste sikkerhetsproblemene kan tillate tilgjengeliggjøring av informasjon hvis en angriper sender en spesiallaget spørring til UAG-serveren.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tilgjengeliggjøring av informasjon</td>
<td>Kan kreve omstart</td>
<td>Microsoft Forefront United Access Gateway</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232498">MS12-028</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Office kan tillate ekstern kjøring av kode (2639185)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Office og Microsoft Works. Sikkerhetsproblemet kan tillate ekstern kjøring av kode dersom en bruker åpner en spesiallaget Works-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den gjeldende brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført etter bulletin-ID og deretter etter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan bruker jeg denne tabellen?**

Bruk denne tabellen til å få mer informasjon om sannsynligheten for angrep i form av kjøring av kode og tjenestenekt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen av denne månedens oppdateringer. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/security/cc998259.aspx).

I kolonnene nedenfor refererer "ny programvareversjon" til den aktuelle programvaren, og "eldre programvareversjoner" refererer til alle eldre, støttede versjoner av den aktuelle programvaren, slik de er oppført i tabellene Berørt programvare eller Uberørt programvare i bulletinen.

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Tittel på sikkerhetsproblem</th>
<th>CVE-ID</th>
<th>Utnyttelsesvurdering for siste programvareversjon</th>
<th>Utnyttelsesvurdering for eldre programvareversjon</th>
<th>Vurdering av utnyttelsesgrad for tjenestenekt</th>
<th>Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>Sikkerhetsproblem i Jscript9 som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0169">CVE-2012-0169</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Ikke berørt</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>Sikkerhetsproblem i OnReadyStateChange som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0170">CVE-2012-0170</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>Sikkerhetsproblem i SelectAll som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0171">CVE-2012-0171</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242739">MS12-023</a></td>
<td>Sikkerhetsproblem i VML Style som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0172">CVE-2012-0172</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238623">MS12-024</a></td>
<td>Sikkerhetsproblem med WinVerifyTrust-signaturvalidering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0151">CVE-2012-0151</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=242032">MS12-025</a></td>
<td>Sikkerhetsproblem med parametervalidering .NET Framework</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0163">CVE-2012-0163</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=238519">MS12-026</a></td>
<td>Sikkerhetsproblem med ufiltrert tilgang til standard UAG-webområde</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0147">CVE-2012-0147</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Ikke berørt</td>
<td>Ikke relevant</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=246275">MS12-027</a></td>
<td>Sikkerhetsproblem med RCE i MSCOMCTL.OCX</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0158">CVE-2012-0158</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke relevant</td>
<td>Microsoft kjenner til begrensede, målrettede angrep som forsøker å utnytte dette sikkerhetsproblemet.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=232498">MS12-028</a></td>
<td>Sikkerhetsproblem med heap-overflyt i Office WPS Converter</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0177">CVE-2012-0177</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke relevant</td>
<td>Microsoft Office 2007 Service Pack 3 og alle støttede versjoner av Microsoft Office 2010 er ikke berørt.</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

Følgende tabeller viser bulletinene etter store programvarekategorier og alvorlighetsgrad.

**Hvordan bruker jeg disse tabellene?**

Bruk disse tabellene til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det kommer noen sikkerhetsoppdateringer som angår installasjonen din. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for ett enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="4">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a490c62-16c4-402a-b2d9-3e8cfb5bcebd">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81b28dd9-87aa-46cc-94c6-2da39d0298db">Internet Explorer 7</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=74ce0e29-046b-4ac3-89a1-b292a177972f">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=575afd20-cee4-4fa9-b781-9f8dfdd41ebe">Windows XP Service Pack 3</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1cfeae57-d4e9-4fff-8956-523e7b71453c">Microsoft .NET Framework 1.0 Service Pack 3</a>
                    <br />(KB2656378)<br />(Bare Media Center Edition 2005 og Tablet PC Edition 2005) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a><br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1b7be43-a32e-456b-8df0-c26cdf187682">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=29ec7b06-c7aa-4149-bb2c-25af7d38a6a9">Internet Explorer 7</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=646c6352-4d99-413a-a75b-71289b5d2b25">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=adc31695-1be6-4976-869c-007df8ac8508">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet  </strong>
                    <strong>alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=020e0d68-dd1c-4297-b565-fcc6dcf5f280">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17b0c139-2709-424d-9d17-827af468e858">Internet Explorer 7</a><br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3289a80a-d1b1-4494-bede-03d0be579acf">Internet Explorer 8</a><br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f79c8940-ca31-4ff7-924e-847f5eef7864">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ffd26218-e149-44ea-a0b9-f2a1315fce9e">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656376) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=295292d3-01a3-4574-b994-8cdbcf5a0d2e">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04656a93-e958-4764-afe8-27c476855506">Internet Explorer 7</a><br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dff4fb63-b319-49ed-8a9d-6b15e43d5bfd">Internet Explorer 8</a><br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03ebf111-1e7b-4dc2-b84f-a26c6b5f0d58">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td>Windows Server 2003 SP2 for Itanium-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09011393-c7d5-4225-9b8e-5a234d4dbcd1">Internet Explorer 6</a>
                    <br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a5ef0147-595e-43b5-819f-73780fcef10d">Internet Explorer 7</a><br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=734ff97a-7d72-4bfe-9557-7fac91902f8e">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c1338821-d8b2-4513-aa35-087323188509">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656369) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f598cad1-4d1a-40ce-a016-bb58778d5dc0">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44284277-06a7-405d-9187-8f50a042604d">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51088164-13b7-4216-90f1-20c92c8b8ca9">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7683919-6d46-4b3e-aa98-1bef20141835">Windows Vista Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2717a997-2066-4a83-ae9b-4611a0851101">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19684033-ddeb-464f-9a22-f580a9c19f8e">Internet Explorer 8</a><br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbb99aee-aadd-4ec7-9e27-91cb8d90803e">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d9f8a6e-17bd-4ed3-8bc7-d5e3b11ca12a">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3e361edd-234b-4053-aa49-278b9fde4d5c">Internet Explorer 7</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6eb6781e-7b38-4679-afbc-4e3bb5747fd8">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d34d7981-ed63-460d-95e4-e6da1ac41d2f">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c36c20f7-a742-4151-b8f2-85ef80479d06">Windows Server 2008 for 32-biters systemer Service Pack 2</a>*<br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td>Windows Server 2008 for x64-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60b76a3c-4530-4101-931f-45df621e1eed">Internet Explorer 7</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd657467-a45c-4354-b947-3a3cceb9b690">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9d773e9-6a2e-45db-8f30-7da0082d909c">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=330cea47-221d-439e-b106-58a146fc28ee">Windows Server 2008 for x64-baserte systemer Service Pack 2</a>*<br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3235216f-497f-4934-81b8-1eb9929e98c9">Internet Explorer 7</a>
                    <br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1ec74522-ec1e-4b3c-bfeb-6a505cc4f11a">Windows Server 2008 for Itanium-baserte systemer Service Pack 2</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c376fbdc-2289-47b6-950b-4e668cd3a390">Microsoft .NET Framework 1.1 Service Pack 1</a>
                    <br />(KB2656370) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e1c10a1-9cb2-4815-8aa6-e401ced5df80">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2656374) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-biters systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8">Windows 7 for 32-biters systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for 32-biters systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a58ca0b-fad7-418e-80ae-ca478168f887">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6724be3-ff4b-4dea-95f3-0b13998b6758">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac183b66-0247-4ae5-bda0-e8d0070917c8">Windows 7 for 32-biters systemer med Service Pack 1</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td>Windows 7 for x64-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430">Windows 7 for x64-baserte systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-baserte systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7215f707-c536-4d81-ad66-e7bff592e400">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0ff822d0-074a-409c-9174-8100618c6171">Internet Explorer 9</a><br />(KB2675157)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27226e64-266f-499e-8c57-866593fc3430">Windows 7 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="4">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242739">
                      <strong>MS12-023</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238623">
                      <strong>MS12-024</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=242032">
                      <strong>MS12-025</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td>Windows Server 2008 R2 for x64-baserte systemer<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a">*</a><br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=237d94e6-b9b9-4177-81fa-a67df2806b0e">Internet Explorer 8</a>**<br />(KB2675157)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d002bfe4-10e9-46d3-a460-06d112201ca5">Internet Explorer 9</a>**<br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54db1495-31bb-4435-a442-74e484630b8a">Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>*<br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>*[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr><td>Windows Server 2008 R2 for Itanium-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2">Windows Server 2008 R2 for Itanium-baserte systemer</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3f521a9-4dc8-46b7-a7f2-696b8759b398">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656372) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7bdba902-0a6e-451e-a29b-6d0a03ff5664">Internet Explorer 8</a>
                    <br />(KB2675157)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a4115bf-028b-4dcc-8995-d3341fdf42f2">Windows Server 2008 R2 for Itanium-based Systems Service Pack 1</a>
                    <br />(KB2653956)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=efccca8d-1371-4cda-96ab-ceef735742e2">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2656373) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40b1ae34-28ad-41a0-88df-b905517e4acf">Microsoft .NET Framework 4</a>[1]<br />(KB2656368) <br />(Kritisk)</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad** **for** **MS12-02** **5**

\[1\] **.NET Framework 4 og .NET Framework 4 Client Profile er berørt.** Omdistribuerbare pakker for .NET Framework versjon 4 er tilgjengelig i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er en del av .NET Framework 4. Sikkerhetsproblemet som løses i denne oppdateringen, berører både .NET Framework 4 og .NET Framework 4 Client Profile. Hvis du vil ha mer informasjon, kan du se MSDN-artikkelen om å [installere .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="3">Microsoft Office-serier og -komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft Office 2003 Service Pack 3</a>
                    <br />(Windows' vanlige kontroller)<br />(KB2597112) <br />(Kritisk)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft Office 2007 Service Pack 2</a>
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fbf24cc6-89e1-48dd-bb83-23eed30195e1">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2596871)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft Office 2007 Service Pack 3</a>
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (32-biters versjoner)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b">Microsoft Office 2010 (32-biters versjoner)</a>
                    <br />(Windows' vanlige kontroller)<br />(KB2598039) <br />(Kritisk)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office 2010 Service Pack 1 (32-biters versjoner)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c9d7bf-c9e0-4e01-8b66-da542332a28b">Microsoft Office 2010 Service Pack 1 (32-biters versjoner)</a>
                    <br />(Windows' vanlige kontroller)<br />(KB2598039) <br />(Kritisk)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Microsoft Office Web Components</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Web Components Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft Office 2003 Web Components Service Pack 3</a>
                    <br />(Windows' vanlige kontroller)<br />(KB2597112) <br />(Kritisk)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Annen Microsoft Office-programvare</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=232498">
                      <strong>MS12-028</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Works 9</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=94e17a66-cf09-4314-89ec-53deadabfa66">Microsoft Works 9</a>
                    <br />(KB2680317) <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Works 6-9-filkonverteringsprogram </td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4605f684-6314-4758-adeb-2a8810dfc8d1">Microsoft Works 6-9-filkonverteringsprogram </a>
                    <br />(KB2680326) <br />(Viktig)</td></tr>
              </table>


**Merknad for MS12-027**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Microsoft Server-programvare

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft SQL Server</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft SQL Server 2000 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=198f1819-818b-4b2e-a424-4a45729746eb">Microsoft SQL Server 2000 Analysis Services Service Pack 4</a>
                    <br />(KB983807) <br />(Kritisk)<br /><br />GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a9d97e8-79e0-4997-88fe-1224707e1b37">Microsoft SQL Server 2000 Service Pack 4</a><br />(KB983808) <br />(Kritisk)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8d0cac2f-f227-4e00-9454-4df62be86407">Microsoft SQL Server 2000 Service Pack 4</a><br />(KB983809) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Microsoft SQL Server-komponenter</th></tr>
              
                <tr class="alternateRow"><td>Microsoft SQL Server 2005 for 32-biters systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 for 32-biters systemer Service Pack 4</a>
                    [1]
                    <br />(Windows' vanlige kontroller)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2005 for Itanium-baserte systemer Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 for Itanium-baserte systemer Service Pack 4</a>
                    [1]
                    <br />(Windows' vanlige kontroller)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2005 for x64-baserte systemer Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 for x64-baserte systemer Service Pack 4</a>
                    [1]
                    <br />(Windows' vanlige kontroller)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2005 Express Edition med Advanced Services Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d0d34b4f-4bcd-4df7-8ebc-87367e889959">Microsoft SQL Server 2005 Express Edition med Advanced Services Service Pack 4</a>
                    [1]
                    <br />(Windows' vanlige kontroller)<br />(KB2597112) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 for 32-biters systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for 32-biters systemer Service Pack 2</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for 32-biters systemer Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for 32-biters systemer Service Pack 3</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 for x64-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for x64-baserte systemer Service Pack 2</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for x64-baserte systemer Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for x64-baserte systemer Service Pack 3</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 for Itanium-baserte systemer Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for Itanium-baserte systemer Service Pack 2</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for Itanium-baserte systemer Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for Itanium-baserte systemer Service Pack 3</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 R2 for 32-biters systemer </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for 32-biters systemer</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for 32-biters systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for 32-biters systemer Service Pack 1</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 R2 for x64-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for x64-baserte systemer</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2008 for x64-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 for x64-baserte systemer Service Pack 1</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft SQL Server 2008 R2 for Itanium-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for Itanium-baserte systemer</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft SQL Server 2008 R2 for Itanium-baserte systemer Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17294713-5c03-4439-bcae-471e9b1e1ac9">Microsoft SQL Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    [2]
                    <br />(Windows' vanlige kontroller)<br />(KB2598041) <br />(Kritisk)</td></tr>
              </table>


**Merknader** **for** **MS12-02** **7**

\[1\]Denne oppdateringen er den samme som KB2597112-oppdateringen for Microsoft Office 2003

\[2\]Denne oppdateringen er den samme som KB2598041-oppdateringen for Microsoft Office 2007

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft BizTalk Server</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft BizTalk Server 2002 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d90b78d2-551b-499b-9bd2-85b40646dbc7">Microsoft BizTalk Server 2002 Service Pack 1</a>
                    <br />(KB2645025) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Microsoft Commerce Server</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Commerce Server 2002 Service Pack 4</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35de8833-50ae-482d-aa07-497bf68fb38e">Microsoft Commerce Server 2002 Service Pack 4</a>
                    <br />(KB2658674) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft Exchange Server 2007 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3f04fb90-8f11-4392-a4bc-800903091f04">Microsoft Exchange Server 2007 Service Pack 2</a>
                    <br />(KB2658677) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Commerce Server 2009</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8998b6b-e9a4-457e-a34f-0458dda81f2f">Microsoft Commerce Server 2009</a>
                    <br />(KB2655547) <br />(Kritisk)</td></tr>
                <tr><td>Microsoft Commerce Server 2009 R2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9221811-8913-412b-ae04-21a55ce7c4c5">Microsoft Commerce Server 2009 R2</a>
                    <br />(KB2658676) <br />(Kritisk)</td></tr>
              </table>


**Merknad for MS12-027**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Utviklerverktøy og programvare fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Visual FoxPro</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual FoxPro 8.0 Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a7ff474-f1e0-4c86-9555-64e8e7357890">Microsoft Visual FoxPro 8.0 Service Pack 1</a>
                    <br />(KB2647488) <br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual FoxPro 9.0 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53c0132e-7724-4e94-abe9-e79b76ce35d7">Microsoft Visual FoxPro 9.0 Service Pack 2</a>
                    <br />(KB2647490) <br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Visual Basic</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246275">
                      <strong>MS12-027</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Visual Basic 6.0 Runtime</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0afe933a-1e62-45c4-910c-ea94b203df5a">Visual Basic 6.0 Runtime</a>
                    <br />(KB2641426) <br />(Kritisk)</td></tr>
              </table>


**Merknad for MS12-027**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Microsoft-programvare for ekstern pålogging

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Forefront Unified Access Gateway</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=238519">
                      <strong>MS12-026</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Forefront Unified Access Gateway</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4b4ecc4-8bc6-43d0-b872-93673e0d9a6f">Microsoft Forefront Unified Access Gateway 2010 Service Pack 1</a>
                    [1]
                    <br />(KB2649261)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0f9acab-bfb8-4758-b60d-64e68a84fba0">Microsoft Forefront Unified Access Gateway 2010 Service Pack 1, oppdatering 1</a>[1]<br />(KB2649262)<br />(Viktig)</td></tr>
              </table>


**Merknad** **for** **MS12-026**

\[1\]Denne oppdateringen er bare tilgjengelig fra Microsoft Download Center.

## Veiledning og verktøy for søking og distribusjon

**Sikkerhetssentral**

Administrer programvare- og sikkerhetsoppdateringene du må installere på serverne og de stasjonære og bærbare datamaskinene i bedriften. Hvis du vil ha mer informasjon, kan du se [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). [TechNet Security Center](http://go.microsoft.com/fwlink/?linkid=21171) gir ytterligere informasjon om sikkerhet for Microsoft-produkter. Forbrukere kan også gå til [Sikkerhet hjemme](http://go.microsoft.com/fwlink/?linkid=85102), der denne informasjonen er tilgjengelig under Siste sikkerhetsoppdateringer.

Sikkerhetsoppdateringer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) og [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130). Sikkerhetsoppdateringer finnes også på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".

For kunder med Microsoft Office for Mac kan Microsoft AutoUpdate for Mac hjelpe med å holde Microsoft-programvaren oppdatert. Hvis du vil ha mer informasjon om bruk av Microsoft AutoUpdate for Mac, kan du se [Check for software updates automatically](http://mac2.microsoft.com/help/office/14/en-us/word/item/ffe35357-8f25-4df8-a0a3-c258526c64ea).

Sist, men ikke minst kan sikkerhetsoppdateringer lastes ned fra [Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=96155). Microsoft Update-katalogen tilbyr en søkbar innholdskatalog som er gjort tilgjengelig via Windows Update og Microsoft Update, inkludert sikkerhetsoppdateringer, drivere og oppdateringspakker. Hvis du søker ved å bruke nummeret for sikkerhetsbulletinen (som MS07-036), kan du legge til alle de gjeldende oppdateringene i kurven (inkludert forskjellige språk for en oppdatering) og laste dem ned til en valgfri mappe. Hvis du vil ha mer informasjon om Microsoft Update-katalogen, kan du se [Vanlige spørsmål i Microsoft Update-katalogen](http://go.microsoft.com/fwlink/?linkid=97900).

**Veiledning for søking og distribusjon**

Microsoft tilbyr veiledning for søking etter og distribusjon av sikkerhetsoppdateringer. Denne veiledningen inneholder anbefalinger og informasjon som kan hjelpe IT-eksperter med å forstå hvordan ulike verktøy for søking etter og distribusjon av sikkerhetsoppdateringer skal brukes. Du finner mer informasjon i [Microsoft Knowledge Base-artikkel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

Med MBSA kan administratorer søke etter manglende sikkerhetsoppdateringer i tillegg til vanlige sikkerhetskonfigurasjoner på lokale og eksterne systemer. Du finner mer informasjon om MBSA på [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Med Windows Server Update Services (WSUS) kan administratorer raskt og trygt distribuere de nyeste kritiske oppdateringene og sikkerhetsoppdateringene for Microsoft Windows 2000 og nyere operativsystemer, Office XP og nyere, Exchange Server 2003 og SQL Server 2000 til Microsoft Windows 2000 og nyere operativsystemer.

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/default.aspx).

**System Center Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse oppgaven med å levere og administrere oppdateringer til IT-systemer i hele bedriften. Med Configuration Manager 2007 kan IT-administratorer levere oppdateringer av Microsoft-produkter til en rekke enheter, inkludert stasjonære datamaskiner, bærbare datamaskiner, servere og mobile enheter.

Den automatiske sikkerhetsproblemvurderingen i Configuration Manager 2007 oppdager behov for oppdateringer og rapporterer om anbefalte handlinger. Software Update Management i Configuration Manager 2007 er bygd på Microsoft Windows Software Update Services (WSUS), en tidstestet oppdateringsinfrastruktur som er velkjent for IT-administratorer over hele verden. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke Configuration Manager 2007 til å distribuere oppdateringer, kan du se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Hvis du vil ha mer informasjon om Configuration Manager, kan du gå til [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne.

**Obs\!** System Management Server 2003 har ikke vanlig kundestøtte etter 12. januar 2010. Hvis du vil ha mer informasjon om produktlivssykluser, kan du gå til [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den neste utgivelsen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se det tidligere avsnittet **System Center Configuration Manager 2007**.

Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du se [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer for å gi bred støtte i forbindelse med søking etter og distribusjon av sikkerhetsbulletinoppdateringer. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validering av Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte oppdateringer på MU, WU og WSUS

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Innholdet i beskrivelsen av Software Update Services og Windows Server Update Services endres. Omfatter alt Windows-innhold.
  - [Oppdateringer de siste månedene for Windows Server Update Services](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Vis alle nye, reviderte og nyutgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows.

#### Microsoft Active Protections Program (MAPP)

For å forbedre sikkerheten for kundene gir Microsoft store leverandører av sikkerhetsprogramvare informasjon om sikkerhetsproblemer før hver månedlige utgivelse av sikkerhetsoppdateringer. Leverandører av sikkerhetsprogramvare kan deretter bruke denne informasjonen om sikkerhetsproblemer til å oppdatere beskyttelsen til kundene via sikkerhetsprogramvaren eller -enhetene deres, som antivirusprogrammer, nettverksbaserte systemer for oppdaging av inntrengere eller vertsbaserte systemer for forhindring av inntrengere. Hvis du vil finne ut om det finnes aktiv beskyttelse tilgjengelig fra leverandører av sikkerhetsprogramvare, kan du gå til webområdene for aktiv beskyttelse fra programpartnerne som er oppført i artikkelen om [MAPP-programpartnere (Microsoft Active Protections Program)](http://go.microsoft.com/fwlink/?linkid=215201).

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

  - linx2008 i [AISec](http://www.aisec.cn/) for rapporten om et sikkerhetsproblem som beskrives i MS12-023
  - Roel Spilker i [TOPdesk](http://www.topdesk.com) for rapporten om et sikkerhetsproblem som beskrives i MS12-023
  - Jose Antonio Vazquez Gonzalez i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com) for rapporten om et sikkerhetsproblem som beskrives i MS12-023
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com) for rapporten om et sikkerhetsproblem som beskrives i MS12-023
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com)[Zero Day Initiative](http://www.zerodayinitiative.com) for rapporten om et sikkerhetsproblem som beskrives i MS12-023
  - Masato Kinugawa for samarbeidet om endringer i dybdeforsvar som er inkludert i MS12-023
  - Robert Zacek og Igor Glucksmann i [Avast Software](http://www.avast.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-024
  - Vitaliy Toropov i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-025
  - Shaun Colley i [IOActive, Ltd.](http://ioactive.co.uk/) for rapporten om et sikkerhetsproblem som beskrives i MS12-028

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Sikkerhetsløsninger for profesjonelle IT-medarbeidere: [TechNet støtte og feilsøking for sikkerhet](http://technet.microsoft.com/security/bb980617.aspx)
  - Bidra til å beskytte Windows-datamaskinen mot virus og skadelig programvare: [Løsnings- og sikkerhetssenter for virus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
  - Lokal støtte for landet ditt: [Internasjonal støtte](http://support.microsoft.com/common/international.aspx)

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (10. april 2012): Publisert sammendrag av sikkerhetsbulletin.
  - V2.0 (26. april 2012): For MS12-027 er Service Pack 1-versjoner av SQL Server 2008 R2 lagt til under Berørt programvare, og Berørt programvare er gjort klarere for å vise at oppdateringen gjelder alle installasjoner av Microsoft SQL Server 2000 Analysis Services Service Pack 4, da skillet mellom QFE og GDR ikke er relevant for dette produktet. Dette er bare informasjonsendringer. Det var ingen endringer i filer for sikkerhetsoppdateringen eller søkelogikken. Fordi riktige oppdateringer har vært tilgjengelige siden den opprinnelige utgivelsen, trenger ikke kunder å gjøre noe mer hvis de allerede har installert oppdateringer.

*Built at 2014-04-18T01:50:00Z-07:00*

