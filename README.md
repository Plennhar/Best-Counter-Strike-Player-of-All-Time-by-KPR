# Best Counter-Strike Players of All Time by KPR
This project ranks Counter-Strike players across 2004 to 2025 by building a yearly performance model based on KPR. For each year, a list of prize-pooled tournaments was compiled, and player KPR data was gathered where available. Players were included only if they had data from at least two tournaments. A prize-pool-weighted mean KPR was then calculated for each player, with missing tournament values imputed using the mean KPR from the relevant event. Each qualified player's Adjusted Weighted KPR was then transformed into an over/underperformance metric (Performance Score), by comparing the result to the mean Adjusted Weighted KPR across all qualified players from that year.  Final all-time totals are then calculated with a squared-sum method, using the sum of squared yearly Performance Scores rather than a simple linear sum. This approach gives extra weight to truly elite peak seasons while still rewarding repeated high-level play, creating a more balanced measure of greatness across both dominance and longevity. The squared-sum method was chosen to reflect the assumption that four Performance Score +0.05 seasons should be valued the same as one Performance Score +0.10 season.

## 2025 List
Place | Country | Nickname | Score
:---: | :---: | :--- | :---:
1 | 🇷🇺 | donk | 0.11
2 | 🇫🇷 | ZywOo | 0.082
3 | 🇷🇺 | m0NESY | 0.069
4 | 🇷🇺 | sh1ro | 0.055
5 | 🇹🇷 | XANTARES | 0.053
6 | 🇹🇷 | Wicadia | 0.045
7 | 🇷🇺 | kyousuke | 0.044
8 | 🇲🇳 | senzu | 0.044
9 | 🇪🇪 | ropz | 0.043
10 | 🇧🇦 | NiKo | 0.04
11 | 🇰🇿 | molodoy | 0.038
12 | 🇮🇱 | Spinx | 0.034
13 | 🇺🇸 | ELiGE | 0.034
14 | 🇨🇦 | Twistzz | 0.033
15 | 🇸🇰 | frozen | 0.033
16 | 🇸🇪 | REZ | 0.031
17 | 🇲🇳 | 910 | 0.03
18 | 🇧🇷 | kscerato | 0.03
19 | 🇨🇿 | PR | 0.028
20 | 🇺🇦 | B1t | 0.028
21 | 🇭🇺 | torzsi | 0.027
22 | 🇹🇷 | woxic | 0.024
23 | 🇷🇴 | iM | 0.023
24 | 🇮🇱 | Nertz | 0.019
25 | 🇺🇦 | w0nderful | 0.019

## All Time List (2005 - 2025)
Place | Country | Nickname | Score | 1st place | 2nd place | 3rd place | Years above average
:---: | :---: | :--- | :---: | :---: | :---: | :---: | :---:
1 | 🇸🇪 | f0rest | 0.086 | 4 | 1 | 2 | 18
2 | 🇵🇱 | neo | 0.074 | 1 | 2 | 0 | 11
3 | 🇸🇪 | GeT_RiGhT | 0.065 | 3 | 2 | 1 | 12
4 | 🇺🇦 | s1mple | 0.041 | 4 | 1 | 1 | 12
5 | 🇫🇷 | ZywOo | 0.038 | 2 | 5 | 0 | 9
6 | 🇧🇦 | NiKo | 0.028 | 0 | 2 | 2 | 15
7 | 🇷🇺 | donk | 0.024 | 2 | 0 | 0 | 5
8 | 🇩🇰 | dev1ce | 0.024 | 0 | 1 | 1 | 13
9 | 🇸🇪 | dsn | 0.022 | 0 | 1 | 0 | 7
10 | 🇦🇹 | gore | 0.021 | 1 | 0 | 0 | 5
11 | 🇸🇪 | flusha | 0.02 | 1 | 0 | 0 | 8
12 | 🇵🇱 | TaZ | 0.02 | 0 | 0 | 1 | 8
13 | 🇧🇷 | cogu | 0.02 | 0 | 1 | 0 | 4
14 | 🇧🇷 | coldzera | 0.018 | 2 | 0 | 0 | 10
15 | 🇵🇱 | snax | 0.018 | 0 | 0 | 1 | 10
16 | 🇺🇦 | Edward | 0.018 | 0 | 1 | 0 | 11
17 | 🇸🇪 | olofmeister | 0.018 | 1 | 0 | 0 | 7
18 | 🇫🇷 | shox | 0.017 | 0 | 0 | 0 | 10
19 | 🇵🇱 | pashaBiceps | 0.017 | 0 | 0 | 0 | 9
20 | 🇸🇪 | JW | 0.016 | 0 | 0 | 0 | 11
21 | 🇩🇰 | dupreeh | 0.016 | 0 | 0 | 1 | 11
22 | 🇫🇷 | kennyS | 0.015 | 0 | 0 | 0 | 10
23 | 🇺🇸 | brax | 0.015 | 0 | 1 | 0 | 5
24 | 🇷🇺 | m0NESY | 0.015 | 0 | 0 | 2 | 7
25 | 🇫🇷 | Happy | 0.015 | 0 | 1 | 0 | 6

## Feedback
I'm looking for ways to improve this model, even if slightly, so if you have an idea for how I could do that, let me know. I'm especially interested in any ways of obtaining KPR data from between 2001 and 2003, or any other player-specific performance data.
