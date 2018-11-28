---
title: Sammendrag av Microsofts sikkerhetsbulletiner for juni 2009
TOCTitle: MS09-JUN
ms:assetid: ms09-jun
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms09-jun(v=Security.10)
ms:contentKeyID: 61315206
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for juni 2009

Publisert: 9. juni 2009

**Versjon:** 1.1

Denne sammendragsbulletinen inneholder en liste over sikkerhetsbulletinene som utgis i juni 2009.

I forbindelse med utgivelsen av bulletinene for juni 2009 erstatter dette bulletinsammendraget forhåndsvarslingen for bulletiner som ble utstedt 4. juni 2009. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletin, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 10. juni 2009 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for juni på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032395225). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=151361">MS09-018</a></td>
<td><strong>Sikkerhetsproblemer i Active Directory kan tillate ekstern kjøring av kode (971055)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i implementeringer av Active Directory på Microsoft Windows 2000 Server og Windows Server 2003 og Active Directory Application Mode (ADAM) når installert på Windows XP Professional og Windows Server 2003. Det mest alvorlige sikkerhetsproblemet kan tillate ekstern kjøring av kode. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system eksternt. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Gode fremgangsmåter for brannmurer og vanlige standard brannmurkonfigurasjoner kan beskytte nettverk mot angrep fra andre steder enn innenfor virksomheten. Gode rutiner anbefaler at systemer som er knyttet til Internett, bør eksponere så få porter som mulig.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td><strong>Sikkerhetsproblemer i utskriftskøen i Windows kan tillate ekstern kjøring av kode (961501)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser tre personlig rapporterte sikkerhetsproblemer i utskriftskøen i Windows. Det alvorligste sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en berørt server mottar en spesiallaget RPC-forespørsel. Gode fremgangsmåter for brannmurer og vanlige standard brannmurkonfigurasjoner kan beskytte nettverk mot angrep fra andre steder enn innenfor virksomheten. Gode rutiner anbefaler at systemer som er knyttet til Internett, bør eksponere så få porter som mulig.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser sju personlig rapporterte sikkerhetsproblemer og ett offentliggjort sikkerhetsproblem i Internet Explorer. De alvorligste av sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147416">MS09-027</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Office Word kan tillate ekstern kjøring av kode (969514)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Word-fil. En angriper som klarer å utnytte et av sikkerhetsproblemene, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser flere personlig rapporterte sikkerhetsproblemer som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-fil som inneholder et misformet postobjekt. En angriper som klarer å utnytte et av disse sikkerhetsproblemene, kan få full kontroll over det berørte systemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128104">MS09-024</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Works-konverteringsprogrammer kan tillate ekstern kjøring av kode (957632)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Works-konverteringsprogrammer. Sikkerhetsproblemet kan tillate ekstern kjøring av kode dersom en bruker åpner en spesiallaget Works-fil. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150174">MS09-026</a></td>
<td><strong>Sikkerhetsproblem i RPC kan tillate rettighetsutvidelse (970238)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i RPC-fasiliteten (Remote Procedure Call) i Windows der RPC-håndteringsmotoren ikke oppdaterer den interne statusen på riktig måte. Sikkerhetsproblemet kan tillate at en angriper kjører vilkårlig kode og får full kontroll over et berørt system. Støttede versjoner av Microsoft Windows leveres ikke med RPC-servere eller -klienter som er berørt av dette sikkerhetsproblemet. I en standardkonfigurasjon kan ikke brukere angripes ved at dette sikkerhetsproblemet utnyttes. Sikkerhetsproblemet finnes imidlertid i kjøretidsversjonen av Microsoft Windows RPC og kan berøre RPC-programmer fra tredjeparter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td><strong>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (968537)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to publiserte og to personlig rapporterte sikkerhetsproblemer i Windows-kjernen som kan tillate rettighetsutvidelse. En angriper som klarer å utnytte et av disse sikkerhetsproblemene, kan kjøre vilkårlig kode og få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte disse sikkerhetsproblemene. Sikkerhetsproblemene kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150568">MS09-020</a></td>
<td><strong>Sikkerhetsproblemer i Internet Information Services (IIS) kan tillate rettighetsutvidelse (970483)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ett publisert sikkerhetsproblem og ett personlig rapportert sikkerhetsproblem i Microsoft Internet Information Services (IIS). Sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en angriper sendte en spesiallaget HTTP-forespørsel til et webområde som krever godkjenning. Disse sikkerhetsproblemene kan tillate at en angriper kan omgå IIS-konfigurasjonen som angir hvilken godkjenningstype som er tillatt, men ikke den filsystembaserte tilgangskontrollisten (ACL) som kontrollerer om en gitt bruker har tilgang til filen eller ikke. Vellykket utnytting av disse sikkerhetsproblemene ville likevel begrense angriperen til tillatelsene som gis til den anonyme brukerkontoen av filsystemets tilgangskontrolliste.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143550">MS09-023</a></td>
<td><strong>Sikkerhetsproblem i Windows Search kan tillate tilgjengeliggjøring av informasjon (963093)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows Search. Dette sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en bruker utfører et søk som returnerer en spesiallaget fil som første resultat, eller hvis brukeren forhåndsviser en spesiallaget fil fra søkeresultatene. Windows Search-komponenten er som standard ikke forhåndsinstallert på Microsoft Windows XP og Windows Server 2003. Det er en valgfri komponent som er tilgjengelig for nedlasting. Windows Search som er installert på støttede versjoner av Windows Vista og Windows Server 2008, berøres ikke av dette sikkerhetsproblemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Tilgjengeliggjøring av informasjon</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=151361">MS09-018</a></td>
<td>Sikkerhetsproblemer i Active Directory kan tillate ekstern kjøring av kode (971055)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1138">CVE-2009-1138</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Konsekvent skadelig kode er usannsynlig</td>
<td>Det er sannsynlig at konsistent utnyttet kode kan føre til tjenestenekt på Windows 2000-servere som eksponerer LDAP eller LDAPS-tjenesten på nettverket. Imidlertid, grunnet flere kontroller på gruppen, vil en fungerende ekstern kodeutnyttelse være svært usannsynlig.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=151361">MS09-018</a></td>
<td>Sikkerhetsproblemer i Active Directory kan tillate ekstern kjøring av kode (971055)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1139">CVE-2009-1139</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Sikkerhetsresultatet til dette sikkerhetsproblemet er en minnelekkasje som til slutt kan føre til tjenestenekt. Det er ikke mulig med kjøring av kode.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-3091">CVE-2007-3091</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1140">CVE-2009-1140</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgang til informasjon på tvers av domener som mest sannsynlig vil føre til tilgjengeliggjøring av informasjon, ikke kjøring av kode.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1141">CVE-2009-1141</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1528">CVE-2009-1528</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1529">CVE-2009-1529</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1530">CVE-2009-1530</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1531">CVE-2009-1531</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150860">MS09-019</a></td>
<td>Kumulativ sikkerhetsoppdatering for Internet Explorer (969897)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1532">CVE-2009-1532</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150568">MS09-020</a></td>
<td>Sikkerhetsproblemer i Internet Information Services (IIS) kan tillate rettighetsutvidelse (970483)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1122">CVE-2009-1122</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Liten sannsynlighet for kjøring av kode, men høy sannsynlighet for tilgjengeliggjøring av informasjon på grunn av situasjoner med omgåelse av godkjenning.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150568">MS09-020</a></td>
<td>Sikkerhetsproblemer i Internet Information Services (IIS) kan tillate rettighetsutvidelse (970483)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1535">CVE-2009-1535</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Offentlig kode er tilgjengelig for tilgjengeliggjøring av informasjon.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0549">CVE-2009-0549</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0557">CVE-2009-0557</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0558">CVE-2009-0558</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0559">CVE-2009-0559</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Det er bare fare for kjøring av kode for Office 2000. Angrep mot nyere versjoner av Office vil sannsynligvis ikke føre til kjøring av kode.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0560">CVE-2009-0560</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0561">CVE-2009-0561</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147294">MS09-021</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Excel kan tillate ekstern kjøring av kode (969462)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1134">CVE-2009-1134</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td>Sikkerhetsproblemer i utskriftskøen i Windows kan tillate ekstern kjøring av kode (961501)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0228">CVE-2009-0228</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td>Sikkerhetsproblemer i utskriftskøen i Windows kan tillate ekstern kjøring av kode (961501)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0229">CVE-2009-0229</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon uten mulighet til å kjøre kode.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=141786">MS09-022</a></td>
<td>Sikkerhetsproblemer i utskriftskøen i Windows kan tillate ekstern kjøring av kode (961501)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0230">CVE-2009-0230</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=143550">MS09-023</a></td>
<td>Sikkerhetsproblem i Windows Search kan tillate tilgjengeliggjøring av informasjon (963093)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0239">CVE-2009-0239</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128104">MS09-024</a></td>
<td>Sikkerhetsproblem i Microsoft Works-konverteringsprogrammer kan tillate ekstern kjøring av kode (957632)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1533">CVE-2009-1533</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1123">CVE-2009-1123</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1124">CVE-2009-1124</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1125">CVE-2009-1125</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150248">MS09-025</a></td>
<td>Sikkerhetsproblemer i Windows-kjernen kan tillate rettighetsutvidelse (968537)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1126">CVE-2009-1126</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>Konsekvent skadelig kode er mest sannsynlig for Windows 2000. Muligheten for kjøring av kode via dette sikkerhetsproblemet med stakkbufferoverflyte reduseres på Windows XP og Windows Server 2003 på grunn av /GS-beskyttelse.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=150174">MS09-026</a></td>
<td>Sikkerhetsproblem i RPC kan tillate rettighetsutvidelse (970238)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0568">CVE-2009-0568</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>Dette sikkerhetsproblemet berører ikke noe Microsoft-programvare direkte. Arbeidsstasjoner der RPC-tjenester er implementert fra uavhengige programvareleverandører, kan imidlertid være sårbare overfor ekstern kjøring av kode hvis denne sikkerhetsoppdateringen ikke installeres.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147416">MS09-027</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Word kan tillate ekstern kjøring av kode (969514)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0563">CVE-2009-0563</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147416">MS09-027</a></td>
<td>Sikkerhetsproblemer i Microsoft Office Word kan tillate ekstern kjøring av kode (969514)</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0565">CVE-2009-0565</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
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
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="8">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bba6e20a-0345-46ae-a6f1-fd27fdee7c21">Active Directory på Microsoft Windows 2000 Server Service Pack 4</a>
                    <br />(KB969805)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=86378753-db24-44c2-a27d-cc0239f40ab8">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d645ad82-13c3-4030-808b-834e86ed3298">Microsoft Internet Explorer 5.01 Service Pack 4</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fe8b3796-a407-4f41-89eb-35b4bcc24ff6">Microsoft Internet Explorer 6 Service Pack 1</a><br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=155a79c1-e5e4-4f62-b4b0-53aca59f20ac">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79b0481d-a3d7-477b-928a-a98cc79374af">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8515a294-4f25-4dc5-860a-e7ad9b6c1c01">Microsoft Internet Information Services 5.0</a>
                    <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="8">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb2c9b76-0c65-4754-9941-d45a7c74a29a">Active Directory Application Mode (ADAM) på Windows XP Professional Service Pack 2 og Windows XP Professional Service Pack 3</a>
                    <br />(KB970437)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f2119aca-a98e-4810-be52-f38241443baf">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3d7f63ee-d7c3-48a5-902e-60625405e97d">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=827b735c-660b-4723-b688-3297e107153a">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d9e27ce1-4e7c-437f-9477-e7805a33da08">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f033fa78-c451-44f8-aa6c-a49622c37f40">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6349e046-a3f8-4ae5-b8c3-c9879cc99e8f">Windows XP Service Pack 2 og Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=97da589f-4534-42f6-9f29-967b5a33c542">Microsoft Internet Information Services 5.1 på Windows XP Professional Service Pack 2 og Windows XP Professional Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=759f22cb-ea7f-49dd-a200-19cb83fffd8d">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ef3aaf0-a2a9-4c17-99ab-a0dc3d3f7e86">Active Directory Application Mode (ADAM)</a>
                    <br />(KB970437)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22699d09-1e68-456a-8733-bfad6667ebf5">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=088f70eb-c5c5-426a-880a-18ed386d0b56">Microsoft Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5d2c81e-ffab-4e3b-a59a-a55000597213">Windows Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a24aedf0-7a31-4ee8-a9a6-998f1160c700">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20734b70-37f1-47dd-bc09-d56f93577a55">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3769800e-af93-4a44-8a1e-b30cc54b226f">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8982e6d2-e1f7-4208-88e3-80b159a8e21a">Microsoft Internet Information Services 6.0</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50c56dd6-c34d-4632-a779-8bcf8fdb341b">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
              
                <tr><th colspan="8">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d814ce65-a193-4027-a6cd-106d388830a6">Active Directory</a> <br />(KB969805)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6f99957-f74f-4446-8734-a468283eebae">Active Directory Application Mode (ADAM)</a> <br />(KB970437)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=865414f8-3f77-4fee-acc6-6684a3dc0aa4">Windows Server 2003 Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72a23752-86fb-4cc9-ab8e-63ffdfae5bec">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a980b867-c67f-4c61-b6db-e55c2ca68dc0">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=298143f2-f37a-4a2c-86ac-9804d4ff1dad">Windows Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62bb9e22-4f4b-4ffc-ba76-f626e94c79d5">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9356404c-d89a-4de0-b9b4-f6e1bdadf745">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bd4e410-dbd8-431a-b316-e1e2f1825c3a">Microsoft Internet Information Services 6.0</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e72ef31f-5161-4fe6-8ed3-6206e02cef31">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0d1f23c8-06eb-4996-92eb-0eb635fd6a42">Active Directory</a>
                    <br />(KB969805)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1a2badc7-c0a5-4032-a009-73ebe9d76313">Active Directory Application Mode (ADAM)</a><br />(KB970437)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=197a6cc7-4ba3-4d2e-b621-0ef3da645ef2">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2a03d3c4-e39d-43a3-8d42-216e9551be96">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5e7d6372-9c8c-449d-88fd-afd4f92ad9e6">Windows Internet Explorer 7</a><br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a5401d7-ca97-4734-a0e9-d7ffe0777e34">Windows Internet Explorer 8</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=888b8dd8-d76c-42f5-a377-1f1750d3cf56">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a3123af-173d-49eb-9997-14e82e764aee">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ea363223-535d-4142-9aba-3890960c6259">Microsoft Internet Information Services 6.0</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ffc3680-f9bf-423b-96a7-102f4cc9c240">Windows Search 4.0</a>
                    <br />(Moderat)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=92e7808b-92ff-449d-bb73-ee8638e9ccd1">Active Directory</a>
                    <br />(KB969805)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=719efd62-fb33-447d-b6dd-2aaafbbad881">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58efde2c-e0b8-4259-b19e-80564b834882">Microsoft Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a2d2907e-67ae-44a4-a805-8670e659ea57">Windows Internet Explorer 7</a><br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3084f46e-02b9-4d99-a7a1-033817f9bd9f">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13b50993-410f-4e7a-a33a-6d9b48dbb4d1">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e6b806eb-e2c4-4436-8964-720db593055d">Microsoft Internet Information Services 6.0</a>
                    <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="8">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
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
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ad8f037-2434-4dea-bfc3-9d3b4008b828">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e60215c3-b8b9-4e45-9d9f-b3fb0b47cce1">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f2730e9-b4fc-4f20-96cf-73f1be63f374">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5ca227c0-f2dd-429c-a542-e08e93527214">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c31b36f8-330c-4a0c-9a3d-7cbe9a1ab8c8">Windows Vista, Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85c317cd-2a14-4747-9f50-3af3ddd3ae1b">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88185088-8c2c-4bc6-89b2-87f4d4849cf7">Windows Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5edb14f7-11ec-4180-9f0f-b2673f1c8d83">Windows Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=188adafe-1feb-46ad-b237-a88d35104dcd">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d70a65f-07ce-4992-8bec-28fefd7587bc">Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="8">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=151361">
                      <strong>MS09-018</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=141786">
                      <strong>MS09-022</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150860">
                      <strong>MS09-019</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150174">
                      <strong>MS09-026</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150248">
                      <strong>MS09-025</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=150568">
                      <strong>MS09-020</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=143550">
                      <strong>MS09-023</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0f18356d-9f09-4d24-8361-970c0d1ccac4">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a0e3f975-57da-43fa-ac12-3d14fd6ce939">Windows Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aaad301c-d232-4733-a0df-8e5d41bbfde8">Windows Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eaa26c6c-5bf7-4099-bb21-1e03de3a25ca">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98ba52b2-da1a-4939-a10e-d43b3a7e7ed4">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7d0a6e8d-a31d-4f3d-a7d7-e61215bfebed">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=758edce7-2a82-4b2e-bd71-5b7075cc4b17">Windows Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faac92d4-4a2b-4bb5-8bd1-1519a9fa8147">Windows Internet Explorer 8</a>**<br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=447aaa4f-946b-4f23-b151-dcf46ea9f80e">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dbaa5a72-c267-4907-a207-525c2803d7b9">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bbac3deb-6c93-45aa-832c-02b915ac7f44">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67d4c189-030d-42eb-98b9-7957ccd92592">Windows Internet Explorer 7</a>
                    <br />(Moderat)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f33012b9-5d5b-4f72-8d49-a8e1c8bc1337">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0e3ad56-a363-44ba-af4d-b7f551c88afd">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              </table>


