---
layout: single
title:  "Dochód pasywny - lipiec 2020"
date:   2020-08-06 12:00:00 +0100
header:
    teaser: /assets/img/2020-08-06-Dochód-pasywny-lipiec-2020/teaser.jpg
---

Oto pierwsze podsumowanie moich działań. Zdążyliśmy już omówić takie aspekty jak powody dla których warto zainteresować się dochodem pasywnym, jak go interpretować oraz jak poprawnie ustanowić cele. Ten wpis będzie pierwszym z serii realnych przykładów przybliżających nas do prawdziwej finansowej niezależności.

## Trudny start

Nie miałem jeszcze możliwości publicznie opowiedzieć o konkretnych sposobach w jaki ja realizuję moje uniezależnienie od aktywnego zarobkowania. Wynika to z prostego faktu, że zanim wyrażę głośno i publicznie opinię o danym produkcie lub sposobie- a za taką formę należy traktować publikację na blogu - muszę sam przekonać się o takich elementach jak:
- Wygoda
- Bezpieczeństwo
- Efektywność
- Etyka

## Podsumowanie

W lipcu otrzymałem łącznie **32,03 zł** i **26,04 €** pasywnego dochodu. W przeliczeniu na złotówki na podstawie kursu z ostatniego dnia miesiąca oznacza łączny dochód w wysokości **146,85 zł** przy zachowaniu zainwestowanego kapitału w wysokości **12 225,63 zł** na pierwszy dzień miesiąca. Zwroty pochodzą z 3 inwestycji w 2 produkty finansowe. Zaczynając po kolei od najwyższych zysków.

## Mintos EUR

To nie był mój najlepszy miesiąc na tym portalu w tej walucie, lecz wciąż udało się uzyskać zwrot w wysokości **19,92 €**. Przez cały miesiąc nie dokonałem ani jednej akcji w portalu. Nie zmieniałem wysokości kapitału, ani nie zmieniałem ustawień inwestowania - typowo pasywny zysk.

<canvas id="mintosEurChart" width="400" height="250"></canvas>
<script>
var ctx = document.getElementById('mintosEurChart').getContext('2d');
var myChart = new Chart(ctx,
    {
        "type":"line",
        "data":
        {
            "labels":["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"],
            "datasets":[
                {
                    "label":"Mintos EUR",
                    "data":[19.92],
                    "fill":false,
                    "borderColor":"rgb(75, 192, 192)",
                    "lineTension":0.1
                }
                ]}
    }
);
</script>

## Mintos PLN

W naszej rodzimej walucie mam w tym miesiącu najlepszy wynik do tej pory. Wartość mojego konta wzrosła o **32,02 zł**. Tak jak wcześniej przez cały miesiąc nie dokonałem ani jednej akcji w portalu.

<canvas id="mintosPlnChart" width="400" height="250"></canvas>
<script>
var ctx = document.getElementById('mintosPlnChart').getContext('2d');
var myChart = new Chart(ctx,
    {
        "type":"line",
        "data":
        {
            "labels":["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"],
            "datasets":[
                {
                    "label":"Mintos EUR",
                    "data":[32.02],
                    "fill":false,
                    "borderColor":"rgb(75, 192, 192)",
                    "lineTension":0.1
                }
                ]}
    }
);
</script>

## Crowdestor

To dla mnie pierwszy miesiąc z tą platoformą. Pierwsze fundusze przelałem 02.07.2020 w kwocie 280.73 € i całość zainwestowałem w jeden projekt. W lipcu otrzymałem jedeną płątność z odsetkami w wysokośći **6,12 €**. Na koniec miesiąca dokonałęm jeszcze dwóch przelewów zwiększając swoją pozycję w tym serwisie.

<canvas id="crowdestorChart" width="400" height="250"></canvas>
<script>
var ctx = document.getElementById('crowdestorChart').getContext('2d');
var myChart = new Chart(ctx,
    {
        "type": "line",
        "data":
        {
            "labels": ["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"],
            "datasets": [
                {
                    "label": "Crowdestor",
                    "data": [6.12],
                    "fill": false,
                    "borderColor": "rgb(75, 192, 192)",
                    "lineTension": 0.1
                }
                ]}
    }
);
</script>