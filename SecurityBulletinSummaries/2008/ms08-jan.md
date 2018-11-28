---
title: Sammendrag av Microsofts sikkerhetsbulletiner for januar 2008
TOCTitle: MS08-JAN
ms:assetid: ms08-jan
ms:mtpsurl: https://technet.microsoft.com/nb-NO/library/ms08-jan(v=Security.10)
ms:contentKeyID: 61315192
ms.date: 04/18/2014
mtps_version: v=Security.10
ms.translationtype: HT
---

# Sammendrag av Microsofts sikkerhetsbulletiner for januar 2008

Publisert: 8. januar 2008 | Oppdatert: 25. januar 2008

**Versjon:** 1.2

Dette sammendraget av sikkerhetsbulletiner inneholder en liste over sikkerhetsbulletinene som utgis i januar 2008.

I forbindelse med utgivelsen av bulletinene for januar 2008 erstatter dette sammendraget av sikkerhetsbulletiner forhåndsvarslingen for bulletiner som ble utstedt 3. januar 2008. Hvis du vil ha mer informasjon om forhåndsvarselstjenesten for bulletiner, kan du se [Forhåndsvarsel for Microsofts sikkerhetsbulletin](http://technet.microsoft.com/security/bulletin/advance).

Hvis du vil ha informasjon om hvordan du kan få beskjed automatisk når Microsofts sikkerhetsbulletiner utstedes, kan du gå til [Microsoft Technical Security Notifications](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft holder en webcast for å svare på spørsmål fra kundene om disse bulletinene 9. januar 2008 kl. 11.00, stillehavstid (USA og Canada). [Registrer deg nå for å følge sikkerhetsbulletinen for januar på webcast](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357213&eventcategory=4&culture=en-us&countrycode=us). Etter denne datoen er webcasten tilgjengelig på forespørsel. Hvis du vil ha mer informasjon, kan du se [Sammendrag av Microsofts sikkerhetsbulletiner og webcast-arrangementer](http://technet.microsoft.com/security/bulletin/summary).

Microsoft gir også informasjon for å hjelpe kundene med å prioritere månedlige sikkerhetsoppdateringer mot ikke-sikkerhetsrelaterte oppdateringer som gis ut samme dag som de månedlige sikkerhetsoppdateringene. Se delen **Annen informasjon**.

### Bulletininformasjon

#### Kortfattede sammendrag

Sikkerhetsbulletinene for denne måneden er som følger, listet etter alvorlighetsgrad:

## Kritisk (1)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-001</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104919"><strong>Sikkerhetsproblemer i Windows TCP/IP kan tillate ekstern kjøring av kode (941644)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne kritiske sikkerhetsoppdateringen løser to privat rapporterte sikkerhetsproblemer i TCP/IP-behandling (Transmission Control Protocol/Internet Protocol). En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fulle brukerrettigheter.</td>
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
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows.</strong> Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Viktig (1)

<table>
<thead>
<tr class="header">
<th>Bulletinidentifikator</th>
<th>Microsofts sikkerhetsbulletin MS08-002</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Bulletintittel</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=104921"><strong>Sikkerhetsproblem i LSASS kan tillate rettighetsutvidelse (943485)</strong></a></td>
</tr>
<tr class="even">
<td><strong>Kortfattet sammendrag</strong></td>
<td>Denne viktige oppdateringen løser et personlig rapportert sikkerhetsproblem i Microsoft Windows Local Security Authority Subsystem Service (LSASS). Sikkerhetsproblemet kan gjøre det mulig for en angriper å kjøre vilkårlig kode med utvidede rettigheter. En angriper som klarer å utnytte dette sikkerhetsproblemet, kan få full kontroll over et berørt system. En angriper kan deretter installere programmer, vise, endre eller slette data, eller opprette nye kontoer med fulle brukerrettigheter.</td>
</tr>
<tr class="odd">
<td><strong>Maksimal alvorlighetsgrad</strong></td>
<td><a href="http://go.microsoft.com/fwlink/?linkid=21140">Viktig</a></td>
</tr>
<tr class="even">
<td><strong>Følger av sikkerhetsproblemet</strong></td>
<td>Lokal rettighetsutvidelse</td>
</tr>
<tr class="odd">
<td><strong>Søking</strong></td>
<td>Microsoft Baseline Security Analyzer kan finne ut om datasystemet trenger denne oppdateringen. Denne oppdateringen krever en omstart.</td>
</tr>
<tr class="even">
<td><strong>Berørt programvare</strong></td>
<td><strong>Windows. </strong>Hvis du vi ha mer informasjon, kan du se delen Berørt programvare og nedlastingssteder.</td>
</tr>
</tbody>
</table>


## Berørt programvare og nedlastingssteder

**Hvordan bruker jeg denne tabellen?**

Bruk tabellen til å lære om sikkerhetsoppdateringer som du kanskje må installere. Du bør gå gjennom alle oppførte programmer eller programvarekomponenter for å se om det finnes nødvendige sikkerhetsoppdateringer. Hvis et program eller en programvarekomponent er oppført, vil virkningen av sikkerhetsproblemet også være oppført i tillegg til en hyperkobling til den tilgjengelige programvareoppdateringen.

**Obs\!** Det kan hende at du må installere flere sikkerhetsoppdateringer for et enkelt sikkerhetsproblem. Gå gjennom hele kolonnen for hver bulletinidentifikator som er oppført, for å kontrollere oppdateringene du har installert, basert på programmer eller komponenter som du har installert på datamaskinen.

**Berørt programvare og nedlastingssteder**

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr class="thead">
    <th></th>
    <th>Detaljer        </th>
    <th>Detaljer        </th>
  </tr>
            <tr><td>
                <strong>Bulletinidentifikator</strong>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104919">
                  <strong>MS08-001</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=104921">
                  <strong>MS08-002</strong>
                </a>
              </td></tr>
            <tr class="alternateRow"><td>
                <strong>Maksimal alvorlighetsgrad</strong>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Kritisk</strong>
                </a>
              </td><td>
                <a Target="" runat="server" href="http://go.microsoft.com/fwlink/?linkid=21140">
                  <strong>Viktig</strong>
                </a>
              </td></tr>
          
            <tr><th colspan="3">Windows-operativsystem:</th></tr>
          
            <tr><td>Microsoft Windows 2000 Service Pack 4</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=980f5457-c7b5-421c-8643-0e57429ec156">Moderat</a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=7956632e-17d9-4876-8340-84fe3e43e5cc">Viktig</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows XP Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0a766242-2342-4fa0-9b66-8953c54a2211">Kritisk</a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=6a4cf182-8e36-490e-aefe-edb7b3a0df9c">Viktig</a>
              </td></tr>
            <tr><td>Windows XP Professional x64 Edition og Windows XP Professional x64 Edition Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2e8bc7d5-fe81-4ed5-9efa-360738d160ee">Kritisk</a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=51fc657b-2b4a-4725-a744-d279e027c4a5">Viktig</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 Service Pack 1 og Windows Server 2003 Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be">Viktig</a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=12397b47-b18f-4d4d-b8d7-adec8ff310d5">Viktig</a>
              </td></tr>
            <tr><td>Windows Server 2003 x64 Edition og Windows Server 2003 x64 Edition Service Pack 2</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=19d993f9-06dd-4dc4-b0cc-c59e822eb8fa">Viktig</a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=f19fd790-a4e6-4a8a-8077-d1bbfe37ecca">Viktig</a>
              </td></tr>
            <tr class="alternateRow"><td>Windows Server 2003 SP1 for Itanium-based Systems og Windows Server 2003 SP2 for Itanium-based Systems</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=2c2264f7-ebbb-40ab-9dbf-9b4e313665a7">Viktig</a>
              </td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=0382a195-aa3d-409b-8a79-9fe61588d8a9">Viktig</a>
              </td></tr>
            <tr><td>Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 og Windows Home Server</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be">Kritisk</a>
              </td><td /></tr>
            <tr class="alternateRow"><td>Windows Vista</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=23c0e03a-db66-4618-bce0-af55e5c1b067">Kritisk</a>
              </td><td /></tr>
            <tr><td>Windows Vista x64 Edition</td><td>
                <a Target="" runat="server" href="http://www.microsoft.com/downloads/details.aspx?familyid=5f6a37b1-c604-47c9-932f-485db2eda133">Kritisk</a>
              </td><td /></tr>
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

### Annen informasjon

#### Microsoft Windows-verktøy for fjerning av skadelig programvare

Microsoft har utgitt en oppdatert versjon av Microsoft-verktøyet for fjerning av ondsinnet programvare på Windows Update, Microsoft Update, Windows Server Update Services og Download Center.

#### Ikke-sikkerhetsrelaterte, høyt prioriterte oppdateringer på MU, WU og WSUS:

For denne måneden:

  - Microsoft har utgitt fem **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update (MU) og Windows Server Update Services (WSUS).
  - Microsoft har utgitt to **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer for Windows på Windows Update (WU) og WSUS.

Vær oppmerksom på at denne informasjonen **bare** gjelder **ikke-sikkerhetsrelaterte**, høyt prioriterte oppdateringer på Microsoft Update, Windows Update og Windows Server Update Services som ble utgitt samme dag som sammendraget av sikkerhetsbulletinen. Det gis **ikke** informasjon om **ikke-sikkerhetsrelaterte** oppdateringer som utgis andre dager.

#### Sikkerhetsstrategier og -sone

**Strategier for behandling av oppdateringer**

På webområdet [Security Guidance for Patch Management](http://go.microsoft.com/fwlink/?linkid=21168) finner du mer informasjon om Microsofts anbefalinger for gode fremgangsmåter for å bruke sikkerhetsdata.

**Få tak i andre sikkerhetsoppdateringer**

Oppdateringer for andre sikkerhetsproblemer finnes på følgende steder:

  - Sikkerhetsoppdateringer finnes på [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129). Du finner dem enkelt ved å foreta et nøkkelordsøk etter "sikkerhetsoppdatering".
  - Oppdateringer for forbrukerplattformer finnes på [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747).
  - Du kan få sikkerhetsoppdateringene som tilbys på Windows Update denne måneden, fra Download Center på Security and Critical Releases ISO CD Image-filer. Hvis du vil ha mer informasjon, kan du se [Microsoft Knowledge Base-artikkel 913086](http://support.microsoft.com/kb/913086).

**Sikkerhetsmiljø for IT-eksperter**

Lær hvordan du kan forbedre sikkerheten og optimalisere IT-infrastrukturen, og delta sammen med andre IT-eksperter i diskusjoner om sikkerhet i [sikkerhetssonen for IT-eksperter](http://go.microsoft.com/fwlink/?linkid=21164).

#### Takk til

Microsoft [takker](http://go.microsoft.com/fwlink/?linkid=21127) følgende for samarbeidet med å beskytte kundene:

  - [IBM Internet Security Systems X-Force](http://www.iss.net/) ved Alex Wheeler og Ryan Smith for rapporten om et sikkerhetsproblem som beskrives i [MS08-001](http://go.microsoft.com/fwlink/?linkid=104919)
  - [IBM Internet Security Systems X-Force](http://www.iss.net/) ved Alex Wheeler og Ryan Smith for rapporten om et sikkerhetsproblem som beskrives i [MS08-001](http://go.microsoft.com/fwlink/?linkid=104919)
  - Thomas Garnier hos [SkyRecon](http://www.skyrecon.com/) for rapporten om et sikkerhetsproblem som beskrives i [MS08-002](http://go.microsoft.com/fwlink/?linkid=104921)

#### Kundestøtte

  - Den berørte programvaren som er oppført, er testet for å avgjøre hvilke versjoner som er berørt. Andre versjoner har nådd slutten av kundestøttesyklusen. Se [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742) for å finne kundestøttesyklusen for programvareversjonen du bruker.
  - Kunder i USA og Canada kan få kundestøtte hos [Microsoft Product Support Services](http://go.microsoft.com/fwlink/?linkid=21131) på telefon 1-866-PCSAFETY. Kundestøttesamtaler i forbindelse med sikkerhetsoppdateringer er gratis.
  - Internasjonale kunder kan få kundestøtte fra de lokale representasjonskontorene for Microsoft. Kundestøtte i forbindelse med sikkerhetsoppdateringer er gratis. Hvis du vil ha mer informasjon om hvordan du kontakter Microsoft angående kundestøtteproblemer, går du til [internasjonal hjelp og støtte](http://go.microsoft.com/fwlink/?linkid=21155).

#### Ansvarsfraskrivelse

Informasjonen i Microsoft Knowledge Base er levert "som den er" uten garantier av noen art. Microsoft fraskriver seg ethvert ansvar, enten direkte eller indirekte, herunder garantier om salgbarhet og anvendelighet for særskilte formål. Microsoft Corporation eller dets leverandører skal ikke under noen omstendigheter holdes ansvarlig for noen skader eller tap herunder direkte, indirekte eller tilfeldige skader eller tap, konsekvenstap, tap av inntekter eller spesielle skader, også i tilfeller der Microsoft Corporation eller dets leverandører er underrettet om muligheten for slike skader eller tap. Ettersom enkelte land ikke tillater fraskrivelse eller begrensning av ansvar for følgeskade eller tilfeldig skade, kan det hende at ovennevnte begrensning ikke gjelder.

#### Revisjoner

  - V1.0 (8. januar 2008): Publisert sammendrag av sikkerhetsbulletin.
  - V1.1 (23. januar 2008): Sammendrag av bulletin oppdatert for å legge til Windows Small Business Server 2003 Service Pack 2 som berørt programvare for MS08-001-bulletinen.
  - V1.2 (25. januar 2008): Sammendrag av sikkerhetsbulletin oppdatert for å legge til Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 og Windows Home Server som berørt programvare for sikkerhetsbulletinen MS08-001.

*Built at 2014-04-18T01:50:00Z-07:00*

