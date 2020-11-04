
# Voorkennis

- [Oefenzitting LaTex](https://github.com/informaticawerktuigen/oefenzitting-latex)
- [Basiskennis van Linux](https://github.com/informaticawerktuigen/oefenzitting-linux)
- [Werkende Linux-omgeving](https://github.com/informaticawerktuigen/klaarzetten-werkomgeving)


# Starten

In deze oefenzitting leren we werken met Beamer. Beamer is een LaTeX-klasse waarmee je presentaties kan genereren.

De opgave van deze oefenzitting is een PDF-bestand dat jullie zelf moeten genereren. Doe dit door:

- De repository van deze oefenzitting te clonen naar je machine

```shell
git clone https://github.com/informaticawerktuigen/oefenzitting-beamer.git
```

- In een terminal te navigeren naar de folder van deze repository en vervolgens het `pdflatex`-commando uit te voeren, met als argument het bestand beamer.tex:

```shell
cd oefenzitting-beamer
pdflatex beamer.tex
```

Dit commando genereert een PDF-bestand genaamd beamer.pdf. Het PDF-bestand is de opgave voor deze oefenzitting.

- Open dit bestand met `evince` en werk de oefenzitting verder af

```shell
evince beamer.pdf
```
