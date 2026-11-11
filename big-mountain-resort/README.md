# Big Mountain Resort: pricing a lift ticket

A guided capstone. Big Mountain is a ski resort in Montana that prices its
tickets by adding a premium to the market average. The question was whether
that price reflects what the resort offers.

## Approach

1. Clean data on about 330 resorts across the United States.
2. Explore which facilities go with higher ticket prices.
3. Train a model to predict ticket price from facilities, leaving Big Mountain out.
4. Ask the model what Big Mountain's facilities would be priced at elsewhere.

## Result

The model priced Big Mountain at **95.87 dollars** against its actual price of
**81.00**. It also tested changes to the resort. Adding a run and raising the
vertical drop supported a further increase of about 2 dollars a ticket.

## Files

| Path | What it is |
| --- | --- |
| `notebooks/Data_Wrangling_RM.ipynb` | Cleaning the resort data |
| `notebooks/Exploratory_Data_Analysis_RM.ipynb` | What goes with higher prices |
| `notebooks/Preprocessing_and_Training_RM.ipynb` | Comparing models |
| `notebooks/Modeling_RM.ipynb` | The final model and the scenarios |
| `Big Mountain Resort Deck.pdf` | Slides |
| `Big Mountain Resort Strategic Recommendations.pdf` | Written recommendations |

## What I would do differently

The notebooks follow the course template, so the structure is not my own. The
data has ticket prices but no costs or visitor numbers, so the model can say
what the market charges for similar facilities, and it cannot say what price
would earn the most.
