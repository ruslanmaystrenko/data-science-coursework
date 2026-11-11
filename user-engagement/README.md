# User engagement: who becomes a regular user?

A take home challenge. Given about 12,000 sign ups and their login history,
find what predicts an adopted user, defined as someone who logged in on three
separate days within one week.

## Approach

1. Work out who counts as adopted from the login records.
2. Build features on how and when each user signed up and how they logged in.
3. Train a classifier and read which features matter.

## Result

About 14 percent of users were adopted. The model scored 99 percent accuracy,
and total visits was by far the strongest predictor, followed by account age
and login streaks. Sign up source and marketing settings mattered very little.

## What I would do differently

That 99 percent is too good, and the reason is simple. Adoption is defined by
how often someone logs in, and the strongest inputs also count logins. The
model is partly restating the definition. A more useful version would use only
what is known in a user's first week, and ask who goes on to adopt later. That
is the question a product team can act on.

## Files

| Path | What it is |
| --- | --- |
| `Relax_Challenge_Notebook.ipynb` | The full analysis |
| `relax_data_science_challenge.pdf` | The challenge brief |
| `data/` | The two tables supplied with the challenge |
