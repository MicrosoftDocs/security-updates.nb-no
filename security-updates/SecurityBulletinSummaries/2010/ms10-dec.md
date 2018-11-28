---
title: Sammendrag av Microsofts sikkerhetsbulletiner for desember 2010
TOCTitle: MS10-DEC
ms:assetid: ms10-dec
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms10-dec(v=Security.10)
ms:contentKeyID: 61315214
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for desember 2010

Publisert: 14. desember 2010 | Oppdatert: 15. desember 2010

**Versjon:** 1.1

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i desember 2010.

I forbindelse med utgivelsen av bulletinene for desember 2010 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 9. desember 2010. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 15. desember 2010 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for desember på webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032454444&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (2416400)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fire personlig rapporterte sikkerhetsproblemer og tre offentliggjorte sikkerhetsproblemer i Internet Explorer. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td><strong>Sikkerhetsproblemer i OpenType-skriftformatet (OTF) kan tillate ekstern kjøring av kode (2296199)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser flere personlig rapporterte sikkerhetsproblemer i Windows OpenType-skriftformatet (OTF) som kan tillate ekstern kjøring av kode. En angriper kan være vert for en spesiallaget OpenType-skrift på en delt nettverksressurs. Den berørte kontrollbanen utløses deretter når brukeren navigerer til denne ressursen i Windows Utforsker og gjør at den spesiallagde skriften kan ta fullstendig kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td><strong>Sikkerhetsproblem i Oppgaveplanlegger kan tillate rettighetsutvidelse (2305420)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i Windows Oppgaveplanlegger. Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på et berørt system og kjører et spesiallaget program. En angriper må ha gyldig legitimasjon for pålogging og må kunne logge seg på lokalt for å kunne utnytte sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td><strong>Sikkerhetsproblem i Windows Movie Maker kan tillate ekstern kjøring av kode (2424434)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i Windows Movie Maker. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper lokker en bruker til å åpne en legitim Windows Movie Maker-fil som ligger på samme nettverkskatalog som en spesiallaget biblioteksfil. For at et angrep skal lykkes, må brukeren besøke en ikke-klarert ekstern filsystemplassering eller delt WebDAV-ressurs og åpne et dokument fra denne plasseringen som deretter blir lastet inn av et sårbart program.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td><strong>Sikkerhetsproblem i Windows Media Encoder kan tillate ekstern kjøring av kode (2447961)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i Windows Media Encoder. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper lokker en bruker til å åpne en legitim Windows Media Profile-fil (PRX) som ligger på samme nettverkskatalog som en spesiallaget biblioteksfil. For at et angrep skal lykkes, må brukeren besøke en ikke-klarert ekstern filsystemplassering eller delt WebDAV-ressurs og åpne et dokument fra denne plasseringen som deretter blir lastet inn av et sårbart program.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Windows kan tillate ekstern kjøring av kode (2385678)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en filtype som EML og RSS (Windows Live Mail) eller WPOST (Microsoft Live Writer) som ligger i samme nettverksmappe som en spesiallaget biblioteksfil. For at et angrep skal lykkes, må brukeren besøke en ikke-klarert ekstern filsystemplassering eller delt WebDAV-ressurs og åpne et dokument fra denne plasseringen som deretter blir lastet inn av et sårbart program.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td><strong>Sikkerhetsproblem i Windows-adresseboken kan tillate ekstern kjøring av kode (2423089)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i Windows-adresseboken. Sikkerhetsproblemet kan tillate ekstern kjøring av kode dersom en bruker åpner en Windows-adressebokfil som ligger i samme nettverksmappe som en spesiallaget biblioteksfil. For at et angrep skal lykkes, må brukeren besøke en ikke-klarert ekstern filsystemplassering eller delt WebDAV-ressurs og åpne et dokument fra denne plasseringen som deretter blir lastet inn av et sårbart program.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td><strong>Sikkerhetsproblem med usikker bibliotekslasting i veiviseren for registrering av Internett-tilkobling kan tillate ekstern kjøring av kode (2443105)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem i veiviseren for registrering av Internett-tilkobling i Microsoft Windows. Denne sikkerhetsoppdateringen har alvorlighetsgraden Viktig for alle støttede versjoner av Windows XP og Windows Server 2003. Ingen støttede versjoner av Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er berørt av sikkerhetsproblemet.<br />
<br />
Sikkerhetsproblemet kan tillate ekstern kjøring av kode dersom en bruker åpner en INS- eller ISP-fil som ligger i samme nettverksmappe som en spesiallaget biblioteksfil. For at et angrep skal lykkes, må brukeren besøke en ikke-klarert ekstern filsystemplassering eller delt WebDAV-ressurs og åpne et dokument fra denne plasseringen som deretter blir lastet inn av et sårbart program.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td><strong>Sikkerhetsproblemer i Windows-kjernemodusdrivere kan tillate rettighetsutvidelse (2436673)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser ett offentliggjort sikkerhetsproblem og flere personlig rapporterte sikkerhetsproblemer i Microsoft Windows. Disse sikkerhetsproblemene kan tillate rettighetsutvidelse hvis en angriper logger seg på lokalt og kjører et spesiallaget program. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte disse sikkerhetsproblemene. Sikkerhetsproblemene kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td><strong>Sikkerhetsproblem med ruting og ekstern tilgang kan tillate rettighetsutvidelse (2440591)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i NDProxy-komponenten for ruting og ekstern pålogging i Microsoft Windows. Denne sikkerhetsoppdateringen har alvorlighetsgraden Viktig for alle støttede versjoner av Windows XP og Windows Server 2003. Ingen støttede versjoner av Windows Vista, Windows Server 2008, Windows 7 og Windows Server 2008 R2 er berørt av sikkerhetsproblemet.<br />
<br />
Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på et berørt system og kjører et spesiallaget program. En angriper må ha gyldig legitimasjon for pålogging og må kunne logge seg på lokalt for å kunne utnytte sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td><strong>Sikkerhetsproblem med brukergrensesnitt for samtykke kan tillate rettighetsutvidelse (2442962)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i brukergrensesnittet (UI) for samtykke. Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper kjører et spesiallaget program på et berørt system. En angriper må ha gyldig legitimasjon for pålogging og SeImpersonatePrivilege og må kunne logge seg på lokalt for å kunne utnytte sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td><strong>Sikkerhetsproblem i Netlogon-tjenesten i Windows kan føre til tjenestenekt (2207559)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Netlogon RPC-tjenesten på berørte versjoner av Windows Server som er konfigurert for å være domenekontrollere. Sikkerhetsproblemet kan føre til tjenestenekt hvis en angriper sender en spesiallaget RPC-pakke til grensesnittet for Netlogon RPC-tjenesten på et berørt system. En angriper krever administratorrettigheter på en maskin som er knyttet til det samme domenet som den berørte domenekontrolleren, for å kunne utnytte sikkerhetsproblemet.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td><strong>Sikkerhetsproblem i Hyper-V kan føre til tjenestenekt (2345316)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows Server 2008 Hyper-V og Windows Server 2008 R2 Hyper-V. Dette sikkerhetsproblemet kan føre til tjenestenekt hvis en spesiallaget pakke sendes til VMBus av en godkjent bruker i en av de virtuelle gjestemaskinene som Hyper-V-serveren er vert for. En angriper må ha gyldig påloggingsinformasjon og må kunne sende spesiallaget innhold fra en virtuell gjestemaskin for å kunne utnytte dette sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td>Krever omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Publisher kan tillate ekstern kjøring av kode (2292970)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser fem personlig rapporterte sikkerhetsproblemer i Microsoft Publisher som kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Publisher-fil. En angriper som klarer å utnytte et av disse sikkerhetsproblemene, kan få full kontroll over det berørte systemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td><strong>Sikkerhetsproblem i Microsoft SharePoint kan tillate ekstern kjøring av kode (2455005)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft SharePoint. Sikkerhetsproblemet kan tillate ekstern kjøring av kode i sikkerhetskonteksten til en gjestebruker hvis en angriper sender en spesiallaget SOAP-forespørsel til starttjenesten for dokumentkonverteringer i et SharePoint-servermiljø som bruker belastningsfordelingstjenesten for dokumentkonverteringer. Som standard er ikke belastningsfordelingstjenesten for dokumentkonverteringer og starttjenesten for dokumentkonverteringer aktivert i Microsoft Office SharePoint Server 2007.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft SharePoint</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td><strong>Sikkerhetsproblemer i Microsoft Office-grafikkfiltre kan tillate ekstern kjøring av kode (968095)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser sju personlig rapporterte sikkerhetsproblemer i Microsoft Office. Sikkerhetsproblemene kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget bildefil via Microsoft Office. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Exchange Server kan føre til tjenestenekt (2407132)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Exchange Server. Sikkerhetsproblemet kan føre til tjenestenekt hvis en godkjent angriper sender en spesiallaget nettverksmelding til en datamaskin som kjører Exchange-tjenesten. Gode fremgangsmåter for brannmurer og vanlige standard brannmurkonfigurasjoner kan beskytte nettverk mot angrep fra andre steder enn innenfor virksomheten. Gode fremgangsmåter anbefaler at systemer som er knyttet til Internett, bør eksponere så få porter som mulig.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Moderat</a><br />
Tjenestenekt</td>
<td>Kan kreve omstart</td>
<td>Microsoft Exchange</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført i synkende rekkefølge etter utnyttelsesvurderingsnivå og deretter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan bruker jeg denne tabellen?**

