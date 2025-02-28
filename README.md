# SPRM

## Introduction

Welcome to the SPRM project repository. In this repository, you will find the code and supplementary materials related to our research.

## Installation
To set up the project locally, please follow the instructions below:

1. Clone the repository:
    ```sh
    git clone https://github.com/WeepCat/SPRM.git
    cd SPRM
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

After setting up the environment, you can run the experiments and analysis scripts as follows:

1. **Data Preparation:**
    Make sure you have the necessary datasets downloaded and preprocessed. You can find the data preparation scripts in the `data/` directory.

2. **Running Experiments:**
    Execute the main experiment scripts to replicate our results:
    ```sh
    python experiments/score_analysis.py
    ```

3. **Evaluation:**
    Evaluate the model performance using the provided evaluation scripts:
    ```sh
    python evaluation/evaluate.py
    ```

## Results

The main results of our experiments are documented in the paper. For convenience, you can also find the result logs and output files in the `results/` directory of this repository.

## Contributing

We welcome contributions from the community. If you have suggestions, bug reports, or improvements, please open an issue or submit a pull request.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

