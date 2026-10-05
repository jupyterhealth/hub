# Tutorial: Plot a patient's glucose data

In this tutorial, you'll open a short notebook on the Hub, load a patient's continuous glucose monitoring (CGM) data from the Exchange, and plot their typical day.
It takes about 5 minutes.

You'll need an Exchange account that belongs to an organization with a study.
See [Log in and launch a session](log-in.md).

## Open the notebook

Click this button:

{button}`Open the tutorial on the Hub <https://jupyter-health.2i2c.cloud/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fjupyterhealth%2Fjupyterhealth-hub-docs&urlpath=lab%2Ftree%2Fjupyterhealth-hub-docs%2Fnotebooks%2Ftutorial.ipynb&branch=add%2Fsimple-tutorial>`

Log in if asked.
The Hub copies this documentation's repository into a `jupyterhealth-hub-docs/` folder in your home directory and opens `notebooks/tutorial.ipynb`.

## Run the notebook

Run each cell in order with {kbd}`Shift+Enter`:

1. The first cell lists the studies you can access.
2. Replace `<STUDY_ID>` with one of those IDs and run the cell. You'll see the patients in that study.
3. Replace `<PATIENT_ID>` with one of those IDs and run the cell. You'll see the patient's first glucose readings. If the table is empty, pick another patient.
4. The last cell plots the patient's glucose by hour of day.

## Stop your server

Choose {menuselection}`File --> Hub Control Panel --> Stop My Server`.
Your copy of the notebook stays in `jupyterhealth-hub-docs/` for next time.

## Next steps

- [Explore your data](run-an-analysis.md) to write these steps yourself from a blank notebook.
- Try the [full CGM demo](https://jupyterhealth.github.io/demos/researcher-view-cgm/) for glucose metrics, more plots, and sleep data.
