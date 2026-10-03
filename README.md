# xG-model-football
Every shot in football (not American) has some probability of becoming a goal, based on things like distance from goal, angle, whether it's a header, how many defenders are in the way, etc. xG assigns each shot a probability (0 to 1) of scoring. This project is investigating into the components that make this model and then building one myself.

# Expected Goals (xG) Model – Football

Every shot in football (soccer) has some chance of becoming a goal, depending on things like how far it is from goal, the shooting angle, and the situation it was taken in. An **Expected Goals (xG)** model gives each shot a probability between 0 and 1 of being scored.

This project explores how xG models work and builds one from scratch in Python.

**Status:** In progress (started July 2026)

## What I Did

This is a solo project. So far I have:

- **Researched how xG models work:** studied the statistical and machine learning ideas behind xG and how analysts measure shot quality.
- **Built a training dataset:** retrieved historical match and shot data from past seasons and cleaned it into a dataset ready for modeling.
- **Built a predictive model:** I'm building and refining a model that estimates goal probability from shot location, angle, and situational features.

## Approach

1. **Data:** Historical shot data from [DATA SOURCE – e.g. StatsBomb Open Data], covering [SEASONS / COMPETITIONS].
2. **Cleaning:** [What you did – e.g. removed penalties, handled missing values, standardized pitch coordinates.]
3. **Features:**
   - Distance from goal
   - Shot angle
   - Situational features: [e.g. header vs. foot, open play vs. set piece]
4. **Model:** [MODEL – e.g. logistic regression in scikit-learn]
5. **Evaluation:** [METRIC – e.g. log loss or ROC AUC on held-out data. Delete this step if you haven't evaluated yet.]

## Results
Still in progress

![Chart description](path/to/chart.png)

## Tech Stack

- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Repository Structure

- `data/` – shot data used for training
- `notebooks/` – data cleaning, exploration, and modeling notebooks

## Running the Project

```
pip install -r requirements.txt
jupyter notebook
```

Then open the notebooks in the `notebooks/` folder.

## Next Steps

- [e.g. Add more situational features, like defender positions]
- [e.g. Compare my model's xG to published xG values]
- [e.g. Try a tree-based model and compare results]
