---
title: Sammendrag av Microsofts sikkerhetsbulletiner for juni 2011
TOCTitle: MS11-JUN
ms:assetid: ms11-jun
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms11-jun(v=Security.10)
ms:contentKeyID: 61315230
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for juni 2011

Publisert: 14. juni 2011 | Oppdatert: 18. januar 2012

**Versjon:** 3.1

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i juni 2011.

I forbindelse med utgivelsen av sikkerhetsbulletinene for juni 2011 erstatter dette sammendraget av bulletiner forhåndsvarslingen for bulletiner som ble utstedt 9. juni 2011. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://go.microsoft.com/fwlink/?linkid=217213).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 15. juni 2011 kl. 11.00 stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for juni på webcast](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?culture=en-us&eventid=1032455073&eventcategory=4). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://go.microsoft.com/fwlink/?linkid=217214).

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212284">MS11-038</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem ved OLE-automatisering som kan tillate ekstern kjøring av kode (2476490)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows OLE-automatisering (Object Linking and Embedding). Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker besøker et webområde som inneholder et spesiallaget WMF-bilde (Windows-metafil). En angriper kan imidlertid aldri tvinge brukere til å besøke et slikt webområde. Angriperen må derfor i stedet forsøke å overtale brukere til å besøke det skadelige webområdet, vanligvis ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212287">MS11-039</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i .NET Framework og Microsoft Silverlight kan tillate ekstern kjøring av kode (2514842)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft .NET Framework og Microsoft Silverlight. Sikkerhetsproblemet kan tillate ekstern kjøring av kode på et klientsystem hvis en bruker viser en spesiallaget webside ved hjelp av en webleser som kan kjøre XAML-leserprogrammer (XBAPer) eller Silverlight-programmer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Sikkerhetsproblemet kan videre tillate ekstern kjøring av kode på et serversystem som kjører IIS, hvis den serveren tillater behandling av ASP.NET-sider og en angriper lykkes i å laste opp en spesiallaget ASP.NET-side til den serveren og deretter kjører siden, slik det kan være tilfelle i et webvertscenario. Dette sikkerhetsproblemet kan også brukes av Windows .NET-programmer til å omgå kodetilgangssikkerhetsrestriksjoner (CAS).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217470">MS11-040</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Threat Management Gateway-brannmurklient kan tillate ekstern kjøring av kode (2520426)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Forefront Threat Management Gateway (TMG) 2010-klienten, tidligere kjent som Microsoft Threat Management Gateway-brannmurklienten. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper får en klientdatamaskin til å sende bestemte forespørsler på et system der TMG-brannmurklienten brukes.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Forefront Threat Management Gateway</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217499">MS11-041</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Windows-kjernemodusdrivere kan tillate ekstern kjøring av kode (2525694)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker besøker en delt nettverksressurs (eller besøker et webområde som viser til en delt nettverksressurs) som inneholder en spesiallaget OpenType-skrift (OTF). En angriper kan imidlertid aldri tvinge brukere til å besøke slike webområder eller delte nettverksressurser. Angriperen må derfor i stedet forsøke å overtale brukere til å besøke de skadelige webområdene eller delte nettverksressursene, vanligvis ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Distributed File System kan tillate ekstern kjøring av kode (2535512)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser to personlig rapporterte sikkerhetsproblemer i Microsoft Distributed File System (DFS). Det mest alvorlige av disse sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en angriper sender et spesiallaget DFS-svar på en DFS-forespørsel fra en klient. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan kjøre vilkårlig kode og få full kontroll over det berørte systemet. Gode fremgangsmåter for brannmurer og vanlige standard brannmurkonfigurasjoner kan beskytte nettverk mot angrep fra andre steder enn innenfor virksomheten. Gode fremgangsmåter anbefaler at systemer som er knyttet til Internett, bør eksponere så få porter som mulig.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215841">MS11-043</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i SMB-klienten kan tillate ekstern kjøring av kode (2536276)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en angriper sender et spesiallaget SMB-svar på en SMB-forespørsel fra en klient. En angriper må overbevise brukeren om å starte en SMB-tilkobling til en spesiallaget SMB-server for å kunne utnytte dette sikkerhetsproblemet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=216436">MS11-044</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i .NET Framework kan tillate ekstern kjøring av kode (2538814)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem i Microsoft .NET Framework. Sikkerhetsproblemet kan tillate ekstern kjøring av kode på et klientsystem hvis en bruker viser en spesiallaget webside ved hjelp av en webleser som kan kjøre XAML-leserprogrammer (XBAPer). Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Sikkerhetsproblemet kan videre tillate ekstern kjøring av kode på et serversystem som kjører IIS, hvis den serveren tillater behandling av ASP.NET-sider og en angriper lykkes i å laste opp en spesiallaget ASP.NET-side til den serveren og deretter kjører siden, slik det kan være tilfelle i et webvertscenario. Dette sikkerhetsproblemet kan også brukes av Windows .NET-programmer til å omgå kodetilgangssikkerhetsrestriksjoner (CAS).</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;"><strong>Kumulativ sikkerhetsoppdatering for Internet Explorer (2530548)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser elleve personlig rapporterte sikkerhetsproblemer i Internet Explorer. De alvorligste sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside ved hjelp av Internet Explorer. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=218115">MS11-052</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Vector Markup Language kan tillate ekstern kjøring av kode (2544521)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsofts VML-implementering (Vector Markup Language). Denne sikkerhetsoppdateringen har alvorlighetsgraden Kritisk for Internet Explorer 6, Internet Explorer 7 og Internet Explorer 8 på Windows-klienter. For Internet Explorer 6, Internet Explorer 7 og Internet Explorer 8 på Windows-servere har den alvorlighetsgraden Moderat. Internet Explorer 9 er ikke berørt av dette sikkerhetsproblemet.<br />
<br />
Dette sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217912">MS11-037</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i MHTML kan tillate tilgjengeliggjøring av informasjon (2544893)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i MHTML-protokollbehandleren i Microsoft Windows. Sikkerhetsproblemet kan føre til tilgjengeliggjøring av informasjon hvis en bruker åpner en spesiallaget URL-adresse fra en angripers webområde. Angriperen må overbevise brukeren om å besøke webområdet, vanligvis ved å få vedkommende til å klikke en kobling i en e-postmelding eller direktemelding.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tilgjengeliggjøring av informasjon</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblemer i Microsoft Excel kan tillate ekstern kjøring av kode (2537146)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser åtte personlig rapporterte sikkerhetsproblemer i Microsoft Office. Sikkerhetsproblemene kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget Excel-fil. En angriper som klarer å utnytte noen av disse sikkerhetsproblemene, kan oppnå samme brukerrettigheter som den påloggede brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter. Hvis filvalidering i Office (OFV) installeres og konfigureres for å hindre at mistenkelige filer åpnes, blokkeres angrepsvektorene for utnyttelse av sikkerhetsproblemene som beskrives i CVE-2011-1272, CVE-2011-1273 og CVE-2011-1279. Microsoft Excel 2010 berøres bare av CVE-2011-1273, som beskrevet i denne bulletinen. Den automatiske Microsoft Fix It-løsningen for å deaktivere redigering i beskyttet visning for Excel 2010, tilgjengelig i Microsoft Knowledge Base-artikkel 2501584, blokkerer angrepsvektorene for utnyttelse av CVE-2011-1273.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Ekstern kjøring av kode</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217464">MS11-046</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i tilleggsfunksjonsdriver kan tillate rettighetsutvidelse (2503665)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et offentliggjort sikkerhetsproblem i Microsofts tilleggsfunksjonsdriver (AFD). Sikkerhetsproblemet kan tillate rettighetsutvidelse hvis en angriper logger seg på en brukers system og deretter kjører et spesiallaget program. En angriper må ha gyldig påloggingsinformasjon og må kunne logge seg på lokalt for å kunne utnytte dette sikkerhetsproblemet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217468">MS11-047</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Hyper-V kan føre til tjenestenekt (2525835)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Windows Server 2008 Hyper-V og Windows Server 2008 R2 Hyper-V. Dette sikkerhetsproblemet kan føre til tjenestenekt hvis en spesiallaget pakke sendes til VMBus av en godkjent bruker i en av de virtuelle gjestemaskinene som Hyper-V-serveren er vert for. En angriper må ha gyldig påloggingsinformasjon og må kunne sende spesiallaget innhold fra en virtuell gjestemaskin for å kunne utnytte dette sikkerhetsproblemet. Sikkerhetsproblemet kan ikke utnyttes eksternt eller av anonyme brukere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215840">MS11-048</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i SMB kan føre til tjenestenekt (2536275)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows. Sikkerhetsproblemet kan føre til tjenestenekt hvis en angriper oppretter en spesiallaget SMB-pakke og deretter sender pakken til et berørt system. Gode sikkerhetsrutiner for brannmurer og vanlige standard brannmurkonfigurasjoner kan beskytte nettverk mot angrep fra andre steder enn innenfor virksomheten som forsøker å utnytte dette sikkerhetsproblemet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tjenestenekt</td>
<td style="border:1px solid black;">Krever omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217077">MS11-049</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i Microsoft XML-redigering kan tillate tilgjengeliggjøring av informasjon (2543893)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft XML-redigering. Sikkerhetsproblemet kan tillate tilgjengeliggjøring av informasjon hvis en bruker åpner en spesiallaget Web Service Discovery-fil (*.disco) inne i et av programmene som er oppført i denne bulletinen. Legg merke til at dette sikkerhetsproblemet ikke gjør det mulig for en angriper å kjøre kode eller å utvide egne brukerrettigheter direkte, men at det kan brukes til å fremskaffe informasjon som kan brukes til å forsøke å skade det berørte systemet ytterligere.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Tilgjengeliggjøring av informasjon</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft SQL Server,<br />
Microsoft Visual Studio</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217101">MS11-051</a></td>
<td style="border:1px solid black;"><strong>Sikkerhetsproblem i webregistreringen for Active Directory Certificate Services kan tillate rettighetsutvidelse (2518295)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i webregistreringen for Active Directory Certificate Services. Sikkerhetsproblemet er et skripting-på-tvers-av-områder-sikkerhetsproblem (XSS) som kan føre til rettighetsutvidelse, slik at en angriper kan utstede vilkårlige kommandoer på området i omgivelsene til målbrukeren. En angriper må sende en spesiallaget kobling til en bruker og overtale vedkommende til å klikke den for å lykkes med å utnytte dette sikkerhetsproblemet. En angriper kan imidlertid aldri tvinge brukere til å besøke dette webområdet. Angriperen må derfor i stedet forsøke å overtale brukere til å besøke webområdet, vanligvis ved å få dem til å klikke en kobling i en e-postmelding eller direktemelding som viderekobler brukeren til det skadelige webområdet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a><br />
Rettighetsutvidelse</td>
<td style="border:1px solid black;">Kan kreve omstart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