**Merknader for Windows Server 2008**

**\*Server Core-installasjonen av Windows Server 2008 berørt.** For støttede versjoner av Windows Server 2008 gjelder denne oppdateringen (med samme alvorlighetsgrad) enten Windows Server 2008 ble installert med installasjonsalternativet for Server Core eller ikke. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen av Windows Server 2008 ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 hvis Windows Server 2008 ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet ved å gå til [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="4">Microsoft Office-serier, -systemer og -komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
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
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2000 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3663e9f2-a952-4238-b902-90b5b09feb38">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB969600)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd16e243-b8e2-4afb-86b6-4d60214598eb">Microsoft Office Excel 2000 Service Pack 3</a>
                    <br />(KB969683)<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4bf95806-3d32-411b-9779-a81aebad45e9">Microsoft Office Word 2000 Service Pack 3</a>
                    <br />(KB957838)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1323be1-15f2-491b-abae-c03ba1394398">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB969602)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd80ce95-0aec-4493-b9d1-c3dad95c3415">Microsoft Office Excel 2002 Service Pack 3</a>
                    <br />(KB969680)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0ba8c9e-75ee-46bd-9e92-d4e6599309ad">Microsoft Office Word 2002 Service Pack 3</a>
                    <br />(KB957646)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7cbc2587-2c8c-49b4-9f40-e4cdccb61ecd">Microsoft Office Word 2003 Service Pack 3</a>
                    <br />(KB969603)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10156044-a5a4-4312-98a7-1b1ced625ddb">Microsoft Office Excel 2003 Service Pack 3</a>
                    <br />(KB969681)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7ba3ea7-d06a-4c14-9107-9b92ef68fcae">Microsoft Office Word 2003 Service Pack 3 med Microsoft Works 6–9-filkonverteringsprogram</a>***<br />(KB968326)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e205108-4c28-4cab-a4d0-4ed3fd696473">Microsoft Office Word 2007 Service Pack 1 og Microsoft Office Word 2007 Service Pack 2</a>
                    <br />(KB969604)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2bcd565a-6acb-407d-80da-0398526ddf99">Microsoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2</a>*<br />(KB969682)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bd47e1e5-cd2e-4c08-9864-471e97f38ca3">Microsoft Office Word 2007 Service Pack 1</a>
                    <br />(KB969559)<br />(Viktig)</td></tr>
              
                <tr><th colspan="4">Microsoft Office for Mac</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Office 2004 for Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550">Microsoft Office 2004 for Mac</a>
                    <br />(KB969661)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5557bfb7-ebb4-4c42-8042-41e830c4e550">Microsoft Office 2004 for Mac</a>
                    <br />(KB969661)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2008 for Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58">Microsoft Office 2008 for Mac</a>
                    <br />(KB971822)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58326da2-eb75-4b42-b1bc-e70319defb58">Microsoft Office 2008 for Mac</a>
                    <br />(KB971822)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Open XML File Format Converter for Mac</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6">Open XML File Format Converter for Mac</a>
                    <br />(KB971824)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d6d9eaa-8442-4184-8886-faab2803bde6">Open XML File Format Converter for Mac</a>
                    <br />(KB971824)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="4">Annen Office-programvare</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147416">
                      <strong>MS09-027</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147294">
                      <strong>MS09-021</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128104">
                      <strong>MS09-024</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
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
                <tr class="alternateRow"><td>Microsoft Office Excel Viewer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=20e6933d-85f8-4cec-9534-893789cd053e">Microsoft Office Excel Viewer 2003 Service Pack 3</a>
                    <br />(KB969685)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ac0530dc-7f63-4ad0-85c1-784ad28156cf">Microsoft Office Excel Viewer</a><br />(KB969686)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Office Word Viewer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b">Microsoft Office Word Viewer 2003 Service Pack 3</a>
                    <br />(KB969614)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82980a40-f10c-4f02-b06c-3a12d4434a6b">Microsoft Office Word Viewer</a><br />(KB969614)<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63bd8f14-e736-46ce-af66-d30f17461e5a">Microsoft Office Compatibility Pack Service Pack 1 for filformater for Word, Excel og PowerPoint 2007 og Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB969613)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2">Microsoft Office Compatibility Pack Service Pack 1 for filformater for Word, Excel og PowerPoint 2007 og Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB969679)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Microsoft Works 8.5</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=628280fe-e035-4274-85f2-393d9bad543c">Microsoft Works 8.5</a>
                    <br />(KB967043)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Works 9</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6fa110e-45c6-450f-ae47-c89a06e3f762">Microsoft Works 9</a>
                    <br />(KB967044)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office SharePoint Server</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=862e6ad1-8124-4060-93b1-2b882ef5ce3d">Microsoft Office SharePoint Server 2007 Service Pack 1 og Microsoft Office SharePoint Server 2007 Service Pack 2 (32-biters versjoner)</a>**<br />(KB969737)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7b6e611-2c5d-4639-add9-972055789ecd">Microsoft Office SharePoint Server 2007 Service Pack 1 og Microsoft Office SharePoint Server 2007 Service Pack 2 (64-biters versjoner)</a>**<br />(KB969737)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              </table>


