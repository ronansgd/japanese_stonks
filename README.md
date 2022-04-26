# japanese_stonks

## Bootstrap

### Python environment

Conda is used as environment manager.
To create your env, run from root folder:

> conda env create -f jap_stonk.yml

To add a package, simply add a line to the jap_stonk.yml file,

### Data

Data should be extracted in the `input` folder (its content is .gitignored) such that the path to the train files folder from the project root be `input/jpx-tokyo-stock-exchange-prediction/train_files`.
