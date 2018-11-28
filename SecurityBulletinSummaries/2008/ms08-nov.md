---
title: Sammendrag av Microsofts sikkerhetsbulletiner for november 2008
TOCTitle: MS08-NOV
ms:assetid: ms08-nov
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms08-nov(v=Security.10)
ms:contentKeyID: 61315197
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for november 2008

Publisert: 11. november 2008 | Oppdatert: 12. juli 2011

**Versjon:** 4.0

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i november 2008.

I forbindelse med utgivelsen av bulletinene for november 2008 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 6. november 2008. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 12. november 2008 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for november på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374642). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (1)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-069</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128803"><strong>Sikkerhetsproblemer i Microsoft XML Core Services kan tillate ekstern kjøring av kode (955218)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser flere sikkerhetsproblemer i Microsoft XML Core Services. Det mest alvorlige sikkerhetsproblemet kan tillate ekstern kjøring av kode hvis en bruker åpner en spesiallaget webside via Internet Explorer. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig (1)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-068</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=133434"><strong>Sikkerhetsproblem i SMB kan tillate ekstern kjøring av kode (957097)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne sikkerhetsoppdateringen løser et publisert sikkerhetsproblem i protokollen for Microsoft-servermeldingsblokken (SMB). Sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode på berørte systemer. En angriper som utnytter dette sikkerhetsproblemet, kan installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
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
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Microsoft Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Utnyttelsesindeks

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=133434">MS08-068</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=133434">Sikkerhetsproblem i SMB kan tillate ekstern kjøring av kode (957097)</a></td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4037">CVE-2008-4037</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td>Skadelig kode er offentliggjort for dette sikkerhetsproblemet på Windows XP.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128803">MS08-069</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128803">Sikkerhetsproblemer i Microsoft XML Core Services kan tillate ekstern kjøring av kode (955218)</a></td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4029">CVE-2008-4029</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">1 – Konsekvent skadelig kode er sannsynlig</a></td>
<td>Skadelig kode for tilgjengeliggjøring av informasjon er sannsynlig ettersom dette kan brukes i angrep på tvers av domener.</td>
</tr>
<tr class="odd">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128803">MS08-069</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128803">Sikkerhetsproblemer i Microsoft XML Core Services kan tillate ekstern kjøring av kode (955218)</a></td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-0099">CVE-2007-0099</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td>Dette sikkerhetsproblemet involverer en kappløpssituasjon ved innlasting av XML-filer. Derfor er det vanskelig å utnytte sikkerhetsproblemet konsekvent.</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=128803">MS08-069</a></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=128803">Sikkerhetsproblemer i Microsoft XML Core Services kan tillate ekstern kjøring av kode (955218)</a></td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4033">CVE-2008-4033</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx">2 – Inkonsekvent skadelig kode er sannsynlig</a></td>
<td></td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

**Hvordan bruker jeg denne tabellen?**

Bruk tabellen til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det finnes nødvendige sikkerhetsoppdateringer. Hvis programvare eller en komponent står oppført, finnes en hyperkobling til den tilgjengelige programvareoppdateringen, og alvorlighetsgraden av programvareoppdateringen er også oppført.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

