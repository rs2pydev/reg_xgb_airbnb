## This repo contains regression analysis of AirBnB listing prices with XGBoost algorithm.

## Important Information:

- To create a virtual Python environment using `conda`, use either of the following: 

    - Use the `xgb_env.yml` file to create a `conda` environment called `xgb` using `conda env create -f environment.yml -n xgb`.

    - Alternatively, use the following `conda` commands to create the `xgb` environment manually:
        - `conda create --name xgb python=3.9`
        - `conda activate xgb`
        - `conda deactivate base && conda activate xgb`
        - `conda install ipykernel`
        - `conda install -c conda-forge xgboost pandas scikit-learn plotnine seaborn`
        - `conda install -c conda-forge pyarrow # Optional step`
        - `python3 -m pip install optuna plotly nbformat`

- To use Google Colab instead of a local virtual environment, uncomment the code cell under section **0. Setup Google Colab Environment**.  
