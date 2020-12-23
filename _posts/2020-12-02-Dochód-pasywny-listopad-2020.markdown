---
layout: single
title:  "Dochód pasywny - listopad 2020"
date:   2020-12-02 12:00:00 +0100
header:
    teaser: /assets/img/2020-12-02-Dochód-pasywny-listopad-2020/teaser.png
---

Listopad za nami. Rzutem na taśmę udało się ustanowić nowy rekord miesięcznych przychodów. W tym okresie sporo rotowałem kapitałem między portalami, tak więc spójrzmy, jak wygląda portfolio na koniec miesiąca.

## Podsumowanie

W październiku otrzymałem łącznie **10,26 zł** i **36,02 €** pasywnego dochodu. W przeliczeniu na złotówki na podstawie kursu z ostatniego dnia miesiąca oznacza to łączny dochód w wysokości **171,60 zł** przy kapitale na ostatni dzień miesiąca w wysokości **18 832,81 zł**. Dołącza do nas kolejna platforma - **EstateGuru**! Zaczynając po kolei od najwyższych zysków:

## Mintos EUR

Delikatny wzrost otrzymanych odsetek. Platforma wygenerowała zysk w wysokości **22,20 €** przy stanie konta w wysokości **2401,58 €**. Ustawienia pozostawiłęm bez zmian. Moja pozycja w tym serwisie i tak jest już dość znacząca, więc na ten moment nic nie dopłacam. Czekam na rozwój wydarzeń z zalegającymi praktycznie u wszystkich Środkami w trakcie odzyskiwania. Ostatnie wieści na temat spłat zaległości od Capital Finance i Finko uznałbym za umiarkowanie pozytywne.

{% include platform-chart.html id="mintos_eur_chart" platform_name="Mintos EUR" data="[19.92, 21.23, 17.21, 19.74, 22.20]" labels='["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"]' %}

## Crowdestor

W listopadzie Crowderstor wzbogacił mnie o **13,82 €**. Jak bardzo lubię to platformę, tak ma ona naprawdę twardy orzech do zgryzienia z przekonaniem inwestorów do przekazania kolejnych środków do firm, których płynność w ostatnim roku diametralnie się pogorszyła. Za ruch w tę stronę odbieram ogłoszony niedawno 2% cashback na wszystkie inwestycje z rynku pierwotnego w grudniu. Świąteczna promocja czy akt desperacji? Osobiście zdecydowałem się reinwestować środki na platformie w inwestycję dotyczącą rękawiczek medycznych (głównie dlatego, że poprzednia inwestycja tego pożyczkobiorcy poszła bardzo sprawnie). Moja aktualna pozycja w tym portalu to **961.52 €** i nie zamieniam jej zmieniać. 

{% include platform-chart.html id="crowdestor_chart" platform_name="Crowdestor" data="[6.12, 14.09, 6.99, 5.36, 13.82]" labels='["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"]' %}

## Mintos PLN

Wartość mojego konta w rodzimej walucie wzrosła o **10,26 zł**. Nadal ciężka sytuacja patrząc na współczynnik opóźnionych płatności (aktualnie 55% inwestycji). Częściowo spowodowana tym, że wychodzę z tej inwestycji, więc pozostają te najbardziej problematyczne inwestycje. W listopadzie wypłaciłem kolejne **468.96 zł**. Póki co nie sprzedaje pożyczek, dam im jeszcze czas aby się zakończyć. Moja pozycja na koniec listopada to **1 170.49 zł**.

{% include platform-chart.html id="mintos_pln_chart" platform_name="Mintos PLN" data="[32.02, 13.70, 25.51, 21.77, 10.26]" labels='["07.2020","08.2020","09.2020","10.2020","11.2020","12.2020"]' %}

## EvoEstate

Tak jak deklarowałem miesiąc temu - piersze odsetki z tej platformy w grudniu tego roku. W międzyczasie powiększyłem swoją pozycję o dwie dodatkowe inwestycje w Hiszpanii i Portugali. Na koniec listopada na EvoEstate posiadam zainwestowane **353.46 €**.

## EstateGuru

Kolejny debiutant reprezentujący inwestycje w nieruchomości. Chciałbym w najbliższych miesiącach zająć mocniejszą pozycję w tej kategorii. Na koniec listopada na EstateGutu przelałem **245,45 €** i zainwestowałem w 3 różne projekty. Pierwsze odsetki na przełomie grudnia/stycznia.

## Portfolio

Na koniec dorzucam Wam procentowe udziały poszczególnych portali przy przeliczeniu euro na koniec listopada. Nie jestem aktualnie zadowolony z tego rozkładu sił, lecz pracujemy nad tym.

<canvas id="portfolioChart" width="400" height="250"></canvas>
<script>
var ctx = document.getElementById('portfolioChart').getContext('2d');

var data = [{
            data: [10807.50, 4327.00, 1170.49, 1590.82, 1104.59],
            backgroundColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ]
        }]

var options = {
    tooltips: {
        enabled: false
    },
    plugins: {
        datalabels: {
            formatter: (value, ctx) => {
                let sum = 0;
                let dataArr = ctx.chart.data.datasets[0].data;
                dataArr.map(data => {
                    sum += data;
                });
                let percentage = (value*100 / sum).toFixed(1)+"%";
                return percentage;
            },
            color: '#fff',
        }
    }
};

var myDoughnutChart = new Chart(ctx, {
    type: 'doughnut',
    data: {
        datasets: data,
        labels: [
        'Mintos EUR',
        'Crowdestor',
        'Mintos PLN',
        'EvoEstate',
        'EstateGuru'
        ]
    },
    options: options
});
</script>

