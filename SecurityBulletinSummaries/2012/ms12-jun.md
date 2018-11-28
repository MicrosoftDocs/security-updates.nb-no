---
title: Sammendrag av Microsofts sikkerhetsbulletiner for juni 2012
TOCTitle: MS12-JUN
ms:assetid: ms12-jun
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms12-jun(v=Security.10)
ms:contentKeyID: 61315239
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for juni 2012

Publisert: 12. juni 2012

**Versjon:** 1.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i juni 2012.

I forbindelse med utgivelsen av sikkerhetsbulletinene for juni 2012 erstatter dette sammendraget av bulletiner forhåndsvarslingen for bulletiner som ble utstedt 7. juni 2012. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://go.microsoft.com/fwlink/?linkid=217213).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 13. juni 2012 kl. 11.00 stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for juni på webcast](https://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032499671). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=246927"><strong>MS12-036</strong></a></td>
<td><strong>Sikkerhetsproblem i Remote Desktop kan tillate ekstern kjøring av kode (2685939)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Remote Desktop Protocol. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper sender en serie med spesiallagede RDP-pakker til et berørt system. Som standard er Remote Desktop Protocol (RDP) ikke aktivert på noe Windows-operativsystem. Systemer som ikke har RDP aktivert, er ikke i faresonen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (2699988)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ett offentliggjort sikkerhetsproblem og tolv personlig rapporterte sikkerhetsproblemer i Internet Explorer. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den gjeldende brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251095"><strong>MS12-038</strong></a></td>
<td><strong>Sikkerhetsproblem i .NET Framework kan tillate ekstern kjøring av kode (2706726)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft .NET Framework. Sikkerhetsproblemet kan tillate ekstern kjøring av kode på et klientsystem hvis en bruker viser en spesiallaget webside ved hjelp av en webleser som kan kjøre XAML-leserprogrammer (XBAPer). Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Dette sikkerhetsproblemet kan også brukes av Windows .NET-programmer til å omgå kodetilgangssikkerhetsrestriksjoner (CAS). I et webleserbasert angrepsscenario kan angriperen være vert for et webområde som inneholder en webside som brukes til å utnytte dette sikkerhetsproblemet. I tillegg kan utsatte webområder og webområder som godtar eller er vert for innhold eller reklame fra brukere, ha spesiallaget innhold som kan utnytte dette sikkerhetsproblemet. Men en angriper kan ikke i noen tilfeller tvinge brukere til å gå til disse webområdene. I stedet må angriperen lokke brukere til å besøke webområdet, for eksempel ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som fører dem til angriperens webområde.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows, Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td><strong>Sikkerhetsproblemer i</strong> <strong>Lync</strong> <strong>kan tillate ekstern kjøring av kode (2707956)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ett offentliggjort sikkerhetsproblem og to personlig rapporterte sikkerhetsproblemer i Microsoft Lync. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker viser delt innhold som inneholder spesiallagede True Type-skrifter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Lync</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251612"><strong>MS12-040</strong></a></td>
<td><strong>Sikkerhetsproblem i Microsoft Dynamics AX Enterprise Portal kan forårsake rettighetsutvidelse (2709100)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Dynamics AX Enterprise Portal. Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en bruker klikker på en spesiallaget URL eller går til et spesiallaget webområde. I et e-postangrepsscenario kan en angriper utnytte dette sikkerhetsproblemet ved å sende en e-post med en spesiallaget URL til en bruker av målområdet med Microsoft Dynamics AX Enterprise Portal og ved å få brukeren til å klikke den spesiallagede URL-en. Risikoen er lavere for brukere med Internet Explorer 8 og Internet Explorer 9 som navigerer til et webområde med Microsoft Dynamics AX Enterprise Portal i Internett-sonen. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 vil som standard forhindre dette angrepet i Internett-sonen. XSS-filteret i Internet Explorer 8 og Internet Explorer 9 er som standard ikke aktivert i intranettsonen.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Kan kreve omstart</td>
<td>Microsoft Dynamics AX</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td><strong>Sikkerhetsproblemer i Windows-kjernemodusdrivere kan tillate rettighetsutvidelse (2709162)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer i Microsoft Windows. Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på systemet og deretter kjører et spesiallaget program. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte noen av disse sikkerhetsproblemene.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td><strong>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (2711167)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem og et offentliggjort sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en angriper logger seg på et berørt system og kjører et spesiallaget program som er utformet for å utnytte sikkerhetsproblemet. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte dette sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=246927"><strong>MS12-036</strong></a></td>
<td>Sikkerhetsproblem i Remote Desktop Protocol</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0173">CVE-2012-0173</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med senterelement som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1523">CVE-2012-1523</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med sanitisering i HTML</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Ikke relevant</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon. <a href="http://go.microsoft.com/fwlink/?linkid=252488">MS12-039</a> behandler også dette sikkerhetsproblemet.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem i forbindelse med null byte som kan føre til tilgjengeliggjøring av informasjon</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1873">CVE-2012-1873</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Ikke relevant</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med utviklerverktøylinje som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1874">CVE-2012-1874</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med samme ID-egenskap som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1875">CVE-2012-1875</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>Microsoft kjenner til begrensede angrep som forsøker å utnytte dette sikkerhetsproblemet.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med kolonneelement som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1876">CVE-2012-1876</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med endring av tittelelement som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1877">CVE-2012-1877</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med OnBeforeDeactivate-hendelse som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1878">CVE-2012-1878</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med insertAdjacentText som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1879">CVE-2012-1879</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med insertRow som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1880">CVE-2012-1880</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=249045"><strong>MS12-037</strong></a></td>
<td>Sikkerhetsproblem med OnRowsInserted-hendelse som kan føre til ekstern kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1881">CVE-2012-1881</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Midlertidig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251095"><strong>MS12-038</strong></a></td>
<td>Sikkerhetsproblem med minnetilgang i .NET Framework</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1855">CVE-2012-1855</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sikkerhetsproblem med TrueType-skriftanalyse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-3402">CVE-2011-3402</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Ikke berørt</td>
<td>Permanent</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sikkerhetsproblem med TrueType-skriftanalyse</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0159">CVE-2012-0159</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Ikke berørt</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sikkerhetsproblem med usikker bibliotekinnlasting i Lync</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1849">CVE-2012-1849</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252488"><strong>MS12-039</strong></a></td>
<td>Sikkerhetsproblem med sanitisering i HTML</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1858">CVE-2012-1858</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Skadelig kode er usannsynlig</td>
<td>Ikke relevant</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon. <a href="http://go.microsoft.com/fwlink/?linkid=249045">MS12-037</a> behandler også dette sikkerhetsproblemet.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251612"><strong>MS12-040</strong></a></td>
<td>Sikkerhetsproblem med Dynamics AX Enterprise Portal XSS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1857">CVE-2012-1857</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke berørt</td>
<td>Ikke relevant</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sikkerhetsproblem med String Atom-klassenavnhåndtering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1864">CVE-2012-1864</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sikkerhetsproblem med String Atom-klassenavnhåndtering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1865">CVE-2012-1865</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sikkerhetsproblem med Clipboard Format Atom-navnhåndtering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1866">CVE-2012-1866</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sikkerhetsproblem med heltallsoverflyt i Refcount-skriftressurs</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1867">CVE-2012-1867</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=251707"><strong>MS12-041</strong></a></td>
<td>Sikkerhetsproblem med kappløpssituasjon i Win32k.sys</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1868">CVE-2012-1868</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td>Sikkerhetsproblem med brukermodusplanlegger som kan forårsake minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-0217">CVE-2012-0217</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Ikke berørt</td>
<td>Permanent</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=252515"><strong>MS12-042</strong></a></td>
<td>Sikkerhetsproblem med ROM-feil i BIOS</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2012-1515">CVE-2012-1515</a></td>
<td>Ikke berørt</td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Skadelig kode er sannsynlig</td>
<td>Permanent</td>
<td>Dette sikkerhetsproblemet er publisert.</td>
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
                <tr><th colspan="6">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd2216eb-283b-4a23-b259-018a7fa5fe47">Windows XP Service Pack 3</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f222e05-2a8d-4099-851f-2044811f7425">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=07c75ac6-f92a-4204-aa58-bdf8c033df9e">Internet Explorer 7</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bc1656f-cf1d-4f77-a078-a8602401b8e1">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a399bd47-ffe1-4476-932c-9c119496222a">Windows XP Service Pack 3</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0efff733-4c8d-4fce-8de3-28465c6b762b">Windows XP Service Pack 3</a>
                    <br />(KB2707511) <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e354955-32ae-447c-b16f-960acc01773b">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57e8bf9d-97c3-4166-a5d4-6b0c99afc6a1">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b35e90b-145d-44c2-a8bc-4f9108d46fa1">Internet Explorer 7</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a386b16-74f7-4d36-93d0-75e7da9bf9b5">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdb356db-bd36-4159-8e64-ecdb3dfc61bf">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet  </strong>
                    <strong>alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8e856fec-9f05-49b7-91b6-11c2636a2f1d">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1dcc826-7e96-464b-830e-39946e7802aa">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=de828031-1ace-43df-80f2-db7d503fb0a2">Internet Explorer 7</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e6e5589-b767-4e8a-b8b3-df7b97e002e5">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0b39b00-d7db-4008-8310-1258e84a72a2">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=855611a1-91ad-4d22-8c1c-fdcd6af4cef0">Windows Server 2003 Service Pack 2</a>
                    <br />(KB2707511) <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b63fa4d-b42e-43ca-9f2c-cf60c37731a5">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b060e03b-e63e-446b-9cfd-ea4e1e9383a6">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a36f7ffe-d537-4f9e-b676-22a24f50c089">Internet Explorer 7</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b1acb2f0-63ba-4524-94cf-42b3534e21e7">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk) <br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed7359ce-13e8-42b2-956d-e8be534583aa">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2003 SP2 for Itanium-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dfdc5dc-54b0-49e3-bf5a-bbc40b0f159f">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=893667c4-ef9f-48d3-ab18-a0df51bd3dcc">Internet Explorer 6</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30a9d518-8067-44f4-90fd-09fec8a0c883">Internet Explorer 7</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3206a637-a25e-4cc7-830c-08454ae86f0f">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686828) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2317c8d9-cae8-497b-952e-78eb4a6d585c">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f55b62bf-0571-4888-9061-3f7cc75d7f17">Windows Vista Service Pack 2</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16f4404e-e6d6-4bde-af15-3bb692412213">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=610e753a-21db-43e6-bc42-3e1227fa4bb1">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=828fdb71-747b-481d-9683-895325331478">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9188f1eb-b568-4a99-9b39-745c760a693d">Windows Vista Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab06290c-4f57-4349-8abd-a382b9044631">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=993c5bc4-8903-4c8c-bbc9-da2e47d959f9">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87100a7e-7feb-4a18-b7aa-04fdd2d6ef52">Internet Explorer 8</a><br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b551d67-e0f1-498a-ac4f-06376a0fcf18">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b94ae42-2882-444c-ad5e-74e34b805006">Windows Vista x64 Edition Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812">Windows Server 2008 for 32-biters systemer med Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7f9ad40-d515-4224-90ff-4bd4bff9180f">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4eaeff8-7b7a-4418-a479-09b2146df2bf">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a20c839c-ce3b-46a5-becb-588de404878d">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745">Windows Server 2008 for 32-biters systemer med Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5">Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7420c9f3-8f7e-4823-aaba-b14b957408d8">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fd5308b7-7430-4713-922c-f06c46886fad">Internet Explorer 8</a><br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a737d87-0689-470b-8fc0-8c874af18794">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2">Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c4b8af1c-b483-4aed-9be5-b0f1698b2c28">Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=472842c4-5fe7-4d4c-a927-05be030b5b4e">Internet Explorer 7</a>
                    <br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f4dadc9-733d-46ba-a6a8-92e7b4f49a7b">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2686833) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=098607b3-9424-4440-8832-fc1de010977e">Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows 7 for 32-biters systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef">Windows 7 for 32-biters systemer</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7">Windows 7 for 32-biters systemer</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows 7 for 32-biters systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8549243-e6bf-4007-9bc3-d9c2a24936ef">Windows 7 for 32-biters systemer med Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=595e72c3-f195-4f93-b24e-afe444abd628">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48ca08c8-78cc-4b09-a0ec-bcd208668620">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=605f64bd-0615-47d8-bb32-6bc3e80da4a7">Windows 7 for 32-biters systemer med Service Pack 1</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows 7 for x64-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07">Windows 7 for x64-baserte systemer</a>
                    <br />(KB2685939) <br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c">Windows 7 for x64-baserte systemer</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb">Windows 7 for x64-baserte systemer</a>
                    <br />(KB2709715) <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-baserte systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f0f54e4-b9d9-45d8-bc58-05d7e7b75f07">Windows 7 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30feb2fe-b19b-4d02-8c5b-4499dd6905d1">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bf8dbfee-573b-4d45-a752-90e1d485e503">Internet Explorer 9</a><br />(KB2699988)<br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c77ca1f-2eec-4f95-a769-973b75af184c">Windows 7 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c2b47091-534f-41c3-a229-b5a9ec4b64bb">Windows 7 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2709715) <br />(Viktig) </td></tr>
              
                <tr><th colspan="6">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-baserte systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-baserte systemer</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-baserte systemer</a>
                    <br />(KB2709715) <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9464b044-e40b-4300-97b8-dc3a13c85929">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c8b04-b749-4c6c-8b9f-244abc5f8ecf">Internet Explorer 9</a><br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2709715) <br />(Viktig)</td></tr>
                <tr><td>Windows Server 2008 R2 for Itanium-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc">Windows Server 2008 R2 for Itanium-baserte systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c">Windows Server 2008 R2 for Itanium-baserte systemer</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ecc5d12-9921-4d04-a04c-d69e8f4349dc">Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40302688-fcda-489c-87c4-480d3b9d754c">Internet Explorer 8</a>
                    <br />(KB2699988)<br />(Moderat)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=039ddfe1-3ce5-48d8-8cb4-65481da3f29c">Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="6">Server Core-installasjonsalternativ</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=246927">
                      <strong>MS12-036</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=249045">
                      <strong>MS12-037</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251095">
                      <strong>MS12-038</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251707">
                      <strong>MS12-041</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252515">
                      <strong>MS12-042</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d8dcb487-0df7-46f4-8726-bd58e2722812">Windows Server 2008 for 32-biters systemer med Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6398a156-9618-4ca4-95bc-d36ecacf0745">Windows Server 2008 for 32-biters systemer med Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40c16540-7839-412c-b474-892292a96fa5">Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bc4412ee-8cb8-42e9-96fe-0be49af149b2">Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-baserte systemer</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=68d3694f-fcc9-49e6-93c2-0568b7280236">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686830) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-baserte systemer</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-baserte systemer</a>
                    <br />(KB2709715) <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12740f33-579c-4a75-bec0-9a69e9c64266">Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2685939) <br />(Kritisk)</td><td>Ikke relevant</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=30b16454-cf11-49e1-9032-71c8d2b5d44b">Microsoft .NET Framework 3.5.1</a>
                    <br />(KB2686831) <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fef24f6c-d81a-4078-af5d-dc7d0b53d145">Microsoft .NET Framework 4</a>[1]<br />(KB2686827) <br />(Kritisk)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34d16819-4a2f-42e2-a4f9-88995719cbe8">Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2709162) <br />(Viktig)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1696726a-ed04-4c0e-b9b6-3ac4ac775c4c">Windows Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>
                    <br />(KB2709715) <br />(Viktig)</td></tr>
              </table>


