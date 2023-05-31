# Regelingenportaal

Dit is het tweede van de 4 loketten die tezamen het VIL vormen.

Het regelingenportaal zorgt ervoor dat een gebruiker zijn gegevens vanuit de wallet tegen regelingen aan kan houden. Afhankelijk van de uitkomst daarvan krijgt de gebruiker een Voucher als VC terug in zijn wallet. Voor meer inzicht in hoe een en ander ander technisch is gebouwd, zie het [technisch ontwerp](techniek.md).

## Welke regelingen?

Op dit moment kunnen voor VIL de volgende inkomensafhankelijke regelingen via het regelingenportaal worden gecheckt:

* [individuele inkomenstoeslag](iit.md) (IIT)
* [draagkrachtberekening](draagkracht.md) (bijzondere bijstand)
* [huurtoeslag](huurtoeslag.md) (element van de draagkrachtberekening)

Het regelingenportaal is door de ontkoppeling eenvoudig uit te breiden naar meerdere lokale en landelijke regelingen.

## Voucher

Als men in aanmerking komt voor een regeling zal het portaal een Voucher sturen naar de wallet, die een claim voorstelt van een recht op de regeling. Om die claim te verzilveren zal de Voucher ingewisseld worden bij de formele aanvraag van de betreffende regeling. De Voucher bevat:

* de uitkomst van de regelingencheck, met referentie naar de regeltabel (DMN)
* de gegevens (VCs) waarmee de regeling is gecheckt

## Hoe kom ik daar?

1. Verzamel eerst de gegevens in je wallet via het [uitreikportaal](uitreikportaal.md)
2. Ga dan naar [regelingenportaal.nl](https://regelingenportaal.nl) en volg de instructies op
