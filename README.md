# ML-project

<b>Naziv projekta:</b> Rock, Paper, Scissors, Lizard, Spock
</br>
</br>
<b>Autori:</b> Jovana Radjenovic, Zorana Aleksic
</br>
</br>
<b>Opis projekta:</b> Rekreiranje igre "Rock, Paper, Scissors, Lizard, Spock" iz serije "The Big Bang Theory"...igra: https://youtu.be/x5Q6-wMx-K8. Ideja: Kamera snima igrača. Igrač stavlja ruku u kvadratić koji se vidi na ekranu. Na osnovu onoga što je stavio i onoga što drugi igrač stavi (ili kompjuter) proglašava se pobednik.
</br>
</br>
<b>Opisom korišćenog skupa podataka:</b> Jedan deo baze je iskoriscen iz vec postojeceg dataset-a ([Rock Paper Scissors Dataset](https://www.tensorflow.org/datasets/catalog/rock_paper_scissors?fbclid=IwAR0gI5kANSViaBfreT38cBEuQQSSdKXYVVCsWlpkrIfzMIs0NJK1sMBK5y4)), zatim je baza dopunjena nedostajucim oblicima (lizard, spock), a postojeci oblici su dopunjeni odgovarajucim slikama.  Za formiranje novih podataka koriscen je [Python skript](https://github.com/SouravJohar/rock-paper-scissors/blob/master/gather_images.py?fbclid=IwAR2b7Anq5vXhFP_A-YYDegejXPx6B8IkiH-tDFeYZIqVKFd3D9SjOxGvfjU) koji implementira image capture. Dataset ima ukupno 3000 slika, gde svaka klasa ima po 500 slika.