**Merknad** **for** **MS12-0** **3** **8**

\[1\] **.NET Framework 4 og .NET Framework 4 Client Profile er berørt.** Omdistribuerbare pakker for .NET Framework versjon 4 er tilgjengelig i to profiler: .NET Framework 4 og .NET Framework 4 Client Profile. .NET Framework 4 Client Profile er en del av .NET Framework 4. Sikkerhetsproblemet som løses i denne oppdateringen, berører både .NET Framework 4 og .NET Framework 4 Client Profile. Hvis du vil ha mer informasjon, kan du se MSDN-artikkelen om å [installere .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

#### Kommunikasjonsplattformer og -programvare fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Communicator</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252488">
                      <strong>MS12-039</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Communicator 2007 R2</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75eea324-689a-4892-bdd9-03ef399c4cba">Microsoft Communicator 2007 R2</a>
                    <br />(KB2708980)<br />(Viktig)</td></tr>
              
                <tr><th colspan="2">Microsoft Lync</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=252488">
                      <strong>MS12-039</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 (32-biters)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=425406ea-28b9-46f7-8c49-0c7ea46f16e3">Microsoft Lync 2010 (32-biters)</a>
                    <br />(KB2693282)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Lync 2010 (64-biters)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06e5285f-1947-4409-b608-e0a145fadba4">Microsoft Lync 2010 (64-biters)</a>
                    <br />(KB2693282)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 Attendee</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c40f0d38-af90-4966-a0f0-346fa48683d0">Microsoft Lync 2010 Attendee</a>
                    <br />(installasjon på administratornivå)<br />(KB2696031)<br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad864c0e-5850-44a3-b74f-5980a998a384">Microsoft Lync 2010 Attendee</a>[1]<br />(installasjon på brukernivå)<br />(KB2693283)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Lync 2010 Attendant (32-biters)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053">Microsoft Lync 2010 Attendant (32-biters)</a>
                    <br />(KB2702444)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Lync 2010 Attendant (64-biters)</td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe7ad0f9-ee84-4cda-b252-a8d31ead5053">Microsoft Lync 2010 Attendant (64-biters)</a>
                    <br />(KB2702444)<br />(Viktig)</td></tr>
              </table>


**Merknad for MS12-0** **39**

\[1\]Denne oppdateringen er bare tilgjengelig fra Microsoft Download Center.

#### Microsoft Enterprise Resource Planning (ERP) Solutions

<table xmlns="http://www.w3.org/1999/xhtml">
                <tr><th colspan="2">Microsoft Dynamics ERP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=251612">
                      <strong>MS12-040</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Dynamics AX 2012 </td><td>
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=45df362d-8fed-4d99-91c1-81c61878300a">Microsoft Dynamics AX 2012 Enterprise Portal</a>
                    [1]
                    <br />(KB2706738) <br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=780ddcef-19da-44c4-beca-d10b652cd22a">Microsoft Dynamics AX 2012 Enterprise Portal</a>[1]<br />(KB2710639) <br />(Viktig)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=41dc5958-c224-40f9-89c2-179607a8ee2a">Microsoft Dynamics AX 2012 Enterprise Portal</a>[1]<br />(KB2711239) <br />(Viktig)</td></tr>
              </table>


**Merknad for MS12-040**

\[1\]Denne oppdateringen er bare tilgjengelig fra webområdene for Microsoft Download Center, Microsoft Dynamics CustomerSource og Microsoft Dynamics PartnerSource.

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

**System** **Center Configuration Manager**

System Center Configuration Manager Software Update Management forenkler den komplekse oppgaven med å levere og administrere oppdateringer til IT-systemer i hele bedriften. Med System Center Configuration Manager kan IT-administratorer levere oppdateringer av Microsoft-produkter til en rekke enheter, inkludert stasjonære datamaskiner, bærbare datamaskiner, servere og mobile enheter.

Den automatiske sikkerhetsproblemvurderingen i System Center Configuration Manager oppdager behov for oppdateringer og rapporterer om anbefalte handlinger. Software Update Management i System Center Configuration Manager er bygd på Microsoft Windows Software Update Services (WSUS), en tidstestet oppdateringsinfrastruktur som er velkjent for IT-administratorer over hele verden. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke System Center Configuration Manager til å distribuere oppdateringer, kan du se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Hvis du vil ha mer informasjon om System Center Configuration Manager, kan du gå til [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne.

**Obs\!** System Management Server 2003 har ikke vanlig kundestøtte etter 12. januar 2010. Hvis du vil ha mer informasjon om produktlivssykluser, kan du gå til [Microsoft Support Lifecycle](http://support.microsoft.com/common/international.aspx?rdpath=dm;en-us;lifecycle). Den neste utgivelsen av SMS, System Center Configuration Manager, er nå tilgjengelig. Se det tidligere avsnittet **System Center Configuration Manager**.

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

  - En anonym forsker i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - Adi Cohen hos [IBM Security Systems - Application Security](http://blog.watchfire.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - Masato Kinugawa for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - Roman Shafigullin hos LinkedIn for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - Code Audit Labs hos [VulnHunt](http://www.vulnhunt.com) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - Dark Son hos [VulnHunt](http://www.vulnhunt.com) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - [Qihoo 360 Security Center](http://www.360.cn/) for samarbeidet i forbindelse med et sikkerhetsproblem som beskrives i MS12-037
  - Yichong Lin hos McAfee Labs for samarbeidet i forbindelse med et problem som beskrives i MS12-037
  - [Google Inc.](http://www.google.com/) for samarbeidet i forbindelse med et problem som beskrives i MS12-037
  - [VUPEN Security](http://www.vupen.com) i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-037
  - Vitaliy Toropov i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-038
  - hamburgers maccoy via Secunia SVCRP for rapporten om et sikkerhetsproblem som beskrives i MS12-039
  - Adi Cohen hos [IBM Security Systems - Application Security](http://blog.watchfire.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-039
  - Alin Rad Pop i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-039
  - Finian Mackin for rapporten om et sikkerhetsproblem som beskrives i MS12-040
  - Tarjei Mandt hos [Azimuth Security](http://www.azimuthsecurity.com/) for rapporten om tre sikkerhetsproblemer som beskrives i MS12-041
  - [Mateusz "j00ru" Jurczyk](http://j00ru.vexillium.org) hos [Google Inc.](http://www.google.com) for rapporten om et sikkerhetsproblem som beskrives i MS12-041
  - Rafal Wojtczuk hos [Bromium](http://www.bromium.com/) og Jan Beulich hos [SUSE](http://www.suse.com/) for rapporten om et sikkerhetsproblem som beskrives i MS12-042

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Sikkerhetsløsninger for profesjonelle IT-medarbeidere: [TechNet støtte og feilsøking for sikkerhet](http://technet.microsoft.com/security/bb980617.aspx)
  - Bidra til å beskytte Windows-datamaskinen mot virus og skadelig programvare: [Løsnings- og sikkerhetssenter for virus](http://support.microsoft.com/contactus/cu_sc_virsec_master)
  - Lokal støtte for landet ditt: [Internasjonal støtte](http://support.microsoft.com/common/international.aspx)

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (12. juni 2012): Publisert sammendrag av sikkerhetsbulletin.

*Built at 2014-04-18T01:50:00Z-07:00*

