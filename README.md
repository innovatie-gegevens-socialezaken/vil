# VIL Documentatie

 Documentatie voor Virtueel Inkomsten Loket

# [Wallet](wallet.md)

Voor het gebruik van het Virtueel Inkomsten Loket (VIL) )is een zogenaamde SSI *wallet* nodig. SSI staat voor Self Sovereign Identity en bevat [standaarden](https://www.w3.org/TR/vc-data-model/ "W3C DID en Verifiable Credentials") voor het uitwisselen van gegevens met behoud van privacy. De wallet is een App voor op je telefoon en kan je downloaden vanuit de Appstore (voor [iPhone](https://apps.apple.com/sa/app/sovrhd/id1571101544 "SSI wallet")) of de Google Play Store (voor [Android phone](https://play.google.com/store/apps/details?id=com.ovrhd.sovrhd "sovrhd app"))

# Ontwerp

Het VIL bevat inkomensafhankelijke overheidsregelingen waarbij je zelf kan beoordelen of je voor een regeling in aanmerking komt, door het verzamelen van betrouwbare gegevens in je wallet en die vervolgens tegen de voorwaarden van de regeling aan te houden. Het VIL bestaat concreet uit 4 digitale portalen:

1. Uitreikportaal
2. Regelingenportaal
3. Inwisselportaal
4. Consulentenportaal

![1682423951989](https://file+.vscode-resource.vscode-cdn.net/Users/marc/GitHub/VIL-Documentatie/image/README/1682423951989.png)De klantreis is zodanig dat de portalen in deze volgorde worden doorlopen om uiteindelijk de gevraagde dienst af te kunnen nemen. Het Uitreikportaal (1) )bevat functies om bepaalde gegevens in je wallet te laden. Met deze gegevens kan je dan vervolgens in het Regelingenportaal (2) checken of je voor een bepaalde regeling in aanmerking komt. Als dat zo is ontvang je een Voucher in je wallet, die in feite een claim voorstelt op een bepaald recht. Deze Voucher kan je dan inwisselen in het Inwisselportaal (3), waarmee formeel een Aanvraag voor een dienst wordt opgestart. Deze Aanvraag wordt door een ambtenaar (gemeente consulent) beoordeeld in het Consulentenportaal (4) of Besluitportaal op basis van de ingewisselde Voucher, die de uitkomst van de regelingencheck bevat en de oorspronkelijke gegevens waarmee de check is uitgevoerd, dus een check op de voorwaarden van de regeling. Als de ambtenaar een en ander heeft geverifieerd volgt er een Besluit of Beschikking die in de gemeentelijke administratie wordt opgeslagen en als een transactiebewijs ook naar je wallet wordt gestuurd. Dan begint het reguliere proces van de regeling te lopen.

Rationale
