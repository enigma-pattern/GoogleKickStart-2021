# [GoogleKickStart 2021](https://codingcompetitions.withgoogle.com/kickstart) ![Language](https://img.shields.io/badge/language-Python-orange.svg) [![License](https://img.shields.io/badge/license-MIT-blue.svg)](./LICENSE) ![Progress](https://img.shields.io/badge/progress-4%20%2F%204-ff69b4.svg)

Python solutions of Google Kick Start 2021. Solution begins with `*` means it will get TLE in the largest data set (total computation amount > `10^8`, which is not friendly for Python to solve in 5 ~ 15 seconds). A problem was marked as `Very Hard` means that it was an unsolved one during the contest and may not be that difficult.

* [Kick Start 2020](https://github.com/kamyu104/GoogleKickStart-2020)
* [Round A](https://github.com/kamyu104/GoogleKickStart-2021#round-a)

## Round A
| # | Title | Solution | Time | Space | Difficulty | Tag | Note |
|---| ----- | -------- | ---- | ----- | ---------- | --- | ---- |
|A| [K-Goodness String](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068cca3)| [Python](./Round%20A/k_goodness_string.py)| _O(N)_ | _O(1)_ | Easy | | String |
|B| [L Shaped Plots](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068c509)| [Python](./Round%20A/l_shaped_plots.py) | _O(R * C)_ | _O(min(R, C))_ | Easy | | DP |
|C| [Rabbit House](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068cb14)| [Python](./Round%20A/rabbit_house.py)| _O(R * C)_ | _O(R * C)_ | Medium | | Bucket Sort, BFS |
|D| [Checksum](https://codingcompetitions.withgoogle.com/kickstart/round/0000000000436140/000000000068c2c3)| [Python](./Round%20A/checksum.py) | _O(N^2)_ | _O(N^2)_ | Hard | | MST, Prim's Algorithm |