#### Operativsystemer og komponenter for Windows

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="3">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133434">
                      <strong>MS08-068</strong>
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
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=559cd4b6-24b7-4e60-8749-37d9b833d3eb">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44c971e6-96fc-4bba-8f4a-f9d46bda2b6c">Microsoft Windows 2000 Service Pack 4</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="3">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133434">
                      <strong>MS08-068</strong>
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
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c">Windows XP Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td>Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.http//www.microsoft.com/downloads/details.aspx?familyid=6ed1a087-97e2-4283-9b53-b7b046654d08">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7493fa37-2cbf-4d66-8690-d50d63da4096">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6f8ae0aa-fd68-4156-9016-bba00149793c">Windows XP Service Pack 3</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1b79f220-ebfc-49c1-963b-58bbda21b6e7">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9501b33b-d639-43e7-ad5a-9e76ed66effd">Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="3">Windows Server 2003</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133434">
                      <strong>MS08-068</strong>
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
                  </td></tr>
                <tr><td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a0f8385-e908-4b5f-b9bf-80b7dabfcafd">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Lav)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=57a0606d-ea7a-4e5b-8b8b-7b77a444ef75">Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=347c8c83-4269-4a0e-af6f-4be2e824d22b">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Lav)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=915e001f-9aa0-4fb0-9c2a-0f0c72b4f056">Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</a>
                    <br />(Viktig)</td></tr>
                <tr><td>Windows Server 2003 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=3a65e1cd-eb4e-44b6-8868-a5a84be2cb32">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Lav)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=59914795-60c7-4ebe-828d-f28cb457e6e3">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6abf7ba9-825f-4ee2-a2fe-6b1cd9fab622">Windows Server 2003 med SP1 for Itanium-based Systems og Windows Server 2003 med SP2 for Itanium based Systems</a>
                    <br />(Viktig)</td></tr>
              
                <tr><th colspan="3">Windows Vista</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133434">
                      <strong>MS08-068</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Vista og Windows Vista Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=affbc957-1867-4bbe-924d-6f0696ae0895">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cb6c4315-8c6d-43af-978b-b190b1a1577a">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5612815f-8685-45d2-af4a-164c298a0869">Windows Vista og Windows Vista Service Pack 1</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>
                    <br />(KB954430)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b01a5f31-8c57-4c5c-909e-b37caf0439b0">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Viktig)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=39443046-2093-4c87-ac7b-679deab96414">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Viktig)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=727ce9b6-827f-4350-b4ff-c08e8ac541a6">Windows Vista x64 Edition og Windows Vista x64 Edition Service Pack 1</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>
                    <br />(KB954430)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Windows Server 2008</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133434">
                      <strong>MS08-068</strong>
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
                      <strong>Moderat</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for 32-biters systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=90a04164-4d02-4ce9-b3d8-bddb1ec27618">Microsoft XML Core Services 3.0</a>**<br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>**<br />(KB954430)<br />(Lav)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=dea9f227-967f-47c7-bb2a-ed68f13645d9">Microsoft XML Core Services 6.0</a>**<br />(KB954459)<br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b305e894-61ec-46b4-91ee-4c9ac59bc47e">Windows Server 2008 for 32-biters systemer</a>*<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 for 32-biters Systems Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>**<br />(KB954430)<br />(Lav)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-baserte systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b7bfe3f4-835f-402c-95b5-6d49b6935308">Microsoft XML Core Services 3.0</a>**<br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>**<br />(KB954430)<br />(Lav)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f16e2a5f-37fd-4ee1-aef0-597214323dc4">Microsoft XML Core Services 6.0</a>**<br />(KB954459)<br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e8d26dfd-b347-4f10-b5b6-27dfff5e4f47">Windows Server 2008 for x64-baserte systemer</a>*<br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 for x64-basert Systems Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>**<br />(KB954430)<br />(Lav)</td><td>Ikke relevant</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=4e0d1efe-70ac-459b-b330-c0149b74f520">Microsoft XML Core Services 3.0</a>
                    <br />(KB955069)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a><br />(KB954430)<br />(Lav)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d4ae74e2-1b09-4a99-8cf5-8a8ca8ac6f7f">Microsoft XML Core Services 6.0</a><br />(KB954459)<br />(Lav)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=d565467d-e10f-4ddc-a278-3f81a3798686">Windows Server 2008 for Itanium-based Systems</a>
                    <br />(Moderat)</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>
                    <br />(KB954430)<br />(Lav)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Windows 7</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133434">
                      <strong>MS08-068</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows 7 for 32-biters systemer og Windows 7 for 32-biters systemer Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>
                    <br />(KB954430)<br />(Viktig)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows 7 for x64-baserte systemer og Windows 7 for x64-baserte systemer Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>
                    <br />(KB954430)<br />(Viktig)</td><td>Ikke relevant</td></tr>
              
                <tr><th colspan="3">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=133434">
                      <strong>MS08-068</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Lav</strong>
                    </a>
                  </td><td>Ingen</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-baserte systemer og Windows Server 2008 R2 for x64-baserte systemer med Service Pack 2**[1]</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>**<br />(KB954430)<br />(Lav)</td><td>Ikke relevant</td></tr>
                <tr><td>Windows Server 2008 R2 for Itanium-baserte systemer og Windows Server 2008 R2 for Itanium-baserte systemer med Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=96a4413c-5261-4f69-83d0-932c430abd14">Microsoft XML Core Services 4.0</a>
                    <br />(KB954430)<br />(Lav)</td><td>Ikke relevant</td></tr>
              </table>


