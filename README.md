# japanese_stonks

## Bootstrap

### Python environment

Conda is used as environment manager.
To create your env, run from root folder:

> conda env create -f jap_stonk.yml

To update the .yml file after adding a package, run:

> conda env export > jap_stonk.yml

### Data

Data should be extracted in the `input` folder (its content is .gitignored) such that the path to the train files folder from the project root be `input/jpx-tokyo-stock-exchange-prediction/train_files`.
