---
layout: single
title:  "Dochód pasywny - wrzesień 2020"
date:   2020-10-03 12:00:00 +0100
header:
    teaser: /assets/img/2020-10-03-Dochód-pasywny-wrzesien-2020/teaser.jpg
---

Do trzech razy sztuka. Kolejne podsumowanie moich działań i pasywnych dochodów. Czy w moich inwestycjach nadal trwa lato? Czy może czuć już nachodzącą, skutą lodem zimę? Zobaczmy to w pierwszym wrześniowym podsumowaniu!

## Podsumowanie

We wrześniu otrzymałem łącznie **25,51 zł** i **24,20 €** pasywnego dochodu. W przeliczeniu na złotówki na podstawie kursu z ostatniego dnia miesiąca oznacza to łączny dochód w wysokości **135,17 zł** przy kapitale na ostatni dzień miesiąca w wysokości **17 091,13 zł**. Zwroty tak jak ostatnio pochodzą z 3 inwestycji w 2 produkty finansowe. Zaczynając po kolei od najwyższych zysków:

## Mintos EUR

To znów nie był mój najlepszy miesiąc na tym portalu w tej walucie, lecz wciąż udało się uzyskać zwrot w wysokości **17,21 €**. Zauważalny spadek względem ostatniego miesiąca, lecz przy zainwestowanym kapitale i aktualnej rynkowej sytuacji - akceptowalny pod względem ryzyk i satysfakcjonujący pod względem zwrotu :-)

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
                    "data": [19.92, 21.23, 17.21],
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

Po gwałtownym strzalne spowalniamy. W tym miesiącu Crowderstor wzbogacił mnie o **6.99 €**. To zrozumiałe względem małej ilości aktualnie dobranych projektów, jak i specyfiki portalu (pożyczki biznesowe). We wrześniu reinwestowałem 61.68 euro, które dotychczas uzbierało się z powracającego kapitału i odsetek oraz na koniec miesiąca powiększyłem swoją pozycję o kolejne 152 euro.

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
                    "data": [6.12, 14.09, 6.99],
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

Po oziębłym sierpniu inwestycje w rodzimej walucie wracają na dobre tory. Wartość mojego konta wzrosła o **25,51** zł. Wciąż współczynnik opóźnionych płatności wskazuje zatrważające 50% inwestycji. Wciąż kwestia Capital Service pozostaje nierozwiązana. Niemniej nie ma powodów ku nadmiernej panice!

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
                    "data":[32.02, 13.70, 25.51],
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