**Merknader for MS09-021**

\*For Microsoft Office Excel 2007 Service Pack 1 og Microsoft Office Excel 2007 Service Pack 2 må kunder i tillegg til å installere sikkerhetsoppdateringspakken KB969682 også installere sikkerhetsoppdateringen for [Microsoft Office Compatibility Pack Service Pack 1 for filformater for Word, Excel og PowerPoint 2007 og Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007](http://www.microsoft.com/downloads/details.aspx?familyid=a8be8457-b0b6-455e-907e-d13be883adf2) (KB969679) for å beskytte seg mot sikkerhetsproblemene som beskrives i denne bulletinen.

\*\*Denne oppdateringen gjelder for servere som har Excel Services installert, for eksempel standardkonfigurasjonen til Microsoft Office SharePoint Server 2007 Enterprise og Microsoft Office SharePoint Server 2007 for Internett-områder. Microsoft Office SharePoint Server 2007 Standard inkluderer ikke Excel Services.

**Merknad for MS09-024**

\*\*\*Microsoft Office Word 2003 berøres hvis et sårbart Works-konverteringsprogram er installert. Works-konverteringsprogrammer er tilgjengelig for Microsoft Office Word 2003 som en nedlasting fra [Microsoft Works 6–9-filkonverteringsprogram](http://www.microsoft.com/downloads/details.aspx?familyid=bf41401e-70fa-465d-ae2e-cf44dbf05297&displaylang=en).

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

  - Joshua J. Drake hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-018
  - Justin Wyatt fra [Beaverton School District](http://www.beaverton.k12.or.us/home/) for rapporten om et sikkerhetsproblem som beskrives i MS09-018
  - David Bloom hos [Google Inc.](http://www.google.com/) for samarbeidet i forbindelse med et sikkerhetsproblem som beskrives i MS09-019
  - Jorge Luis Alvarez Medina hos [Core Security Technologies](http://www.coresecurity.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-019
  - Haifei Li hos [Fortinet](http://www.fortinet.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-019
  - [Tippingpoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-019
  - Peter Vreugdenhil i samarbeid med [Tippingpoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-019
  - Wushi i samarbeid med [Tippingpoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS09-019
  - Nils i samarbeid med [Tippingpoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-019
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-020
  - Bing Liu hos Fortinets [FortiGuard Global Security Research Team](http://www.fortiguardcenter.com/) for rapporten om tre sikkerhetsproblemer som beskrives i MS09-021
  - Carsten H. Eiram hos [Secunia](http://secunia.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS09-021
  - [TELUS Security Labs Vulnerability Research Team](http://telussecuritylabs.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-021
  - Sean Larsson og Joshua Drake hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-021
  - [TippingPoint](http://www.tippingpoint.com/) og [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-021
  - Jun Mao hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-022
  - Yair Amit hos [IBM Rational Application Security](http://blog.watchfire.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-023
  - Shaun Colley hos [NGS Software](http://www.ngssoftware.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-024
  - Thomas Garnier for rapporten om to sikkerhetsproblemer som beskrives i MS09-025
  - Wushi hos [team509](http://www.team509.com/) i samarbeid med [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-027
  - Nicolas Joly hos [VUPEN Security](http://www.vupen.com/) for rapporten om et sikkerhetsproblem som beskrives i MS09-027

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.1 (10. juni 2009): Korrigert vurderinger og nøkkelnotis for CVE-2009-1138 i Exploitability Index.
  - V1.0 (9. juni 2009): Publisert sammendrag av sikkerhetsbulletin.

*Built at 2014-04-18T01:50:00Z-07:00*

