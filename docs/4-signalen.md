# Signalen

Activiteiten uit gebeurtenissen leiden tot het wijzigen van gegevens in de registraties van NWB en/of BGT. Als de ene partij aanpast, zal de andere partij mee moeten aanpassen om beide registraties actueel en consistent met elkaar te houden. Dat betekent dat als de BGT wordt aangepast er op de ene of andere manier een signaal van bronhouder naar wegbeheerder moet gaan, en vice versa, zodanig dat wijzigingen die relevant zijn voor de andere partij worden opgemerkt.

In dit kader onderscheiden we twee typen signalen:

1. Met een **mutatie** bedoelen we een signaal in de vorm van een gegevensbestand in een vast uitwisselformaat waarin de wijziging (was-wordt) van één of meer kenmerken van het object exact wordt doorgegeven. Software kan deze wijziging veelal automatisch overnemen in registraties.
2. Met een **melding** bedoelen we een signaal dat er een wijziging in een bepaald gebied heeft plaatsgevonden, waarin wordt beschreven (toelichtende tekst) op welke manier gegevens zijn gewijzigd of geconstateerd zijn dat deze gegevens afwijken. De ontvanger van een melding zal zelf onderzoek moeten doen op welke manier deze gegevens al dan niet overgenomen moeten worden in registraties. Veelal worden meldingen achteraf verstuurd door gebruikers die een wijziging of onjuistheid in de gegevens hebben geconstateerd (=signalering).

Hierna zullen we een aantal bestaande kanalen schetsen waarin meldingen en mutaties voor NWB en BGT worden uitgewisseld. Organisaties kunnen hier voor hun eigen bijhoudingsproces op aansluiten. Welk kanaal een organisatie kiest, laten we graag over aan de bronhouder en wegbeheerder van een organisatie.

## Mutaties van en meldingen naar NWB 

Gegevens van het NWB zijn beschikbaar in verschillende producten als downloads via Rijkswaterstaat [https://www.rijkswaterstaat.nl/apps/geoservices/geodata/dmc/nwb-wegen/]: o.a. een volledig bestand NWB-Wegen, en een bestand met wijzigingen in het netwerk tussen twee peildatums, zijnde **NWB-wegen mutaties**. Met een mutatiecode wordt aangegeven of een wegvak in die periode is vervallen, gewijzigd of ontstaan. Deze mutaties worden beschikbaar gesteld in de uitleverformaten Geographic Data Files (GDF) en Shape , Arc Info Coverage (AIC) of Arc Info Export (AIE).  

Een melding met een geconstateerde wijzigingen en/of opmerkingen betreffende het NWB kunnen via **het NWB-loket** op emailadres nwb@rws.nl ingediend worden.

## Mutaties van en meldingen naar BGT
Mutaties van en meldingen op BGT-gegevens kunnen via verschillende kanalen worden afgenomen of doorgegeven. Onderstaande figuur toont de uitwisseling van mutaties en meldingen in de BGT-keten.

![](media/bgt_referentiemodel.png)

Mutaties op BGT objecten worden op drie plekken in de BGT keten uitgewisseld:
1. Via **PDOK** worden de gegevens in de Landelijke Voorziening verstrekt aan afnemers via **web service (WMTS) en GML en StUF-Geo IMGeo downloads** van totaalstanden. Op dit moment (februari 2018) werkt PDOK aan een generiek XML/GML-uitwisselformaat voor levering van mutaties in verschillende basisregistraties (BGT, BRK, BAG) aan afnemers.
2. Via **BRAVO** worden **via een abonnementenservice de mutaties** door andere bronhouders verstuurd naar geraakte bronhouders. De mutaties worden uitgewisseld in een StUF-Geo IMGeo mutatiebericht.
3. In het **Geo-BOR koppelvlak** worden **mutaties op BGT-objecten** door de Geo-afdeling in een organisatie verstuurd naar de afdeling Beheer Openbare Ruimte (BOR), die deze gegevens nodig heeft voor groenbeheer, wegbeheer e.d. Een BOR-beheerder kan ook bij een voorgenomen of geconstateerde wijziging op de eigen beheerobjecten (bijvoorbeeld groenvoorzieningen of wegen) een verzoek met wijziging van gegevens aan Geo sturen. De mutaties worden uitgewisseld in een StUF-Geo IMGeo mutatiebericht of mutatieverzoek.

Meldingen over geconstateerde wijzigingen/onjuistheden van BGT-gegevens worden op drie plekken in de BGT keten doorgegeven aan bronhouders:
1. Via **Verbeterdekaart** kan een gebruiker van BGT-gegevens een **terugmelding** doen, door het prikken van een puntlocatie op een interactieve kaart en een toelichting te geven over de geconstateerde afwijking tussen kaart en werkelijkheid. Verbeterdekaart is het offciële terugmeldsysteem (TMS) voor de BGT.
2. Via het **MutatieMeldSysteem** (MMS) van het SVB-BGT kunnen bronhouders de interne werkvoorraad met openstaande meldingen op BGT-gegevens en in-te-meten gebieden bijhouden. 
3. In het **Geo-BOR koppelvlak** kan een BOR-beheerder een verzoek doen aan de Geo-afdeling om een bepaald gebied te onderzoeken en evt. opnieuw in te meten. Dit verzoek wordt uitgewisseld in een StUF-Geo IMGeo exploratieverzoek.

## Relevante mutaties

Niet alle wijzigingen in de registraties van NWB en BGT zijn van belang voor de de andere partij. Bijvoorbeeld het wijzigen van een wegbeheerdercode in het NWB heeft geen vloed op de gegevens van een wegdeel in de BGT, en het wijzigen van het type verharding van een wegdeel in de BGT is niet van belang voor het wegvak in het NWB. Daarom schetsen we hierna welke gegevens in NWB en BGT een relatie hebben met elkaar (mapping). 

**Objecten**

...

**Geometrie**

...

**Attributen**

In bijlage xx.xx. staat een tabel met een mapping van de gegevens tussen het NWB wegvak en objecten in de BGT

