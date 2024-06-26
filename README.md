# Ten Million Row Challenge

I have generated a [(CSV) dataset](./data/measurements.csv) with ten million rows.
Each row in the dataset represents a single temperature measurement of a weather
station. There are multiple weatherstations in the dataset.

Example:

```csv
Sabirabad;11.6264
Cagnes-sur-Mer;-2.6981
Ekerö;-0.0331
Diabigué;1.6713
Pāiker;28.2705
Seddouk Oufella;25.7646
Kawashiri;35.8271
Bhānpura;16.1663
Colwood;-3.4679
Sabunçu;1.5455
Āvadi;8.3049
```

Your assignment, should you choose to accept it, is to aggregate all measurements,
and provide a minimum, average and maximum temperature for each station. Your program
should output only one single line of JSON per station on `stdout`, in the
following format:

```json
{ "station": "station name", "min": -12.3, "avg": 34.5, "max": 45.6 }
```

The station name must be exactly as it appears in the dataset, and all measurements
must have a significance of only _one single_ decimal.

Although the primary objective is to have a functionally working solution with correct
output, the secondary objective is to make it as fast as possible. Processing times
below one second should be easily achievable.

## Checkout

Please note that this repo uses Git LFS in order to store the dataset file. Before you
clone this repository please make sure you have Git LFS installed. You can find some
[instructions here](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage).

## Organisation

Pick any programming language and platform you like. Do it solo, as a pair or group.
We have 90 minutes to write code, after that each team will do a small (only 5 minutes!)
presentation with:

- demo of the solution
- conceptual overview of the solution (**no** in-depth code walk-throughs)
- what did your team find most challenging?

I would love pull requests which add a link to your solution's Github repo in this README,
in the list below:

## Solution references

Here is a list of contributor solutions:

- a link to your solution here?
