# GW Open Data Workshop 2022

My answers for the Challenge. I hope they're somewhat correct, but I won't rely on it too much!

## Challenge 1

> code in *mychallenge_12.ipynb*

Sampling rate is 4096.0 Hz.

Duration is 128.0 s.

There is a merger at $t=2.97 s$.

## Challenge 2

> code in *mychallenge_34a.ipynb*

There is a merger at $t=-14.6 s$.

Matched SNR is $18.55$.

## Challenge 3

> code in *mychallenge_34a.ipynb*

There is a signal at $t \simeq 2483.97$  with SNR $\sim 26.65$.

## Challenge 4

> code in *mychallenge_34a.ipynb* & *mychallenge_4b.ipynb*

Both detector agree on these **gravitational waves**:

| H1 time | H1 SNR | H1 mass | L1 time | L1 SNR | L1 mass |
| :-: | :-: | :-: | :-: | :-: | :-: |
|1204.71| 39.65 | 22 | 1204.74 | 52.58 | 22 |
|1638.17| 32.04 | 17 | 1638.18 | 38.06 | 17 |
|2483.96| 26.64 | 10 | 2483.96 | 29.61 | 10 |
|2995.34| 10.62 | 32 | 2995.34 |  8.83 | 32 |
|3319.26| 13.7  | 36 | 3319.25 | 13.94 | 35 |

I list the following **glitches**:

| detector | time |
| :-: | :-: |
| L1 |196.1 |
| H1 | 981.9 |
| H1 | 987.6 |
| H1 | 998.8 |

The spectrograms of gws and glitches can be found in notebook *mychallenge_34a.ipynb*.

As for the **posterior analysis**, it has been performed in notebook *mychallenge_4b.ipynb*.

| time (H1) | SNR (H1 & L1) | matched filtering mass | posterior mass |
| :-: | :-: | :-: | :-: |
|1204.71| 39.65 52.58 | 22 | $$21.8^{+1.61}_{-1.57}$$ |
|1638.17| 32.04 38.06 | 17 | $$15.97^{+1.57}_{-1.41}$$ |
|2483.96| 26.64 29.61 | 10 | $$8.78^{+1.68}_{-1.20}$$ |
|2995.34| 10.62  8.83 | 32 | $$30.75^{+1.62}_{-1.39}$$ |
|3319.26| 13.7  13.94 | 36 | $$34.41^{+1.65}_{-1.53}$$ |

***

*coder*: Barone Francesco Pio  |   git@[baronefr](http://github.com/baronefr)
<br>MSc in *Physics of Data*, University of Padua, AY 2021/22