Følgende tabell gir en utnyttelsesvurdering av hvert av sikkerhetsproblemene som løses denne måneden. Sikkerhetsproblemene er oppført etter bulletin-ID og deretter etter CVE-ID. Det er bare sikkerhetsproblemer med en alvorlighetsgrad på Kritisk eller Viktig som er inkludert.

**Hvordan bruker jeg denne tabellen?**  

Bruk denne tabellen til å få mer informasjon om sannsynligheten for angrep i form av kjøring av kode og tjenestenekt innen 30 dager etter at sikkerhetsbulletinen utgis, for hver av sikkerhetsoppdateringene som du kanskje må installere. Se gjennom hver av vurderingene nedenfor, i henhold til din bestemte konfigurasjon, for å prioritere distribusjonen av denne månedens oppdateringer. Hvis du vil ha mer informasjon om hva disse vurderingene betyr, kan du se [Microsoft Exploitability Index](http://technet.microsoft.com/en-us/security/cc998259.aspx).

I kolonnene nedenfor refererer "ny programvareversjon" til den aktuelle programvaren, og "eldre programvareversjoner" refererer til alle eldre, støttede versjoner av den aktuelle programvaren, slik de er oppført i tabellene Berørt programvare eller Uberørt programvare i bulletinen.

<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;">Bulletin-ID</th>
<th style="border:1px solid black;">Tittel på sikkerhetsproblem</th>
<th style="border:1px solid black;">CVE-ID</th>
<th style="border:1px solid black;">Vurdering av utnyttelsesgrad for kjøring av kode i ny programvareversjon</th>
<th style="border:1px solid black;">Vurdering av utnyttelsesgrad for kjøring av kode i eldre programvareversjoner</th>
<th style="border:1px solid black;">Vurdering av utnyttelsesgrad for tjenestenekt</th>
<th style="border:1px solid black;">Viktige merknader</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217912">MS11-037</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med MHTML Mime-formatert forespørsel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1894">CVE-2011-1894</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemet er publisert.<br />
<br />
Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212284">MS11-038</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i OLE-automatisering som kan føre til bufferunderflyt</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0658">CVE-2011-0658</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=212287">MS11-039</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i .NET Framework som kan føre til matriseforskyvning</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-0664">CVE-2011-0664</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217470">MS11-040</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i TMG-brannmurklienten som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1889">CVE-2011-1889</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217499">MS11-041</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med OTF-validering i Win32k</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1873">CVE-2011-1873</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med minnefeil i DFS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1868">CVE-2011-1868</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215838">MS11-042</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med DFS-svar på henvisning</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1869">CVE-2011-1869</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215841">MS11-043</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med analysering av svar i SMB</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1268">CVE-2011-1268</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=216436">MS11-044</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med JIT-optimalisering i .NET Framework</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1271">CVE-2011-1271</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemet er publisert.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med utilstrekkelig validering av poster i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1272">CVE-2011-1272</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med analyse av poster i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1273">CVE-2011-1273</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med matrisetilgang utenfor område i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1274">CVE-2011-1274</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med Heap-overskriving av minne i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1275">CVE-2011-1275</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med bufferoverløp i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1276">CVE-2011-1276</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Excel som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1277">CVE-2011-1277</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med WriteAV i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1278">CVE-2011-1278</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217502">MS11-045</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med WriteAV utenfor område i Excel</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1279">CVE-2011-1279</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217464">MS11-046</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med rettighetsutvidelse i tilleggsfunksjonsdriver</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1249">CVE-2011-1249</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">Dette sikkerhetsproblemet er publisert.<br />
<br />
Dette er et sikkerhetsproblem som omfatter rettighetsutvidelse</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217468">MS11-047</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med permanent VMBus DoS</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1872">CVE-2011-1872</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=215840">MS11-048</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med analysering av forespørsel i SMB</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1267">CVE-2011-1267</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Permanent</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan forårsake tjenestenekt</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217077">MS11-049</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med oppløsning i XML på eksterne enheter</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1280">CVE-2011-1280</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med koblingsegenskaper som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1250">CVE-2011-1250</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem ved DOM-manipulering som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1251">CVE-2011-1251</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med toStaticHTML som kan føre til tilgjengeliggjøring av informasjon</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1252">CVE-2011-1252</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">3</a> – Fungerende skadelig kode er usannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som kan føre til tilgjengeliggjøring av informasjon</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med dra-og-slipp som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1254">CVE-2011-1254</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med tidselement som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1255">CVE-2011-1255</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem ved DOM-endring som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1256">CVE-2011-1256</a></td>
<td style="border:1px solid black;">Ikke berørt</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med oppsett som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1260">CVE-2011-1260</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med markeringsobjekt som kan føre til minnefeil</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1261">CVE-2011-1261</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217212">MS11-050</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med omadressering som kan føre til minnefeil i HTTP</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1262">CVE-2011-1262</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2</a> – Inkonsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=217101">MS11-051</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem i Active Directory Certificate Services</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1264">CVE-2011-1264</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Ikke relevant</td>
<td style="border:1px solid black;">Dette er et sikkerhetsproblem som omfatter rettighetsutvidelse</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=218115">MS11-052</a></td>
<td style="border:1px solid black;">Sikkerhetsproblem med minnefeil i VML</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2011-1266">CVE-2011-1266</a></td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1</a> – Konsekvent skadelig kode er sannsynlig</td>
<td style="border:1px solid black;">Midlertidig</td>
<td style="border:1px solid black;">(Ingen)</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

Følgende tabeller viser bulletinene etter store programvarekategorier og alvorlighetsgrad.

**Hvordan bruker jeg disse tabellene?**  

Bruk disse tabellene til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det kommer noen sikkerhetsoppdateringer som angår installasjonen din. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for ett enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

**Tabell 1**

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="8" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2371079f-fb20-4fd5-999e-e73f3701818c">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3.5</a>
                    <br />(KB2478656)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=67a25abd-f43c-4b01-b507-a109b739238f">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=492310d3-bbb4-4fff-b5fe-3470c17e7681">Windows XP Service Pack 3</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ingen alvorlighetsgrad[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=26ec66af-9727-4423-90da-012ed5b30856">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4203a59a-a809-45db-a234-fef0ff5063f9">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4a49ec89-2a8f-41d9-8f0b-ee57fdf21f50">Internet Explorer 8</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b53d6631-4ded-48f5-a503-925b89b322b2">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3.5</a>
                    <br />(KB2478656)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=035d5115-54b6-41d3-b9f0-890041ead178">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=af6b7627-c462-45fe-8948-70da37e60659">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e10a4c3c-2ef8-4cfc-ac9b-4d97bfa79ac1">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ingen alvorlighetsgrad[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f6e05fef-ee8c-44ff-a106-d7b8659c8d91">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9fc734db-a177-43d2-a74a-b1fe6ea6f779">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e4e18a4-97dc-4c5e-a078-8466913aa29e">Internet Explorer 8</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7e6ff410-4552-4687-81ab-83d9c91f8af5">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3.5</a>
                    <br />(KB2478656)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3aa8f1bc-07de-451a-8244-1733247e6f2e">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2719e0fb-3cfd-47b2-906d-3e07b0e3c978">Windows Server 2003 Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ingen alvorlighetsgrad[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=638f6dd6-bea0-4356-b23a-45e865a6b28b">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3bd0012-4a45-4f96-8a51-3ff1f85d1e37">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19557984-5088-44cc-b5ba-9bab33df8e7e">Internet Explorer 8</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9c1a539f-1472-4394-8354-bd549d8332e0">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3.5</a>
                    <br />(KB2478656)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4aa8c003-0353-4a5b-8aea-c01a103af393">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e9018258-5a72-47a1-8584-3d1aa52317c3">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c962531e-f580-4195-989b-cf348cc96fa7">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ingen alvorlighetsgrad[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce616970-343d-49f1-994d-4269b9a11448">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=70ece3b4-e5bb-469c-bfef-c8310681f5a7">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c92d94c5-5e8f-45aa-a24a-f4d0efd93732">Internet Explorer 8</a><br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 SP2 for Itanium-baserte systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c194dd35-b9db-44a5-a252-38f9f803802f">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=686e5192-63e4-410e-b653-2cfddd5b409f">Microsoft .NET Framework 3.5</a>
                    <br />(KB2478656)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3db8a718-4441-4e1a-889f-abcc4bde1125">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478658)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e07b5fa-c9fa-495b-9352-c07ce46a7e8b">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96309c49-4822-4c47-b364-2ba65327cac5">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ea18a916-03cf-4eac-bacc-ceb006491f24">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 2.0 Service Pack 2</a>
                    <br />(KB2518864)<br />(Ingen alvorlighetsgrad[2])<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c7e115a1-486b-4a2b-a7d6-42c4018fc02d">Microsoft .NET Framework 3.5</a><br />(KB2530095)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=960f8920-906b-48a8-8700-94f09babc628">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518864)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f58ebc9e-00e1-413c-8076-d7a44003d0c7">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80231a27-b37c-4101-a34f-19a26a040836">Internet Explorer 7</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f33c9e54-c2e5-498d-a798-5bbfe9e4249c">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB2478657)<br />(Kritisk)<br /><br />Bare Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478659)<br />(Kritisk)<br /><br />Bare Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478660)<br />(Kritisk)<br /><br />Windows Vista Service Pack 1 og Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=aded8f20-479d-40c1-9560-c0581c6f77a2">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a62edfd8-9016-4bb5-bf48-885498fa0042">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB2518863)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518865)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a><br />(KB2518863)<br />(Kritisk)<br /><br />Bare Windows Vista Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518865)<br />(Kritisk)<br /><br />Bare Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518866)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518866)<br />(Kritisk)<br /><br />Windows Vista Service Pack 1 og Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fea735a8-032b-4fa6-8337-1fa411df0b88">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4cddfc68-eff6-4587-8607-63307d039489">Internet Explorer 8</a><br />(Kritisk)<br /><br />Bare Windows Vista Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=392316fc-f531-469c-aa60-4ecf061a5354">Internet Explorer 9</a><br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4566528f-62ee-4d78-b3af-131a7cc15e1f">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB2478657)<br />(Kritisk)<br /><br />Bare Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478659)<br />(Kritisk)<br /><br />Bare Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478660)<br />(Kritisk)<br /><br />Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a519a5d7-bfe3-4e53-99e9-d85f7e34237f">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=962cb40c-680c-4c37-98d4-ca9789ca7270">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb561ba6-af4d-40cc-947c-923f9cca9a7e">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB2518863)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518865)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a><br />(KB2518863)<br />(Kritisk)<br /><br />Bare Windows Vista x64 Edition Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518865)<br />(Kritisk)<br /><br />Bare Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518866)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518866)<br />(Kritisk)<br /><br />Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=49dcb47b-3c79-4f69-ba07-f471304c16e2">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e0a8fbac-2c31-4cf8-9967-6171edabd560">Internet Explorer 8</a><br />(Kritisk)<br /><br />Bare Windows Vista x64 Edition Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44b2aa73-c318-47ac-ad87-0d24afd9cdd7">Internet Explorer 9</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0c9614d9-6f61-463d-b1fa-bd5eb2c1a5c5">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB2478657)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478659)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for 32-biters systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478660)<br />(Kritisk)<br /><br />Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ebfa067-0236-4454-8605-df1b99742f90">*</a><br />(Viktig)</td><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8ab9679e-6a69-4ca3-9210-7ca4fb1980c2">*</a><br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a>**<br />(KB2518863)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Server 2008 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518865)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Server 2008 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a>**<br />(KB2518863)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518865)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for 32-biters systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518866)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for 32-biters systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518866)<br />(Kritisk)<br /><br />Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b6547ff0-b059-495d-8816-bb094ac11be7">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9650c47-ac52-433d-b409-ce1cfe8d3e87">Internet Explorer 8</a>**<br />(Kritisk)<br /><br />Bare Windows Server 2008 for 32-biters systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7f9b1ba2-8247-494b-990c-f62003188c5a">Internet Explorer 9</a>**<br />(Kritisk)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=36698775-0e4e-4980-ae4c-43542de424ca">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a>**<br />(KB2478657)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478659)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for x64-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2478660)<br />(Kritisk)<br /><br />Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd8f3713-b408-4db6-aecd-7eed2176a715">*</a><br />(Kritisk)</td><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f1d76b82-9996-4d08-894b-9c16a4b3bb1e">*</a><br />(Viktig)</td><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22c63fc3-2c5a-4e50-9026-2e04a6e74210">*</a><br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a>**<br />(KB2518863)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Server 2008 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518865)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Server 2008 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a>**<br />(KB2518863)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518865)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for x64-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a>**<br />(KB2518866)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for x64-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a>**<br />(KB2518866)<br />(Kritisk)<br /><br />Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>**[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=feff3364-4bfd-45f5-99da-9192b47ef5d4">Internet Explorer 7</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7dff9f08-19cb-41dd-a315-84c1dac81510">Internet Explorer 8</a>**<br />(Kritisk)<br /><br />Bare Windows Server 2008 for x64-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fdf88a52-c099-44eb-95a0-650129c0e678">Internet Explorer 9</a>**<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3edb613f-5bf0-4e28-9835-4afbb6ef0e01">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2eabacce-394f-4b9a-8306-0875ca19a3a9">Microsoft .NET Framework 2.0 Service Pack 1 og Microsoft .NET Framework 3.5</a><br />(KB2478657)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=55fd3254-7e59-4cf9-afa8-45ae66bc7390">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478659)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=afa11dda-a543-42a7-b997-5292fd869a8b">Microsoft .NET Framework 2.0 Service Pack 2 og Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2478660)<br />(Kritisk)<br /><br />Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5a61f888-c81e-4b8a-8932-2fe67df4b2ad">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f80c89c6-27ab-4f6a-afad-9c8e92cbbce4">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5bb889de-8ff6-4587-8ef9-ffb13e8d60fd">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 2.0 Service Pack 1</a><br />(KB2518863)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518865)<br />(Ingen alvorlighetsgrad[2])<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7092fe-079d-4175-b8b7-412f259ff7e4">Microsoft .NET Framework 3.5</a><br />(KB2518863)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80423e37-0a54-413d-b44a-41c68c2030b8">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518865)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 2.0 Service Pack 2</a><br />(KB2518866)<br />(Kritisk)<br /><br />Bare Windows Server 2008 for Itanium-baserte systemer Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e3ca981-5565-41a8-ab5e-941c92e74c7d">Microsoft .NET Framework 3.5 Service Pack 1</a><br />(KB2518866)<br />(Kritisk)<br /><br />Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d81a9219-da95-4fbf-af7f-898f553b0572">Internet Explorer 7</a>
                    <br />(Kritisk)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50ae36ff-2406-48a4-97cc-12782b6d30ac">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows 7 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a><br />(KB2478661)<br />(Kritisk)<br /><br />Windows 7 for 32-biters systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a><br />(KB2478662)<br />(Kritisk)<br /><br />Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9de1bf5d-6f25-496d-bc44-a32c5e8920fe">Windows 7 for 32-biters systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19a15098-1754-4536-a9ca-ff07d16464b7">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows 7 for 32-biters systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a><br />(KB2518867)<br />(Kritisk)<br /><br />Windows 7 for 32-biters systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a><br />(KB2518869)<br />(Kritisk)<br /><br />Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=91b98f02-a09e-48f1-9f78-a949f7268542">Internet Explorer 8</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=79f846da-3b17-43c9-9016-a055c2c56975">Internet Explorer 9</a><br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1241f0f8-a5c7-420a-a5b7-b6c3caa9e5e2">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows 7 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a><br />(KB2478661)<br />(Kritisk)<br /><br />Windows 7 for x64-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a><br />(KB2478662)<br />(Kritisk)<br /><br />Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7f52b13-5b3d-438c-ae14-86da50c8b67a">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=50d1c677-57aa-4e3f-bdfc-6f01b5d3bfe2">Windows 7 for x64-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b449f23e-b3df-46e5-bfe3-98268d20ad54">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows 7 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a><br />(KB2518867)<br />(Kritisk)<br /><br />Windows 7 for x64-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a><br />(KB2518869)<br />(Kritisk)<br /><br />Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=264107cc-68b4-401c-82f7-de64b535c18d">Internet Explorer 8</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e87a09f2-b755-48ef-9b85-fc78d0bfce43">Internet Explorer 9</a><br />(Kritisk)</td></tr>
              
                <tr><th colspan="8" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212284">
                      <strong>MS11-038</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217499">
                      <strong>MS11-041</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215838">
                      <strong>MS11-042</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215841">
                      <strong>MS11-043</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=216436">
                      <strong>MS11-044</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217212">
                      <strong>MS11-050</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8181c359-cd79-438a-87be-093b363d0b04">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>**<br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 R2 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a>*<br />(KB2478661)<br />(Kritisk) <br /><br />Bare Windows Server 2008 R2 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a>*<br />(KB2478662)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>*[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b77e5be6-d3eb-4e3a-9be2-831578f0447c">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Kritisk)</td><td style="border:1px solid black;">Windows Server 2008 R2 for x64-baserte systemer<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9d66b1e7-dbf9-4475-a973-49fb85557eca">*</a><br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=06008192-3cac-477b-a913-83eed39d8718">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Kritisk)</td><td style="border:1px solid black;">Bare Windows Server 2008 R2 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a>*<br />(KB2518867)<br />(Kritisk) <br /><br />Bare Windows Server 2008 R2 for x64-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a>*<br />(KB2518869)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for x64-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>*[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8b18e6f9-96b8-4dec-bcd0-d71f1bac3eb0">Internet Explorer 8</a>**<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=81814b15-ebdf-4817-932b-5ea7a37fa6ed">Internet Explorer 9</a>**<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6b63a1eb-445a-4cd3-b357-9a1dd82d7a35">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Windows Server 2008 R2 bare for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9720a317-ca4c-4a47-b99c-2c66301e62c6">Microsoft .NET Framework 3.5.1</a><br />(KB2478661)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c8152a18-0367-4c00-a3c7-669325a899f4">Microsoft .NET Framework 3.5.1</a><br />(KB2478662)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c72635e4-c733-4fa1-9db0-75de6ead9e1c">Microsoft .NET Framework 4.0</a>[1]<br />(KB2478663)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c00a33bc-c874-4693-b0f7-5034c5df9424">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c8455f1-b8a0-4ba2-84a2-043d25ef75c5">Windows Server 2008 R2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=93a32bd9-7e67-4ace-8c45-116f91b032f9">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">Windows Server 2008 R2 bare for Itanium-baserte systemer: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=bff13134-ed84-4370-beb4-340c340a5d98">Microsoft .NET Framework 3.5.1</a><br />(KB2518867)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer bare med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dab623bf-d23d-42a9-9e74-ae75d779b980">Microsoft .NET Framework 3.5.1</a><br />(KB2518869)<br />(Kritisk)<br /><br />Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1: <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f7afba05-974f-48f8-b600-9e131ceb7951">Microsoft .NET Framework 4.0</a>[1]<br />(KB2518870)<br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ab2406a8-06f7-4f88-9af4-dc136d64bc35">Internet Explorer 8</a>
                    <br />(Kritisk)</td></tr>
              </table>


**Merknader for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknader for MS11-039**

\[1\] **.NET Framework 4.0 og .NET Framework 4.0 Client Profile er berørt.** Omdistribuerbare pakker for .NET Framework versjon 4 er tilgjengelig i to profiler: .NET Framework 4.0 og .NET Framework 4.0 Client Profile. .NET Framework 4.0 Client Profile er en del av .NET Framework 4.0. Sikkerhetsproblemet som løses i denne oppdateringen, berører både .NET Framework 4.0 og .NET Framework 4.0 Client Profile. Hvis du vil ha mer informasjon, kan du se MSDN-artikkelen om å [installere .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

**Merknader for MS11-044**

\[1\] **.NET Framework 4.0 og .NET Framework 4.0 Client Profile er berørt.** Omdistribuerbare pakker for .NET Framework versjon 4 er tilgjengelig i to profiler: .NET Framework 4.0 og .NET Framework 4.0 Client Profile. .NET Framework 4.0 Client Profile er en del av .NET Framework 4.0. Sikkerhetsproblemet som løses i denne oppdateringen, berører både .NET Framework 4.0 og .NET Framework 4.0 Client Profile. Hvis du vil ha mer informasjon, kan du se MSDN-artikkelen om å [installere .NET Framework](http://msdn.microsoft.com/en-us/library/5a4x27ek.aspx).

\[2\]Alvorlighetsgrader gjelder ikke for denne oppdateringen fordi sikkerhetsproblemet som omtales i denne bulletinen, ikke påvirker denne programvaren. Som et ledd i en mer dyptgående beskyttelse mot eventuelle nye vektorer som kan bli avdekket senere, anbefaler imidlertid Microsoft at kunder som bruker denne programvaren, installerer denne oppdateringen.

**Tabell 2**

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="7" style="border:1px solid black;">Windows XP</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows XP Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c760c7f-94f1-437f-a645-fd33b50d03f4">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0b88f9e9-3439-44e5-92c8-66a3c97cb03d">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=03b45ad8-cc6b-473b-8112-bd513ed97f5d">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ce5bc2d7-9438-4bf0-be5e-be9dd00c3286">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a1db7736-f3e4-45df-af1d-52746978a0a8">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows XP Professional x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c94c0d17-fdbe-41b3-a23d-98f43f907b89">Internet Explorer 6</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ff955dc3-58ca-40ea-b7f1-9ff40c37f997">Internet Explorer 7</a><br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed502ece-737e-44cb-84fd-8a0d1bc321c8">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7b211b02-a005-46a3-ad1d-d4baaeec8289">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=71497891-41a2-476d-b524-4eb5cecb9639">Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows Server 2003</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5dafb455-969e-4be9-8735-d4ee0682d22f">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ba3beb80-a921-489e-a6ff-a7b2d665ada6">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a8038325-0d14-445b-a5d9-ce7ac1fa44b5">Internet Explorer 8</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6427ea5d-05d0-4367-805c-9cb305802b3c">Windows Server 2003 Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c614cb8b-223e-4f84-b94c-f15747760aa5">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ef90d6c1-ea7f-4c32-9c90-0303e04c7436">Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2003 x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e78829d0-8215-4e56-8959-ebd3bc8e9a91">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3bec943e-5758-4439-a947-a8fafd30edec">Internet Explorer 7</a><br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f7bcbad-f647-4fbb-88d4-b19c54db6f00">Internet Explorer 8</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e7f65891-32c0-4817-b3b2-d8be73145df9">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a951087-25c5-4f5c-8407-a1585491ae0b">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=62944095-33d6-4131-be32-a79d9ec4d4a9">Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2003 SP2 for Itanium-baserte systemer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1e822515-9f0a-4ef0-bb70-d4889d200f47">Internet Explorer 6</a>
                    <br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=47a0fdc6-7576-4c32-b8fd-cbb05d57599d">Internet Explorer 7</a><br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ca8b1d09-9f80-417b-99b1-8f86e86e1f11">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd48b93b-24fa-45a3-91fb-9f9f9418c49f">Windows Server 2003 SP2 for Itanium-baserte systemer</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e541f1bb-c9bf-4dc8-96ec-58a3de5ba7fd">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd059690-52b0-4b37-9fbb-d9906ae46fed">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ebea38a7-1fbe-4141-a529-52d7a7326d6a">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b69e3bda-940b-4524-a724-0af4ae0ec719">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f0007c3-8d11-4940-8766-1112e3777aae">Windows Vista Service Pack 1 og Windows Vista Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6c7d7162-ef19-49f4-a8fc-5db7415445a4">Internet Explorer 7</a>
                    <br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=256bb26f-df9e-4259-881b-e8313a9fafa8">Internet Explorer 8</a><br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=54833350-a385-4a31-995a-9ddc38798c21">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e3a26bc5-1757-4b38-9cae-419c919f4877">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fadf6f12-1f09-4d49-93b1-8fce01400b4f">Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4446121a-0aab-4fbc-ba74-68d7650e8bca">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ed089de4-c9ec-4ac7-a711-5f7cb29c05bc">Internet Explorer 8</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a3bbd67-94db-40b2-8786-cb39a493ec92">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e34e4cf9-cdae-4240-8574-950c0be00822">*</a><br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=8960dd62-7cf7-41cb-97b2-b082bd1750aa">*</a><br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=46ade106-e0cb-4c71-8230-793a15062823">Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</a>**<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=01399fc7-dc2b-461e-a1a5-751a3b61bde0">Internet Explorer 7</a>**<br />(Moderat)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dd32b7c6-daa1-47aa-807f-25a678790cf2">Internet Explorer 8</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4cb870f3-9878-4075-b8fd-2ee90c8e3bc8">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Lav)</td><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a3604f05-26b2-451b-9153-0e718158371e">*</a><br />(Viktig)</td><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=24789423-72b7-48d1-bdc1-f0e5174d99bb">*</a><br />(Viktig)</td><td style="border:1px solid black;">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2<a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0abc6908-ac6a-4da3-843a-af6841ccc1db">*</a><br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6141a1c5-ecaf-4553-9d27-dd6e5c4a13fd">Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</a>**<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=16a8b78a-3979-4cc7-bbe5-6d962aa64336">Internet Explorer 7</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e1243011-00e6-49f2-a676-c04cb805d36a">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8a82b44-e1d8-45f8-b8b8-b1f74e1efce0">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=057f1356-9c70-4457-a1df-69334fdab467">Windows Server 2008 for Itanium-baserte systemer og Windows Server 2008 for Itanium-baserte systemer med Service Pack 2</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows 7</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27e767d8-84e3-434f-bb8d-3b2303774ad0">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c3647646-658a-423b-b0cb-bba7613b67e7">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=63d8b801-5178-474b-a21e-72a0ce501d3e">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cf9e5ecd-68f7-4982-b4ed-be80859b757c">Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=747ba56a-0d47-4946-99a4-bae1f11ea748">Internet Explorer 8</a>
                    <br />(Kritisk)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7996511d-4b8e-49c3-a0fa-4da907a6c947">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cd7d3cb9-cb60-4b62-b0df-a38fe21802e9">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2707650a-604c-4044-acc4-07a30b5640d8">Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="7" style="border:1px solid black;">Windows Server 2008 R2</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=218115">
                      <strong>MS11-052</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217912">
                      <strong>MS11-037</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217464">
                      <strong>MS11-046</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217468">
                      <strong>MS11-047</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=215840">
                      <strong>MS11-048</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217101">
                      <strong>MS11-051</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Moderat</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cff7f53d-0fd6-48f8-a9d6-bf19e0a32905">Internet Explorer 8</a>**<br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=40354f73-4f4d-4a4a-abac-f8a3d4c3ae5f">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>**<br />(Lav)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e67c73ca-d0f9-40c1-8b6e-25b1b13caa3a">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=c9c6c36d-a455-42f7-b7d4-9fb9824c07cb">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f9824310-772d-4e1e-980e-11e2db3ac53e">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>*<br />(Viktig)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1da04414-6210-43ea-8e0a-cf21cf144076">Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer Service Pack 1</a>**<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4dd2c0f4-b29c-4648-a123-83d3ae6a878f">Internet Explorer 8</a>
                    <br />(Moderat)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=22853823-8f63-4258-8991-1ad50e58a0d9">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Lav)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72d1d6b6-e8bd-492b-b65a-82060beef441">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0533d293-e186-4d39-a925-ab3d9ed46290">Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1</a>
                    <br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Merknad for Windows Server 2008 og Windows Server 2008 R2**

**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

#### Microsoft Office-serier og -programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office-serier og -komponenter</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office XP Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=853c0663-94f7-4634-98ad-47ca4b1f7b1e">Microsoft Excel 2002 Service Pack 3</a>
                    <br />(KB2541003)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2003 Service Pack 3</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f38f183a-9c64-406b-9bf6-807cb2d55e56">Microsoft Excel 2003 Service Pack 3</a>
                    <br />(KB2541025)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2007 Service Pack 2</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5b271f87-a279-419f-9437-ded224fa19f1">Microsoft Excel 2007 Service Pack 2</a>
                    [1]
                    <br />(KB2541007)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2010 (32-biters versjoner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=baba7ec1-4a5e-4e13-9d0e-9085a39a0554">Microsoft Excel 2010 (32-biters versjoner)</a>
                    <br />(KB2523021)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2010 (64-biters versjoner)</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d6e9f422-43b0-4da5-8356-c38482e8eebb">Microsoft Excel 2010 (64-biters versjoner)</a>
                    <br />(KB2523021)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Office for Mac</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office 2004 for Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d12d0868-4f28-4c0a-ab61-338878064b70">Microsoft Office 2004 for Mac</a>
                    <br />(KB2555786)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Office 2008 for Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9e2d348b-c753-4eab-838c-370cd5af5e14">Microsoft Office 2008 for Mac</a>
                    <br />(KB2555785)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office for Mac 2011</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3c58555c-1eba-42fe-a10f-b30af9031e44">Microsoft Office for Mac 2011</a>
                    <br />(KB2555784)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">Open XML File Format Converter for Mac</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6118d5f5-b6fd-4584-be25-209534772379">Open XML File Format Converter for Mac</a>
                    <br />(KB2555787)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft InfoPath</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office InfoPath 2007 Service Pack 2</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=88eedb0b-a2cf-4a1b-b1b9-0b2926c25872">Microsoft Office InfoPath 2007 Service Pack 2</a>
                    <br />(KB2510061)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft InfoPath 2010 (32-bitersversjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90ffe910-bd9c-48aa-8007-2b43e1a99999">Microsoft InfoPath 2010 (32-bitersversjoner)</a>
                    <br />(KB2510065)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft InfoPath 2010 (64-bitersversjoner)</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f3244003-fb63-44d8-bedc-6399c39aacba">Microsoft InfoPath 2010 (64-bitersversjoner)</a>
                    <br />(KB2510065)<br />(Viktig)</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Annen Office-programvare</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217502">
                      <strong>MS11-045</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Excel Viewer</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=77c1e7e2-207f-46fd-81f2-43a25eddc010">Microsoft Excel Viewer Service Pack 2</a>
                    <br />(KB2541015)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3512a033-871d-49ec-a8d2-1b9c7dec4936">Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007</a>
                    <br />(KB2541012)<br />(Viktig)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              </table>


**Merknad for MS11-045**

\[1\]For Microsoft Office Excel 2007 Service Pack 2 må kunder i tillegg til sikkerhetsoppdateringspakken KB2541007 også installere sikkerhetsoppdateringen for Microsoft Office Compatibility Pack Service Pack 2 for filformater for Word, Excel og PowerPoint 2007 (KB2541012) for å være beskyttet mot sikkerhetsproblemene beskrevet i denne bulletinen.

**Merknad for MS11-049**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Microsoft Server-programvare

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="" style="border:1px solid black;">Microsoft SQL Server</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 Service Pack 3</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 Service Pack 3</a><br />(KB2494113)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 Service Pack 3</a><br />(KB2494112)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 x64 Edition Service Pack 3</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 x64 Edition Service Pack 3</a><br />(KB2494113)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 x64 Edition Service Pack 3</a><br />(KB2494112)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 for Itanium-baserte systemer Service Pack 3</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 for Itanium-baserte systemer Service Pack 3</a><br />(KB2494113)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 for Itanium-baserte systemer Service Pack 3</a><br />(KB2494112)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 Service Pack 4</a><br />(KB2494120)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 Service Pack 4</a><br />(KB2494123)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 x64 Edition Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 x64 Edition Service Pack 4</a><br />(KB2494120)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 x64 Edition Service Pack 4</a><br />(KB2494123)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 for Itanium-baserte systemer Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 for Itanium-baserte systemer Service Pack 4</a><br />(KB2494120)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 for Itanium-baserte systemer Service Pack 4</a><br />(KB2494123)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 Express Edition Service Pack 3</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 Express Edition Service Pack 3</a><br />(KB2494113)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 Express Edition Service Pack 3</a><br />(KB2494112)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 Express Edition Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 Express Edition Service Pack 4</a><br />(KB2494120)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 Express Edition Service Pack 4</a><br />(KB2494123)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2005 Express Edition med Advanced Services Service Pack 3</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=faca7f7a-c346-48e3-9bf5-f140a51aae4e">SQL Server 2005 Express Edition med Advanced Services Service Pack 3</a><br />(KB2494113)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d214763c-5a16-4959-90ff-08112345d867">SQL Server 2005 Express Edition med Advanced Services Service Pack 3</a><br />(KB2494112)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2005 Express Edition med Advanced Services Service Pack 4</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2aba4a2e-477f-4267-9ebe-ab7b29d218ad">SQL Server 2005 Express Edition med Advanced Services Service Pack 4</a><br />(KB2494120)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2975ad1a-1852-4771-b3fa-2be79899be57">SQL Server 2005 Express Edition med Advanced Services Service Pack 4</a><br />(KB2494123)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server Management Studio Express (SSMSE) 2005</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161">SQL Server Management Studio Express (SSMSE) 2005</a><br />(KB2546869)<br />(Viktig)<br /><br />QFE-oppdatering:<br />Ikke relevant</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server Management Studio Express (SSMSE) 2005 x64 Edition</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=34c3ba21-b158-4e6d-82ba-831053d41161">SQL Server Management Studio Express (SSMSE) 2005 x64 Edition</a><br />(KB2546869)<br />(Viktig)<br /><br />QFE-oppdatering:<br />Ikke relevant</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2008 for 32-biters systemer med Service Pack 1</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c">SQL Server 2008 for 32-biters systemer med Service Pack 1</a>[1]<br />(KB2494096)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c">SQL Server 2008 for 32-biters systemer med Service Pack 1</a>[1]<br />(KB2494100)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2008 R2 for x64-baserte systemer med Service Pack 1</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c">SQL Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>[1]<br />(KB2494096)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c">SQL Server 2008 R2 for x64-baserte systemer med Service Pack 1</a>[1]<br />(KB2494100)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2008 for Itanium-baserte systemer Service Pack 1</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=ae7db514-d96b-4cff-a13d-c74f4cf8cf0c">SQL Server 2008 for Itanium-baserte systemer Service Pack 1</a><br />(KB2494096)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=312a39c4-cb32-4216-8672-1b1c0937ba6c">SQL Server 2008 for Itanium-baserte systemer Service Pack 1</a><br />(KB2494100)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2008 for 32-biters systemer med Service Pack 2</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276">SQL Server 2008 for 32-biters systemer med Service Pack 2</a>[1]<br />(KB2494089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91">SQL Server 2008 for 32-biters systemer med Service Pack 2</a>[1]<br />(KB2494094)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2008 for x64-baserte systemer med Service Pack 2</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276">SQL Server 2008 for x64-baserte systemer med Service Pack 2</a>[1]<br />(KB2494089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91">SQL Server 2008 for x64-baserte systemer med Service Pack 2</a>[1]<br />(KB2494094)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2008 for Itanium-baserte systemer Service Pack 2</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f4767bf-257d-4822-b768-7b6702261276">SQL Server 2008 for Itanium-baserte systemer Service Pack 2</a><br />(KB2494089)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23240963-e2c6-4d40-8179-661117b53e91">SQL Server 2008 for Itanium-baserte systemer Service Pack 2</a><br />(KB2494094)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2008 R2 for 32-biters systemer</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41">SQL Server 2008 R2 for 32-biters systemer</a>[1]<br />(KB2494088)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4">SQL Server 2008 R2 for 32-biters systemer</a>[1]<br />(KB2494086)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">SQL Server 2008 R2 for x64-baserte systemer</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41">SQL Server 2008 R2 for x64-baserte systemer</a>[1]<br />(KB2494088)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4">SQL Server 2008 R2 for x64-baserte systemer</a>[1]<br />(KB2494086)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">SQL Server 2008 R2 for Itanium-baserte systemer</td><td style="border:1px solid black;">GDR-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=80e98567-1b28-49b1-a646-579f8c115a41">SQL Server 2008 R2 for Itanium-baserte systemer  </a><br />(KB2494088)<br />(Viktig)<br /><br />QFE-oppdatering:<br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9df95137-d1b3-4fac-8958-8042aa2010c4">SQL Server 2008 R2 for Itanium-baserte systemer  </a><br />(KB2494086)<br />(Viktig)</td></tr>
              </table>


**Merknad** **er** **for MS11-049**

\[1\]Denne oppdateringen gjelder også tilsvarende Express og Express med Advanced Services-versjoner.

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Utviklerverktøy og programvare fra Microsoft

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Silverlight</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td><td style="border:1px solid black;">Ingen</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Silverlight 4 </td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8">Microsoft Silverlight 4</a> når installert på Mac<br />(KB2512827)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8">Microsoft Silverlight 4</a> når installert på alle versjoner av Microsoft Windows-klienter<br />(KB2512827)<br />(Kritisk)<br /><br /><a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2f71b104-b66f-4146-9d70-fcde766c91b8">Microsoft Silverlight 4</a> når installert på alle versjoner av Microsoft Windows-servere**<br />(KB2512827)<br />(Kritisk)</td><td style="border:1px solid black;">Ikke relevant</td></tr>
              
                <tr><th colspan="3" style="border:1px solid black;">Microsoft Visual Studio</th></tr>
              
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=212287">
                      <strong>MS11-039</strong>
                    </a>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217077">
                      <strong>MS11-049</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">Ingen</td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual Studio 2005 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e5ce8a9a-e89b-4095-9f21-7e6f307fbf2b">Microsoft Visual Studio 2005 Service Pack 1</a>
                    <br />(KB2251481)<br />(Viktig)</td></tr>
                <tr><td style="border:1px solid black;">Microsoft Visual Studio 2008 Service Pack 1</td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cc01bce9-3f38-4590-9c6e-a4048c886d33">Microsoft Visual Studio 2008 Service Pack 1</a>
                    <br />(KB2251487)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">Microsoft Visual Studio 2010 </td><td style="border:1px solid black;">Ikke relevant</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=213b820f-dcba-4895-b339-b50eeb92524d">Microsoft Visual Studio 2010</a>
                    <br />(KB2251489)<br />(Viktig)</td></tr>
              </table>


**Merknader for MS11-039**

**\*\*Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Hvis du vil ha mer informasjon om dette installasjonsalternativet, kan du se TechNet-artiklene [Managing a Server Core Installation](http://technet.microsoft.com/en-us/library/ee441255\(ws.10\).aspx) og [Servicing a Server Core Installation](http://technet.microsoft.com/en-us/library/ff698994\(ws.10\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon i [Compare Server Core Installation Options](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

**Merknad for MS11-049**

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Sikkerhetsprogramvare fra Microsoft

<table style="border:1px solid black;" class="dataTable">
  <tr class="thead">
    <th style="border:1px solid black;"></th>
    <th style="border:1px solid black;"></th>
  </tr>
                <tr><th colspan="" style="border:1px solid black;">Microsoft Forefront</th></tr>
              
                <tr><td style="border:1px solid black;">
                    <strong>Bulletinidentifikator</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=217470">
                      <strong>MS11-040</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td style="border:1px solid black;">
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td style="border:1px solid black;">
                    <a runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td style="border:1px solid black;">Microsoft Forefront Threat Management Gateway 2010-klient</td><td style="border:1px solid black;">
                    <a runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d1c85acd-a6df-4634-9cd4-c562ad92097e">Microsoft Forefront Threat Management Gateway 2010-klient</a>
                    <br />(Kritisk)</td></tr>
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

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

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

  - Billy Rios og Eduardo Vela Nava hos [Google Security Team](http://www.google.com/) for samarbeidet om endringer i MS11-037
  - Yamata Li hos [Palo Alto Networks](http://www.paloaltonetworks.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-038
  - Michael J. Liu for rapporten om et sikkerhetsproblem som beskrives i MS11-039
  - Koro hos [www.korosoft.net](http://www.korosoft.net/) for rapporten om et sikkerhetsproblem som beskrives i MS11-041
  - Laurent Gaffié hos [NGS Software](http://www.ngssoftware.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-042
  - Dan Kaminsky for samarbeidet i forbindelse med et sikkerhetsproblem som beskrives i MS11-044
  - Bing Liu hos [Fortinets FortiGuard Labs](http://www.fortiguard.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-045.
  - En anonym forsker i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-045
  - Omair i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-045
  - En anonym forsker i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-045
  - Nicolas Gregoire hos [Agarri](http://www.agarri.fr/) i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-045
  - Omair for rapporten om et sikkerhetsproblem som beskrives i MS11-045
  - Will Dormann hos [CERT/CC](http://www.cert.org/) for rapporten om to sikkerhetsproblemer som beskrives i MS11-045
  - Steven Adair hos [Shadowserver Foundation](http://www.shadowserver.org) og Chris S. for rapporten om et sikkerhetsproblem som beskrives i MS11-046
  - Nicolas Economou hos [Core Security Technologies](http://www.coresecurity.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-047
  - Jesse Ou hos [Cigital](http://www.cigital.com) for rapporten om et sikkerhetsproblem som beskrives i MS11-049
  - Robert Swiecki hos [Google Inc.](http://www.google.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - [NSFOCUS Security Team](http://www.nsfocus.com/) for rapporten om et problem som beskrives i MS11-050
  - En anonym forsker i samarbeid med [Beyond Securitys SecuriTeam Secure Disclosure](http://www.beyondsecurity.com/ssd.html)-program for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - Adi Cohen hos [IBM Rational Application Security](http://blog.watchfire.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - [Trend Micro](http://www.trendmicro.com/) for samarbeidet i forbindelse med et problem som beskrives i MS11-050
  - Nirmal Singh Bhary hos [Norman](http://www.norman.com) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - En anonym forsker i samarbeid med [VeriSign iDefense Labs](http://labs.idefense.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - Damian Put i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - Yoel Gluck, Yogesh Badwe og Varun Badhwar i produktsikkerhetsteamet hos [salesforce.com](http://www.salesforce.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - Jose Antonio Vazquez Gonzalez i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - Peter Winter-Smith i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-050
  - Stephen Fewer hos [Harmony Security](http://www.harmonysecurity.com/) i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for samarbeidet med oss i forbindelse med forandringer i dybdeforsvar som omhandles i MS11-050
  - Ruggero Strabla og [eMaze](http://www.emaze.net/) Networks' [Saipem Security Team](http://www.saipem.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-051
  - En anonym forsker i samarbeid med [TippingPoints](http://www.tippingpoint.com/)[Zero Day Initiative](http://www.zerodayinitiative.com/) for rapporten om et sikkerhetsproblem som beskrives i MS11-052

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (14. juni 2011): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (14. juni 2011): For MS11-042, fjernet Windows 7 for 32-biters systemer Service Pack 1, Windows 7 for x64-baserte systemer Service Pack 1, Windows Server 2008 R2 for x64-baserte systemer Service Pack 1 og Windows Server 2008 R2 for Itanium-baserte systemer Service Pack 1 fra avsnittet **Berørt programvare og nedlastingssteder**. Dette er bare en informasjonsendring. Det var ingen endringer i filer for sikkerhetsoppdateringen eller søkelogikken.
  - V2.0 (9. august 2011): Publiserte MS11-043 på nytt for å tilby oppdateringen på nytt for alle støttede operativsystemer for å løse et stabilitetsproblem. Kunder som allerede har oppdatert systemene sine, bør installere MS11-043 på nytt. I tillegg er MS11-049 publisert på nytt for å kunngjøre en gjenkjenningsendring for oppdateringen av Microsoft Visual Studio 2005 Service Pack 1 som legger til gjenkjenning av beslektet programvare. Det er ingen endringer av sikkerhetsoppdateringsfilene i MS11-049. Kunder som allerede har oppdatert systemene sine, trenger ikke å installere MS11-049 på nytt.
  - V2.1 (26. oktober 2011): For MS11-039 og MS11-044 er brukbarheten for Server Core-installasjon endret for .NET Framework 4 på Windows Server 2008 R2 for x64-baserte systemer.
  - V3.0 (8. november 2011): MS11-037 publisert på nytt for å tilby oppdateringen på nytt for alle støttede versjoner av Windows og Windows Server 2003. Kunder som bruker Windows XP eller Windows Server 2003, inkludert kunder som allerede har installert oppdateringen som opprinnelig ble tilbudt 14. juni 2011, bør installere oppdateringen som tilbys på nytt.
  - V3.1 (18. januar 2012): For MS11-049 er det lagt til en merknad i delen Berørt programvare og nedlastingssteder for å redegjøre for at denne oppdateringen også gjelder 32-biters og x64-baserte versjoner av SQL Server 2008 og SQL Server 2008 R2 Express og Express Advanced-versjoner.

*Built at 2014-04-18T01:50:00Z-07:00*

