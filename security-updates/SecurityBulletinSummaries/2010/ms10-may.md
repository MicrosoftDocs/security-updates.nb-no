---
title: Sammendrag av Microsofts sikkerhetsbulletiner for mai 2010
TOCTitle: MS10-MAY
ms:assetid: ms10-may
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms10-may(v=Security.10)
ms:contentKeyID: 61315220
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for mai 2010


**Versjon:** 1.2

Dette sammendraget av sikkerhetsbulletinen inneholder en liste over sikkerhetsbulletinene som utgis i mai 2010.

I forbindelse med utgivelsen av bulletinene for mai 2010 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 6. mai 2010. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 12. mai 2010 kl. 11.00 stillehavstid (USA og Canada). [Registrer deg nå for å følge webcasten om sikkerhetsbulletinene for mai](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032427724&culture=en-us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

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
<td><a href="http://go.microsoft.com/fwlink/?linkid=188377">MS10-030</a></td>
<td><strong>Sikkerhetsproblem i Outlook Express og Windows kan tillate ekstern kjøring av kode (978542)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Outlook Express, Windows Mail og Windows Live Mail. Sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis en bruker besøker en skadelig e-postserver. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan oppnå samme brukerrettigheter som den lokale brukeren. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Windows</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=178811">MS10-031</a></td>
<td><strong>Sikkerhetsproblem i Microsoft Visual Basic for Applications kan tillate ekstern kjøring av kode (978213)</strong><br />
<br />
Denne sikkerhetsoppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Visual Basic for Applications. Sikkerhetsproblemet kan potensielt tillate ekstern kjøring av kode hvis et vertsprogram åpner og sender en spesiallaget fil til Visual Basic for Applications Runtime. Hvis en bruker er logget på med administrative rettigheter, kan en angriper som klarte å utnytte dette sikkerhetsproblemet, ta kontroll over det berørte systemet. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fullstendige brukerrettigheter. Brukere med kontoer som er konfigurert med få brukerrettigheter på systemet, er mindre utsatt enn brukere som har administrative rettigheter.</td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisk</a><br />
Ekstern kjøring av kode</td>
<td>Kan kreve omstart</td>
<td>Microsoft Office, Microsoft Visual Basic for Applications</td>
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
<td><a href="http://go.microsoft.com/fwlink/?linkid=178811">MS10-031</a></td>
<td>Sikkerhetsproblem med stakkminnefeil i VBE6.DLL</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0815">CVE-2010-0815</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>(Ingen)</td>
</tr>
<tr class="even">
<td><a href="http://go.microsoft.com/fwlink/?linkid=188377">MS10-030</a></td>
<td>Sikkerhetsproblem med heltallsoverflyt i Outlook Express og Windows Mail</td>
<td><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0816">CVE-2010-0816</a></td>
<td><a href="http://technet.microsoft.com/en-us/security/cc998259.aspx"><strong>2</strong></a> - Inkonsekvent skadelig kode er sannsynlig</td>
<td>Utnyttelse av Windows Vista og nyere operativsystemer er mindre sannsynlig på grunn av heap-begrensninger</td>
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
  </tr>
                <tr><th colspan="2">Microsoft Windows 2000</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=188377">
                      <strong>MS10-030</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=661f5de3-a593-4961-8e8d-2777797eb5c5">Microsoft Outlook Express 5.5 Service Pack 2</a>
                    <br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=cda75174-b535-4559-a52d-b5ec3a1df349">Microsoft Outlook Express 6 Service Pack 1</a><br />(KB978542)<br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Windows XP</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=188377">
                      <strong>MS10-030</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows XP Service Pack 2 og Windows XP Service Pack 3</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703">Microsoft Outlook Express 6</a>
                    <br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=99707c3d-a3cb-47da-b38e-8ae0227fd703">Windows Live Mail</a>[1]<br />(KB978542)<br />(Viktig)</td></tr>
                <tr><td>Windows XP Professional x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44bc97bb-6f76-4c96-af72-69daaea80fff">Microsoft Outlook Express 6</a>
                    <br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=44bc97bb-6f76-4c96-af72-69daaea80fff">Windows Live Mail</a>[1]<br />(KB978542)<br />(Viktig)</td></tr>
              
                <tr><th colspan="2">Windows Server 2003</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=188377">
                      <strong>MS10-030</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=eb9742fc-0934-4b38-9ec4-3597fc71ec00">Microsoft Outlook Express 6</a>
                    <br />(KB978542)<br />(Kritisk)</td></tr>
                <tr><td>Windows Server 2003 x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5678515a-97ea-4e00-8700-d3f2fcdc0efc">Microsoft Outlook Express 6</a>
                    <br />(KB978542)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=60ef635b-cb6d-402f-b904-e69b519d797f">Microsoft Outlook Express 6</a>
                    <br />(KB978542)<br />(Kritisk)</td></tr>
              
                <tr><th colspan="2">Windows Vista</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=188377">
                      <strong>MS10-030</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Vista Service Pack 1 og Windows Vista Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1">Windows Mail</a>
                    <br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a970c869-24fe-4ef4-b189-7a6bac2411f1">Windows Live Mail</a>[1]<br />(KB978542)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Vista x64 Edition Service Pack 1 og Windows Vista x64 Edition Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5">Windows Mail</a>
                    <br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=9a7853b5-4f9f-4467-9530-eea2efd504a5">Windows Live Mail</a>[1]<br />(KB978542)<br />(Viktig)</td></tr>
              
                <tr><th colspan="2">Windows Server 2008</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=188377">
                      <strong>MS10-030</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Windows Server 2008 for 32-biters systemer og Windows Server 2008 for 32-biters systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c">Windows Mail</a>**<br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f77a640-247c-4ed2-9fca-4b7344f4dc7c">Windows Live Mail</a>**[1]<br />(KB978542)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 for x64-baserte systemer og Windows Server 2008 for x64-baserte systemer med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0">Windows Mail</a>**<br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=b0eab011-5847-44e4-bc0d-5c5355e1e8d0">Windows Live Mail</a>**[1]<br />(KB978542)<br />(Viktig)</td></tr>
                <tr><td>Windows Server 2008 for Itanium-based Systems og Windows Server 2008 for Itanium-based Systems med Service Pack 2</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da01ae82-895e-4739-916f-a63b9095a076">Windows Mail</a>
                    <br />(KB978542)<br />(Kritisk)<br /><br /><a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=da01ae82-895e-4739-916f-a63b9095a076">Windows Live Mail</a>[1]<br />(KB978542)<br />(Viktig)</td></tr>
              
                <tr><th colspan="2">Windows 7</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=188377">
                      <strong>MS10-030</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows 7 for 32-biters systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=1f0c17be-ba4c-4a1c-b9c3-8ac368800947">Windows Live Mail</a>
                    [1]
                    <br />(KB978542)<br />(Viktig)</td></tr>
                <tr><td>Windows 7 for x64-baserte systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=a70f15e1-512c-44ca-a308-928e237ac0ce">Windows Live Mail</a>
                    [1]
                    <br />(KB978542)<br />(Viktig)</td></tr>
              
                <tr><th colspan="2">Windows Server 2008 R2</th></tr>
              
                <tr class="alternateRow"><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=188377">
                      <strong>MS10-030</strong>
                    </a>
                  </td></tr>
                <tr><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>Windows Server 2008 R2 for x64-baserte systemer</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=e2e25c02-38ce-4868-a01a-39fc7d2a4150">Windows Live Mail</a>** [1]<br />(KB978542)<br />(Viktig)</td></tr>
                <tr><td>Windows Server 2008 R2 for Itanium-based Systems</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=53ed1055-b5ee-4fde-9550-f8b401916467">Windows Live Mail</a>
                    [1]
                    <br />(KB978542)<br />(Viktig)</td></tr>
              </table>


**Merknad for Windows Server 2008 og Windows Server 2008 R2**

**Server Core-installasjonen ikke berørt.** Sikkerhetsproblemene som løses i denne oppdateringen, berører ikke støttede versjoner av Windows Server 2008 eller Windows Server 2008 R2 som angitt, når de ble installert med installasjonsalternativet for Server Core. Du finner mer informasjon om dette installasjonsalternativet, kan du se MSDN-artiklene [Server Core](http://msdn.microsoft.com/en-us/library/ms723891\(vs.85\).aspx) og [Server Core for Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631\(vs.85\).aspx). Legg merke til at installasjonsalternativet for Server Core ikke gjelder for visse versjoner av Windows Server 2008 og Windows Server 2008 R2. Du finner mer informasjon under [sammenligningen av installasjonsalternativer for Server Core](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Merknad for MS10-030**

\[1\]Windows Live Mail er en komponent på dette operativsystemet som er klar til bruk, som må installeres separat for at sikkerhetsproblemet skal finnes.

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
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178811">
                      <strong>MS10-031</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Viktig</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Office XP</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=72c23b0f-4e24-4334-bc8a-334adc8bc42b">Microsoft Office XP Service Pack 3</a>
                    [1] <br />(KB976380)<br />(Viktig)</td></tr>
                <tr class="alternateRow"><td>Microsoft Office 2003</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f8eac9bc-8389-4ac8-8b29-9a8180d9fd34">Microsoft Office 2003 Service Pack 3</a>
                    [1] <br />(KB976382)<br />(Viktig)</td></tr>
                <tr><td>2007 Microsoft Office System</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=160ad53e-6475-4550-90c2-444e4abea730">2007 Microsoft Office System Service Pack 1 og 2007 Microsoft Office System Service Pack 2</a>
                    [1] <br />(KB976321)<br />(Viktig)</td></tr>
              </table>


**Merknader for MS10-031**

\[1\]Disse oppdateringene for Microsoft Office gjelder for alle støttede Microsoft Office-serier og annen Microsoft Office-programvare som inneholder den sårbare delte Office-komponenten. Dette omfatter, men er ikke begrenset til, støttede versjoner av Microsoft Office Visio og Microsoft Office Project.

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

#### Utviklerverktøy og programvare fra Microsoft

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th></th>
  </tr>
                <tr><th colspan="2">Microsoft Visual Basic for Applications</th></tr>
              
                <tr><td>
                    <strong>Bulletinidentifikator</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=178811">
                      <strong>MS10-031</strong>
                    </a>
                  </td></tr>
                <tr class="alternateRow"><td>
                    <strong>Samlet alvorlighetsgrad</strong>
                  </td><td>
                    <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                      <strong>Kritisk</strong>
                    </a>
                  </td></tr>
                <tr><td>Microsoft Visual Basic for Applications</td><td>
                    <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=436a8a66-352e-44d1-a610-c825083ad24a">Microsoft Visual Basic for Applications</a>
                    [1]
                    <br />(KB974945)<br />(Kritisk)</td></tr>
                <tr class="alternateRow"><td>Microsoft Visual Basic for Applications SDK</td><td>Microsoft Visual Basic for Applications SDK[2][3]<br />(Kritisk)</td></tr>
              </table>


**Merknader for MS10-031**

\[1\]Denne oppdateringspakken gjelder for støttede versjoner av Microsoft Visual Basic for Applications Runtime (Vbe6.dll) og er bare tilgjengelig fra Microsoft Download Center.

\[2\]De støttede versjonene av VBA SDK er Microsoft Visual Basic for Applications SDK 6.3, Microsoft Visual Basic for Applications SDK 6.4 og Microsoft Visual Basic for Applications SDK 6.5.

\[3\]Den oppdaterte versjonen av Visual Basic for Applications SDK som løser sikkerhetsproblemet som beskrives i denne bulletinen, er tilgjengelig for uavhengige programvareleverandører (ISVer) fra [Summit Software Company](http://www.summsoft.com/).

Se også andre programvarekategorier i denne delen, **Berørt programvare og nedlastingssteder**, for å få flere oppdateringsfiler under den samme bulletinidentifikatoren. Denne bulletinen omhandler mer enn én programvarekategori.

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

  - Francis Provencher hos Protek Research Lab for rapporten om et sikkerhetsproblem som beskrives i MS10-030
  - [NSFocus Security Team](http://www.nsfocus.com/) for rapporten om et sikkerhetsproblem som beskrives i MS10-031

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få teknisk støtte fra [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) eller 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis. Du finner mer informasjon om tilgjengelige alternativer for støtte ved å gå til [Microsoft Hjelp og støtte](http://support.microsoft.com/).
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (11. mai 2010): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (12. mai 2010): Korrigert kravene til omstart for MS10-030.
  - V1.2 (19. mai 2010): Fjernet feilaktige referanser for MS10-030 til Windows Mail når installert på Windows 7 og Windows Server 2008 R2. I tillegg er det lagt til merknad om berørt programvare for MS10-031 for å informere om at oppdateringene for Microsoft Office gjelder for alle støttede Microsoft Office-serier og annen Microsoft Office-programvare som inneholder en sårbar versjon av VBE6.dll.

*Built at 2014-04-18T01:50:00Z-07:00*

