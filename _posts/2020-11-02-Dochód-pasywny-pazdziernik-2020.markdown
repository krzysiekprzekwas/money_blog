---
layout: single
title:  "Dochód pasywny - październik 2020"
date:   2020-11-02 12:00:00 +0100
header:
    teaser: /assets/img/2020-11-02-Dochód-pasywny-pazdziernik-2020/teaser.png
---

Środek jesień. Podsumowanie moich działań i pasywnych dochodów z miesiąca października. Podsumujmy zwroty i zmiany w kapitale w minionym miesiącu.

## Podsumowanie

W październiku otrzymałem łącznie **21,77 zł** i **25,10 €** pasywnego dochodu. W przeliczeniu na złotówki na podstawie kursu z ostatniego dnia miesiąca oznacza to łączny dochód w wysokości **137,70 zł** przy kapitale na ostatni dzień miesiąca w wysokości **17 311,47 zł**. Inwestycje, po raz pierwszy od kiedy prowadzę tego bloga, pochodzą z 4 inwestycji w 3 produkty finansowe. Dołącza do nas portal **EvoEstate**! Zaczynając po kolei od najwyższych zysków:

## Mintos EUR

Zwroty zdają się normować na podobnym poziomie w ostatnich miesiącach. Platforma wygenerowała zysk w wysokości **19,74 €**. Dokonałem w tym miesiącu jedynie drobnych zmian w strategiach automatycznego inwestowania, aby ograniczyć potencjalne opóźnienia w nowo-zakupowanych pożyczkach.

<canvas id="mintosEurChart" width="400" height="250"></canvas>
<script>
var ctx = document.getElementById('mintosEurChart').getContext('2d');
var myChart = new Chart(ctx,
    {
        type: "line",
        data: {
            "labels":["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"],
            "datasets":[{
                    "label": "Mintos EUR",
                    "data": [19.92, 21.23, 17.21, 19.74],
                    "fill": false,
                    "borderColor": "rgb(75, 192, 192)",
                    "lineTension": 0.1
                }]
        },
        options: {
            scales: {
                yAxes: [{
                    ticks: {
                        beginAtZero: true
                    }
                }]
            }
        }
    }
);
</script>

## Crowdestor

Na ostatni dzień miesiąca Crowderstor wzbogacił mnie o **5,36 €**. Jeden z projektów, który miał wygenerować większe zyski, zakończył się dokądnie ostatniego dnia tego miesiąca i płatność jeszcze nie dotarła :-(  W związku z wieloma problemami dotyczącymi niektórych projektów P2B zdecydowałem się nie powiekszać swojej pozycji w tym portalu.

<canvas id="crowdestorChart" width="400" height="250"></canvas>
<script>
var ctx = document.getElementById('crowdestorChart').getContext('2d');
var myChart = new Chart(ctx,
    {
        type: "line",
        data: {
            "labels":["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"],
            "datasets":[{
                    "label": "Crowdestor",
                    "data": [6.12, 14.09, 6.99, 5.36],
                    "fill": false,
                    "borderColor": "rgb(75, 192, 192)",
                    "lineTension": 0.1
                }]
        },
        options: {
            scales: {
                yAxes: [{
                    ticks: {
                        beginAtZero: true
                    }
                }]
            }
        }
    }
);
</script>

## Mintos PLN

Wartość mojego konta w rodzimej walucie wzrosła o **21,77 zł**. Tak jak miesiąc temu współczynnik opóźnionych płatności wskazuje zatrważające 50% inwestycji. Wciąż kwestia Capital Service pozostaje nierozwiązana. Tym razem już tracę zaufanie do naszych pożyczkodawców i redukuję pozycję. Wyłączyłem reinwestycję i z uzyskanych środków wypłaciłem w tym miesiącu **308,88 zł**.

<canvas id="mintosPlnChart" width="400" height="250"></canvas>
<script>
var ctx = document.getElementById('mintosPlnChart').getContext('2d');
var myChart = new Chart(ctx,
    {
        type: "line",
        data: {
            "labels":["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"],
            "datasets":[{
                    "label": "Mintos PLN",
                    "data":[32.02, 13.70, 25.51, 21.77],
                    "fill": false,
                    "borderColor": "rgb(75, 192, 192)",
                    "lineTension": 0.1
                }]
        },
        options: {
            scales: {
                yAxes: [{
                    ticks: {
                        beginAtZero: true
                    }
                }]
            }
        }
    }
);
</script>

## EvoEstate

Witamy nowego debiutanta. Platforma EvoEstate specjalizuje się w pośrednictwie pożyczkowym dla branży nieruchomości. Inwestycję dotyczą rynków pierwotnych, wtórnych, flipów, najmów czy udziałów w projektach deweloperskich. Zdecydowałem się przekierować tutaj kapitał wycofany z Mintosa (**308,88 zł**). Piersze odsetki w grudniu tego roku!