**\*Server Core-installasjonen berørt.** Denne oppdateringen gjelder (med samme alvorlighetsgrad) for støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, enten de ble installert med installasjonsalternativet for Server Core eller ikke. Du finner mer informasjon om dette installasjonsalternativet, kan du se MSDN-artiklene [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet, kan du se MSDN-artiklene [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3">Microsoft XML Core Services 5.0</a>
                    <br />(KB951535)<br />(Viktig)<br /></td></tr>
                <tr class="alternateRow"><td>2007 Microsoft Office System og 2007 Microsoft Office System Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245">Microsoft XML Core Services 5.0</a>
                    <br />(KB951550)<br />(Viktig)<br /></td></tr>
              
                <tr><th colspan="2">Annen Office-programvare</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=128803">
                      <strong>MS08-069</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Word Viewer 2003 Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7ad891a8-c3bb-4479-8282-13d629c410e3">Microsoft XML Core Services 5.0</a>
                    <br />(KB951535)<br />(Viktig)<br /></td></tr>
                <tr class="alternateRow"><td>Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007, Microsoft Office Compatibility Pack for filformater for Word, Excel og PowerPoint 2007 Service Pack 1</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245">Microsoft XML Core Services 5.0</a>
                    <br />(KB951550)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Expression Web og Microsoft Expression Web 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=27b06ee8-570a-4dc2-a230-c70d4a706245">Microsoft XML Core Services 5.0</a>
                    <br />(KB951550)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office SharePoint Server 2007 og Microsoft Office SharePoint Server 2007 Service Pack 1 (32-biters versjoner)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a208f2b5-2b0d-43bb-8f8a-58d4a3fc64f5">Microsoft XML Core Services 5.0</a>
                    <br />(KB951597)<br />(Viktig)</td></tr>
                <tr><td>Microsoft Office SharePoint Server 2007 og Microsoft Office SharePoint Server 2007 Service Pack 1 (64-biters versjoner)</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c">Microsoft XML Core Services 5.0</a>
                    <br />(KB951597)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office Groove Server 2007</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c">Microsoft XML Core Services 5.0</a>
                    <br />(KB951597)<br />(Viktig)</td></tr>
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

**Systems Management Server:**

Microsoft Systems Management Server (SMS) er en svært fleksibel løsning for bedrifter for administrasjon av oppdateringer. Ved hjelp av SMS kan administratorer identifisere Windows-baserte systemer som trenger sikkerhetsoppdateringer, og utføre kontrollert distribusjon av disse oppdateringene i virksomheten med et minimalt avbrudd for sluttbrukerne. Den neste versjonen av SMS, System Center Configuration Manager 2007, er nå tilgjengelig. Se også [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx). Hvis du vil ha mer informasjon om hvordan administratorer kan bruke SMS 2003 til å distribuere sikkerhetsoppdateringer, kan du gå til [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Brukere av SMS 2.0 kan også bruke [Software Updates Services Feature Pack](http://go.microsoft.com/fwlink/?linkid=33340) for å få hjelp til å distribuere sikkerhetsoppdateringer. Hvis du vil ha informasjon om SMS, kan du gå til [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Obs\!** SMS bruker Microsoft Baseline Security Analyzer og Microsoft Office-søkeverktøyet til å gi omfattende støtte for oppdaging og distribusjon av sikkerhetsbulletiner. Enkelte programvareoppdateringer oppdages kanskje ikke av disse verktøyene. Administratorer kan i slike tilfeller bruke lagerfunksjonene i SMS for å knytte oppdateringer til bestemte systemer. Hvis du vil ha mer informasjon om denne fremgangsmåten, kan du lese [Deploying Software Updates Using the SMS Software Distribution Feature](http://go.microsoft.com/fwlink/?linkid=33341). Noen sikkerhetsoppdateringer krever administrative rettigheter etter at datamaskinen er startet på nytt. Administratorer kan bruke distribusjonsverktøyet for hevede rettigheter (tilgjengelig i [SMS 2003 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=33387) og i [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)) til å installere disse oppdateringene.

**Update Compatibility Evaluator og Application Compatibility Toolkit**

Oppdateringer skriver ofte til de samme filene og registerinnstillingene som er nødvendige for at programmene dine kan kjøres. Dette kan føre til inkompatibilitet og til at det tar lenger tid å distribuere sikkerhetsoppdateringer. Du kan strømlinjeforme testing og validere Windows-oppdateringer mot installerte programmer med [Update Compatibility Evaluator](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true)-komponentene som følger med [Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en).

Application Compatibility Toolkit (ACT) inneholder verktøy og dokumentasjon som er nødvendig for å kunne vurdere og begrense problemer med programkompatibilitet før distribusjon av Microsoft Windows Vista, en Windows Update-oppdatering, en sikkerhetsoppdatering fra Microsoft eller en ny versjon av Windows Internet Explorer i miljøet.

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

Hvis du vil ha informasjon om ikke-sikkerhetsrelaterte versjoner på Windows Update og Microsoft Update, kan du se:

  - [Microsoft Knowledge Base-artikkel 894199](http://support.microsoft.com/kb/894199): Beskrivelse av innholdsendringer for Software Update Services og Windows Server Update Services 2008. Inkluderer alt Windows-innhold.
  - [Nye, reviderte og utgitte oppdateringer for andre Microsoft-produkter enn Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

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

  - Gregory Fleischer for rapporten om et sikkerhetsproblem som beskrives i MS08-069
  - Stefano Di Paola hos [Minded Security](http://www.mindedsecurity.com/) for rapporten om et sikkerhetsproblem som beskrives i MS08-069

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (11. november 2008): Publisert sammendrag av sikkerhetsbulletin.
  - V2.0 (29. april 2009): Microsoft XML Core Services 4.0 (KB954430) på 32-biters og x64-baserte versjoner av Windows Vista Service Pack 2 og på 32-biters og x64-baserte versjoner og Itanium-based-versjoner av Windows Server 2008 Service Pack 2 er lagt til som berørt programvare for MS08-069. Dette er bare en gjenkjenningsending, det var ingen endringer i binære filer. Kunder som allerede har installert KB954430 uten problemer, trenger ikke å gjøre det på nytt.
  - V3.0 (13. oktober 2009): Microsoft XML Core Services 4.0 (KB954430) når installert på 32-biters og x64-baserte versjoner av Windows 7 og x64-baserte versjoner og Itanium-based-versjoner av Windows Server 2008 R2 er lagt til som berørt programvare for MS08-069. Dette er bare en gjenkjenningsending, det var ingen endringer i binære filer. Kunder som allerede har installert KB954430 uten problemer, trenger ikke å gjøre det på nytt.
  - V4.0 (12. juli 2011): Microsoft XML Core Services 4.0 (KB954430) når installert på 32-biters og x64-baserte versjoner av Windows 7 Service Pack 1 og x64-baserte versjoner og Itanium-based-versjoner av Windows Server 2008 R2 Service Pack 1 er lagt til som berørt programvare for MS08-069. Dette er bare en gjenkjenningsending, det var ingen endringer i binære filer. Kunder som allerede har installert KB954430 uten problemer, trenger ikke å gjøre det på nytt.

*Built at 2014-04-18T01:50:00Z-07:00*