Bruk denne tabellen til å få mer informasjon om sannsynligheten for at fungerende skadelig kode blir utgitt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Du bør se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

<table>
<thead>
<tr class="header">
<th>Bulletin-ID</th>
<th>Tittel på sikkerhetsproblem</th>
<th>CVE-ID</th>
<th>Utnyttelsesindeksvurdering</th>
<th>Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Sikkerhetsproblem med heap-feil i forbindelse med størrelsesverdi i pubconv.dll</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2569">CVE-2010-2569</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Sikkerhetsproblem med heap-overløp i pubconv.dll</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2570">CVE-2010-2570</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206689">MS10-097</a></td>
<td>Sikkerhetsproblem med usikker bibliotekslasting i veiviseren for registrering av Internett-tilkobling</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3144">CVE-2010-3144</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206738">MS10-096</a></td>
<td>Sikkerhetsproblem med usikker bibliotekinnlasting</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3147">CVE-2010-3147</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203463">MS10-092</a></td>
<td>Sikkerhetsproblem med oppgaveplanlegger</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3338">CVE-2010-3338</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes på Internett</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Sikkerhetsproblem i HTML-objektforekomst kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3340">CVE-2010-3340</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Sikkerhetsproblem i HTML-objektforekomst kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3343">CVE-2010-3343</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Sikkerhetsproblem med HTML-element som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3345">CVE-2010-3345</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Sikkerhetsproblem med HTML-element som kan føre til minnefeil</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3346">CVE-2010-3346</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Sikkerhetsproblem med bufferoverflyt i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3939">CVE-2010-3939</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>&quot;Double Free&quot;-sikkerhetsproblem i Win32k PFE-peker</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3940">CVE-2010-3940</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Sikkerhetsproblem med markørkobling i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3943">CVE-2010-3943</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Sikkerhetsproblem med minnefeil i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3944">CVE-2010-3944</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>Sikkerhetsproblem med bufferoverflyt i FlashPix-bildekonvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3951">CVE-2010-3951</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td>&quot;Double Free&quot;-sikkerhetsproblem i OpenType-skrift</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3957">CVE-2010-3957</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td>Sikkerhetsproblem i OpenType CMAP-tabell</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3959">CVE-2010-3959</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204906">MS10-100</a></td>
<td>Sikkerhetsproblem falsk representasjon i samtykkebrukergrensesnitt</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3961">CVE-2010-3961</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206495">MS10-090</a></td>
<td>Sikkerhetsproblem med feil i ikke-initialisert minne</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3962">CVE-2010-3962</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet utnyttes for øyeblikket på Internett</strong></td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206365">MS10-099</a></td>
<td>Sikkerhetsproblem med bufferoverflyt i kjerne-NDProxy</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3963">CVE-2010-3963</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206469">MS10-104</a></td>
<td>Sikkerhetsproblem med feil utformet forespørsel i forbindelse med kjøring av kode</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3964">CVE-2010-3964</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206699">MS10-094</a></td>
<td>Sikkerhetsproblem med usikker bibliotekinnlasting</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3965">CVE-2010-3965</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206683">MS10-095</a></td>
<td>BranchCache-sikkerhetsproblem med usikker bibliotekinnlasting</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3966">CVE-2010-3966</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=206698">MS10-093</a></td>
<td>Sikkerhetsproblem med usikker bibliotekinnlasting</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3967">CVE-2010-3967</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>1</strong></a> – Konsekvent skadelig kode er sannsynlig</td>
<td><strong>Dette sikkerhetsproblemet er publisert</strong></td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Sikkerhetsproblem med minnefeil på grunn av ugyldig indeks i datatabell i Pubconv.dll</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2571">CVE-2010-2571</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>&quot;Double Free&quot;-sikkerhetsproblem i Win32k</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3941">CVE-2010-3941</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204869">MS10-098</a></td>
<td>Sikkerhetsproblem i Win32k WriteAV</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3942">CVE-2010-3942</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>Sikkerhetsproblem med bufferoverflyt i CGM-bildekonvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3945">CVE-2010-3945</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>Sikkerhetsproblem med heltallsoverflyt i PICT-bildekonvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3946">CVE-2010-3946</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>Sikkerhetsproblem med heap-overflyt i TIFF-bildekonvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3947">CVE-2010-3947</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>Sikkerhetsproblem med bufferoverflyt i TIFF-bildekonvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3949">CVE-2010-3949</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>Sikkerhetsproblem med minnefeil i TIFF-bildekonvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3950">CVE-2010-3950</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=147425">MS10-105</a></td>
<td>Sikkerhetsproblem med heap-feil i FlashPix-bildekonvertering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3952">CVE-2010-3952</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Sikkerhetsproblem med minnefeil i forbindelse med datatabellindeksering</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3955">CVE-2010-3955</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=203895">MS10-091</a></td>
<td>Sikerhetsproblem med OpenType-skriftindeks</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3956">CVE-2010-3956</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=201319">MS10-101</a></td>
<td>Sikkerhetsproblem med null-dereferensiering for DOS i Netlogon RPC</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-2742">CVE-2010-2742</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette sikkerhetsproblemet kan bare forårsake tjenestenekt</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=204624">MS10-106</a></td>
<td>Sikkerhetsproblem med uendelig løkke i Exchange Server</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3937">CVE-2010-3937</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette sikkerhetsproblemet kan bare forårsake tjenestenekt</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=198156">MS10-103</a></td>
<td>Sikkerhetsproblem med feil i Microsoft Publisher-minne</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3954">CVE-2010-3954</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=205309">MS10-102</a></td>
<td>Sikkerhetsproblem med Hyper-V VMBus</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-3960">CVE-2010-3960</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>3</strong></a> – Fungerende skadelig kode er usannsynlig</td>
<td>Dette sikkerhetsproblemet kan bare forårsake tjenestenekt</td>
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
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="14">Windows XP</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6031d98a-cd0f-4dd8-80b6-70a7167e9e55">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=922a0835-7f69-4e37-a9f7-c64e976e3513">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a55b8029-9499-4219-99b7-65c30b0b864a">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cdef3358-ad3e-40a6-9ba5-3be220a56a65">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1">Windows Media Encoder 9 x86</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46baa431-126c-4fa5-9a7b-525008e2817d">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fa9a1aac-b9c5-4d4e-9083-a080ad4ccc6f">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bb9d1657-5beb-4372-b74c-a612a6fff5a8">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4d0ae558-a4f2-4048-b5fd-ba072ca35e48">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5d3a5678-77f8-4ebc-8775-aedd25ef0eb8">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a7c826b0-4aac-41ce-b297-6b6e11105c14">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d5207bf5-7e58-4001-aa8f-f9a4b2c037d8">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=070fef8e-ba09-40f4-abaa-9cebf08983c3">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d">Windows Media Encoder 9 x86</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75">Windows Media Encoder 9 x64</a><br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b9ce9d62-2eaa-48d8-bb6d-ea137e63d077">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6dabc306-c858-46b1-815c-cd8d011ff62e">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f277ae4-4f85-4c8a-bfc5-dcdc8afed133">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=238bb885-eae6-464a-bb3d-679025f1cb50">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="14">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f1f41fb-368a-42e6-8d17-fca83b64f57b">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3b57d26-5551-4785-86cf-41b532d78979">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4f5a3677-0990-4702-bf08-af64cf12cb6c">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b70334c-490d-446c-988a-a88a75595fd4">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef0ada2c-965f-438f-a1d3-bd45db8460c1">Windows Media Encoder 9 x86</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0b2837c-019b-419b-954d-5bdc71a3a332">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8fa2cfa4-a01d-4910-b69f-736aeb585bab">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa39f59-2177-459f-9b8a-9543330d48ec">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c87af292-a068-4089-aab8-115c18b4b024">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad843b97-2f6e-4406-a17a-627b7db8a926">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a9f56a0-230a-4dde-94da-f051ebf51f47">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b0d2a3a-7fed-4d48-9ec5-8558000e51bb">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e134e5d-84fb-432b-99b1-593b1be5d5a4">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=08328e82-b012-4ea5-bf89-becb4881084f">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dc777e61-e1e3-43bf-a84d-22c4a69c135d">Windows Media Encoder 9 x86</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=550957c2-ce66-439f-95ea-681237513f75">Windows Media Encoder 9 x64</a><br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4c5cb600-9a39-40a0-be42-1593b1e0b97d">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=17b0b340-73b2-42a7-9d86-1297c63dcc2b">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bca61d61-d5cf-49a4-ab99-b61e50e8f619">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e17b8878-d065-49cc-bdba-0f24cdf35ea3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b0a06e7-0ae5-41f4-9ff5-d524fc0afbfa">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c1cf126-604c-4f70-bbe8-aa4d145eb68f">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96884bfa-00c8-4263-9936-d7c054919dd3">Internet Explorer 7</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=15588d6a-f576-4e3d-95e8-d422af8a94de">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9abc8270-f3ac-474d-9ebc-410aaa6262cc">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=04a178cc-1afd-4e47-8cab-05e402e5a568">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4fce129d-2b4e-4a66-af27-bbbde1e65ba1">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ad896d80-167f-4e8f-a448-cac93516f4d0">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7c0c2850-e81d-4347-aeb3-47036caa7c1b">Windows Server 2003 med SP2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="14">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=897351de-9697-4954-aa7e-169e980b932c">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bebf0df0-5ebe-44b4-9ace-b3085a993e58">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2ddb8a06-c9cc-4d33-b6d1-22dbda2d871f">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=48f10251-34d8-4149-b4b2-bf3ec28f5846">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55141a02-3ad3-4691-98b9-80dd8ecb14c5">Movie Maker 2.6</a>
                    [1]
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8a57950-43cd-486f-bd97-70b0ad360a0b">Windows Media Encoder 9 x86</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1c7f1b5-e054-4cd6-857d-2ab0a2fe9f62">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b824d3b9-2ce1-4abc-ae06-68aef1250be9">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85265a23-5094-4007-8d33-f402cabd1664">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=171c02f9-f7d2-42f2-ba31-4c819a43784a">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=837b6056-af04-4aed-8afe-cc392770a590">Internet Explorer 8</a><br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a245f3c-ffb6-4ccd-956c-e7d1231fca30">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=099ccc5f-b92f-4d06-bcb5-92e35c49f613">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b078136-a492-4a2e-939d-82799f774d82">Movie Maker 2.6</a>
                    [1]
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f98c3b96-acb5-49f1-be42-3dd44d316408">Windows Media Encoder 9 x86</a>
                    <br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1054088-f484-4f44-ba0e-5cbd21773c0c">Windows Media Encoder 9 x64</a><br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=73624b68-a69d-4517-b971-f0b7d2ccc9d6">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f4c42cfe-b7f2-4436-919e-4bd305a3439a">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63c7257a-16bf-4108-80b9-9dfe53528348">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="14">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3785f3b-64c6-46a4-8e3a-9b9448124a8f">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=98183a76-5642-4e19-b488-029eb7ed3942">Internet Explorer 8</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=87149ec2-74a8-4dea-b7e3-873558e0103e">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bdc9564a-4091-4cde-963a-239513db6c17">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a4ea028f-edfc-4237-8325-7ece11fcf437">Windows Media Encoder 9 x86</a>**<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=118f528f-bd05-49c2-a4a4-78314cd00992">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6e2f572a-4169-47f2-a872-5466997122ed">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=14e079a8-01a4-47c9-bd47-f5c9a6ca070a">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6793f75b-cdf4-42ef-a53e-a1acb5b662d1">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4b81aae5-6034-4c83-b5d2-e7e472435284">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d47b457d-e995-4a7e-9bfa-eebab9b3a729">Internet Explorer 8</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=523a47d3-771d-471a-889b-16311c276a00">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dff39bfe-0799-4912-ae22-392562178ae6">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f468d2b5-f02c-4691-9fb5-a7f69752f126">Windows Media Encoder 9 x86</a>**<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=533d91d8-0291-421e-9701-3bd86d18bc45">Windows Media Encoder 9 x64</a>**<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77e288fb-b51f-4f57-baac-1443d8fbd37b">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=09a4b646-989d-43ef-a3e8-64af8b380a14">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6baf92b7-a336-45f2-a1ba-c00c34dfb76f">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=85add876-ca5a-4a92-984e-188a72e349fc">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b8c06bbc-6e84-4cf1-89f0-c0d34cfffaed">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>*<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ddafaaf-84a0-4325-b06f-4aac7cd61274">Internet Explorer 7</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=959146ee-0e70-4e56-9012-72ed59aeb24b">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf341a35-32ea-4ff7-aca9-1a4683c100ee">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=82f71194-6f1f-4f43-8752-4bf5e5f94a93">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46522323-837e-4a74-9cf0-45f69343e776">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7a4b23d4-f68e-4d5b-8814-d9247145f164">Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="14">Windows 7</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td></tr>
                <tr><td>Windows 7 for 32-biters systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c288fe87-b113-4615-9b02-5e388bcb5241">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff590db8-4264-42ba-9e07-88d100e1c4f5">Windows 7 for 32-biters systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf85cdb6-58c7-4144-82f6-f01a6a4f9c3a">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=75591d37-2cb8-4cdf-acbb-89cd0d1a9290">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e8ad5cd-af27-4f00-9378-ad778b8ee7b3">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aa7de2e4-ba48-4d58-b034-05349f0eb920">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7c7d57a-d031-46a3-9613-eae2b9cb6401">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows 7 for x64-baserte systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2cf4ac70-88b4-4840-9895-2bcf119312a7">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4ea4e339-9db2-4b99-b567-80ee55ecdf92">Windows 7 for x64-baserte systemer</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0597018d-39f5-4ca9-b437-63d9e68f264d">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a0c4dd0-98b4-4e7a-99ed-22b9d9f76cd1">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=35a3e821-b463-411c-858b-d01eb5aed42b">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b21db627-91c2-4ebf-b7c0-38ac58ae5b6c">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e52c36f5-637b-4928-83d0-27514c6cc384">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="14">Windows Server 2008 R2</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206495">
                      <strong>MS10-090</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203895">
                      <strong>MS10-091</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=203463">
                      <strong>MS10-092</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206698">
                      <strong>MS10-093</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206699">
                      <strong>MS10-094</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206683">
                      <strong>MS10-095</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206738">
                      <strong>MS10-096</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206689">
                      <strong>MS10-097</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204869">
                      <strong>MS10-098</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206365">
                      <strong>MS10-099</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204906">
                      <strong>MS10-100</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=201319">
                      <strong>MS10-101</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=205309">
                      <strong>MS10-102</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td><td>
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
                <tr><td>Windows Server 2008 R2 for x64-baserte systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99a91ba7-035b-4717-ada5-c1ad6645db64">Internet Explorer 8</a>**<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e52f7869-474a-44c8-a102-e766c576fc01">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=28c832fb-4937-4652-8799-eab6c76d05fb">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58a765f-cea9-456d-b0ab-bfc70b109cbf">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e2c95f6-9381-4484-b11b-814ab9138118">Windows Server 2008 R2 for x64-baserte systemer</a>**<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d417ebce-7841-4bbb-8abc-b15ef5f4b733">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b823a7aa-0eb9-42dd-bf56-8907d94b314a">Windows Server 2008 R2 for x64-baserte systemer</a>**<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d7307afd-84a0-434e-9658-bf9f8ae4b938">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39b7abc7-65a4-4dfd-92ba-c638e3de1118">Windows Server 2008 R2 for x64-baserte systemer</a>*<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c26de145-94b8-404a-b946-744988fab83b">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a21d061a-794a-4012-b3cd-c67445c074f5">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Kritisk)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3ad64d5c-2d81-4ac8-934e-8917b2fcf961">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=13a9f838-ac07-43dc-9aee-a77207998e1e">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb4211f3-1082-4245-8f03-7cbac90e9a31">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7eeac1bb-9f86-4ea5-b30f-980d52be5044">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=66b2506d-80e0-4e32-86e6-0908ef56ae90">Windows Server 2008 R2 for Itanium-based Systems</a>
                    <br />(Viktig)</td><td>Ikke relevant</td><td>Ikke relevant</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene om [administrasjon av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [betjening av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene om [administrasjon av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [betjening av en Server Core-installasjon](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS10-093**

\[1\]Windows Movie Maker 2.6 er en valgfri nedlastning som kan installeres på de angitte operativsystemene.

#### Microsoft Office-serier og -programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Office-serier og -komponenter</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=198156">
                      <strong>MS10-103</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147425">
                      <strong>MS10-105</strong>
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
                  </td></tr>
                <tr><td>Microsoft Office XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f540692c-e404-4383-8937-4d6a36475da5">Microsoft Publisher 2002 Service Pack 3</a>
                    <br />(KB2284692)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=724d0ad6-ba5f-4dbf-b280-3fb36335d33b">Microsoft Office XP Service Pack 3</a>
                    [1]
                    <br />(KB2289162)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e600de65-3e9d-4e37-8906-8b7091ff523e">Microsoft Publisher 2003 Service Pack 3</a>
                    <br />(KB2284695)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=976857e9-77fc-4667-88ca-7637e57536cd">Microsoft Office 2003 Service Pack 3</a>
                    [1]
                    <br />(KB2289163)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office 2007 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79275011-bdc1-446a-8ea6-56fc31bd9c35">Microsoft Publisher 2007 Service Pack 2</a>
                    <br />(KB2284697)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=676eeed6-f2b7-4265-afc7-a82ffdbeb290">Microsoft Office 2007 Service Pack 2</a>
                    <br />(KB2288931)<br />(Ingen alvorlighetsgrad[2])</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2010 (32-biters versjoner)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99e18990-75e9-497e-9b4f-5d7ef8656ab2">Microsoft Publisher 2010 (32-biters versjoner)</a>
                    <br />(KB2409055)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6d644494-b530-4b37-bc37-8a8a7edefe53">Microsoft Office 2010 (32-biters versjoner</a>
                    <br />(KB2289078)<br />(Ingen alvorlighetsgrad[2])</td></tr>
                <tr><td>Microsoft Office 2010 (64-biters versjoner)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9b27ee11-e563-4152-9691-25eec1ee9966">Microsoft Publisher 2010 (64-biters versjoner)</a>
                    <br />(KB2409055)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=58e54779-aa8f-41b3-9993-8cec12c49082">Microsoft Office 2010 (64-biters versjoner)</a>
                    <br />(KB2289078)<br />(Ingen alvorlighetsgrad[2])</td></tr>
              
                <tr><th colspan="3">Annen Office-programvare</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=198156">
                      <strong>MS10-103</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=147425">
                      <strong>MS10-105</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Microsoft Office Converter Pack</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dcded2ee-0673-4afe-abe6-04941a2ad306">Microsoft Office Converter Pack</a>
                    <br />(KB2456849)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Works 9</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=10f6f330-05d8-4b60-9ebb-822a7321ac0f">Microsoft Works 9</a>
                    <br />(KB2431831)<br />(Viktig)</td></tr>
              </table>


**Merknader for MS10-105**

\[1\]Kunder som bruker den angitte programvaren, må også installere Microsoft Office-oppdateringen som tilbys i MS10-087, for å være beskyttet mot sikkerhetsproblemene som beskrives i MS10-105.

\[2\]Alvorlighetsgrader gjelder ikke for denne oppdateringen fordi sikkerhetsproblemene som omtales i denne bulletinen, ikke berører denne programvaren. Som et ledd i en mer dyptgående beskyttelse mot eventuelle nye vektorer som kan bli avdekket senere, anbefaler imidlertid Microsoft at kunder som bruker denne programvaren, installerer denne oppdateringen.

#### Microsoft Server-programvare

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft SharePoint Server</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206469">
                      <strong>MS10-104</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204624">
                      <strong>MS10-106</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007 Service Pack 2 (32-biters versjoner)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8fb9f9-7920-43ea-b618-e26dc3360c60">Microsoft Office SharePoint Server 2007 Service Pack 2 (32-biters versjoner)</a>
                    <br />(KB2433089)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 Service Pack 2 (64-biters versjoner)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db09280-24bd-42e0-9ae3-02c9bf3e8ee3">Microsoft Office SharePoint Server 2007 Service Pack 2 (64-biters versjoner)</a>
                    <br />(KB2433089)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Microsoft Exchange Server</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=206469">
                      <strong>MS10-104</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=204624">
                      <strong>MS10-106</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>Ingen</td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Exchange Server 2007 Service Pack 2 for x64-baserte systemer</td><td>Ikke relevant</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b983156-9e9f-4d29-9e9b-2369747e3b62">Microsoft Exchange Server 2007 Service Pack 2 for x64-baserte systemer</a>
                    <br />(KB2407132)<br />(Moderat)</td></tr>
              </table>


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

Du finner mer informasjon om hvordan du distribuerer denne sikkerhetsoppdateringen ved hjelp av Windows Server Update Services, på [Windows Server Update Services](http://go.microsoft.com/fwlink/?linkid=50120).

**SystemCenter Configuration Manager 2007**

Configuration Manager 2007 Software Update Management forenkler den komplekse oppgaven med å levere og administrere oppdateringer til IT-systemer i hele bedriften. Med Configuration Manager 2007 kan IT-administratorer levere oppdateringer av Microsoft-produkter til en rekke enheter, inkludert stasjonære datamaskiner, bærbare datamaskiner, servere og mobile enheter.

Den automatiske sikkerhetsproblemvurderingen i Configuration Manager 2007 oppdager behov for oppdateringer og rapporterer om anbefalte handlinger. Software Update Management i Configuration Manager 2007 er bygd på Microsoft Windows Software Update Services (WSUS), en tidstestet oppdateringsinfrastruktur som er velkjent for IT-administratorer over hele verden. Hvis du vil ha mer informasjon om hvordan administratorer kan bruke Configuration Manager 2007 til å distribuere oppdateringer, kan du se [Software Update Management](http://www.microsoft.com/systemcenter/en/us/configuration-manager/cm-software-update-management.aspx). Hvis du vil ha mer informasjon om Configuration Manager, kan du gå til [System Center Configuration Manager](http://www.microsoft.com/systemcenter/en/us/configuration-manager.aspx).

**Systems Management Server 2003**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne.

**Obs\!** System Management Server 2003 har ikke vanlig kundestøtte etter 12. januar 2010. Hvis du vil ha mer informasjon om produktlivssykluser, kan du gå til . Den neste utgivelsen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se den tidligere delen **SystemCenter Configuration Manager 2007**.

Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du se [Scenarios and Procedures for Microsoft Systems Management Server 2003: Software Distribution and Patch Management](http://www.microsoft.com/downloads/en/details.aspx?familyid=32f2bb4c-42f8-4b8d-844f-2553fd78049f&displaylang=en). Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server TechCenter](http://technet.microsoft.com/en-us/systemcenter/bb545936.aspx).

**Obs\!**  SMS bruker Microsoft Baseline Security Analyzer for å gi bred støtte i forbindelse med søking etter og distribusjon av sikkerhetsbulletinoppdateringer. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/en/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=en)) til å installere disse oppdateringene.

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

  - Aniway hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-090
  - Nicolas Joly hos [VUPEN Vulnerability Research Team](http://www.vupen.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-090
  - Stephen Fewer i samarbeid med [Tipping Points](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-090
  - [Peter Vreugdenhil](http://vreugdenhilresearch.nl/), i samarbeid med [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/), for rapporten om et sikkerhetsproblem som beskrives i MS10-090
  - [Yosuke Hasegawa](http://utf-8.jp/) for samarbeidet i forbindelse med et problem som beskrives i MS10-090
  - Jose Antonio Vazquez Gonzalez hos [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-090
  - Marc Schoenefeld hos [Red Hat Security Response Team](https://www.redhat.com/security/team/), i samarbeid med [Opera Security Team](http://www.opera.com/security/), for rapporten om et sikkerhetsproblem som beskrives i MS10-091
  - Marc Schoenefeld hos [Red Hat Security Response Team](https://www.redhat.com/security/team/) for rapporten om et sikkerhetsproblem som beskrives i MS10-091
  - Paul-Kenji Cahier Furuya for rapporten om et sikkerhetsproblem som beskrives i MS10-091
  - Sergey Golovanov, Alexander Gostev, Maxim Golovkin og Alexey Monastyrsky hos [Kaspersky Lab](http://usa.kaspersky.com/) og Vitaly Kiktenko og Alexander Saprykin hos [Design and Test Lab](http://www.dnt-lab.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-092
  - Liam O Morchu hos [Symantec](http://www.symantec.com/index.jsp) for rapporten om et sikkerhetsproblem som beskrives i MS10-092
  - Alexandr Matrosov, Eugene Rodionov, Juraj Malcho og David Harley hos [ESET](http://www.eset.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-092
  - Haifei Li hos [Fortinet’s FortiGuard Labs](http://www.fortiguard.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-095
  - Simon Raner hos [ACROS Security](http://www.acrossecurity.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-096
  - HD Moore hos [Rapid7](http://www.rapid7.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-096
  - Muhaimin Dzulfakar hos [NGS Software](http://www.ngssoftware.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-096
  - Muhaimin Dzulfakar hos [NGS Software](http://www.ngssoftware.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-097
  - Tarjei Mandt hos [Norman](http://www.norman.com/) for rapporten om fire sikkerhetsproblemer som beskrives i MS10-098
  - Stéfan Le Berre hos [Sysdream](http://www.sysdream.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-098
  - Honggang Ren hos [Fortinet's FortiGuard Labs](http://www.fortiguard.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-099
  - Cesar Cerrudo hos [Argeniss](http://www.argeniss.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-100
  - Matthias Dieter Wallnöfer og Andrew Bartlett hos The Samba Team for rapporten om et sikkerhetsproblem som beskrives i MS10-101
  - [HP](http://www.hp.com/) og [techit](http://www.techit.de/) for rapporten om et sikkerhetsproblem som beskrives i MS10-102
  - Chaouki Bekrar hos [VUPEN Vulnerability Research Team](http://www.vupen.com/) for rapporten om fem sikkerhetsproblemer som beskrives i MS10-103
  - Oleksandr Mirosh i samarbeid med [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-104
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS10-105
  - Alin Rad Pop hos [Secunia Research](http://secunia.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-105
  - Carsten Eiram hos [Secunia Research](http://secunia.com/) for rapporten om tre sikkerhetsproblemer som beskrives i MS10-105
  - Dyon Balding hos [Secunia Research](http://secunia.com/) for rapporten om to sikkerhetsproblemer som beskrives i MS10-105
  - Oleksandr Mirosh i samarbeid med [TippingPoints](http://www.tippingpoint.com/) [Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-106

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (14. desember 2010): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (15. desember 2010): Informasjon om at kunder med Microsoft Office XP og Microsoft Office 2003 må ta i bruk oppdateringen i MS10-087 for å være beskyttet mot sikkerhetsproblemene som beskrives i MS10-105.

*Built at 2014-04-18T01:50:00Z-07:00*

