# Ride share: demand, an experiment and rider retention

A three part take home challenge for a ride share company.

## Part 1: when is demand highest?

Login times grouped into 15 minute blocks show strong daily cycles. Activity
peaks late at night and in the early morning, most of all on weekends.

## Part 2: design an experiment

Two neighboring cities are split by a toll bridge, so drivers tend to stay on
one side. The company wants to test paying the tolls. My design: assign half
the drivers at random to have tolls repaid for a month, and measure the share
of drivers who serve both cities.

## Part 3: which riders stay?

A model predicts if a rider is still active in their sixth month. It was right
about 75 percent of the time on riders it had not seen. The strongest
predictors were the rider's average rating from drivers, the share of trips
taken on weekdays, and the home city.

Suggestions that follow from it: reward well rated riders, encourage weekday
use, and push for a few trips in the first month.

## What I would do differently

Part 2 names a metric and a split but does not work out how many drivers are
needed to detect a real difference. Part 3 reports what predicts retention,
which is not the same as what causes it. A rider's rating may reflect how
engaged they already are.

## Files

| Path | What it is |
| --- | --- |
| `Ultimate_DS_Challenge.ipynb` | All three parts |
| `ultimate_data_science_challenge.pdf` | The challenge brief |
| `data/` | Login times and rider records supplied with the challenge |
