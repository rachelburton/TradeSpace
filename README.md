# OS4 - Model

## Overview

This notebook contains the model for OS4, which is designed to evaluate the performance and cost of different system architectures for a shared autonomous vehicle (SAV) system. The model considers various factors such as passenger throughput, availability, passenger volume, average wait time, and system cost. It uses a multi-attribute utility function to assess the overall utility of each system architecture.

## Software Environment

This notebook requires the following Python libraries:

* pandas
* numpy
* matplotlib
* warnings
* itertools
* scipy
* os
* math
* plotly

You can install these libraries using `pip`:
bash pip install pandas numpy matplotlib scipy plotly
## Hardware

This notebook can be run on any machine with sufficient resources to execute the code. It is recommended to use Google Colab for running this notebook, as it provides a free and convenient environment with pre-installed libraries.

## Data

The notebook uses an Excel file named `SAU_input_multiples.xlsx` as input. This file contains data for different attributes of the SAV system, including passenger throughput, availability, passenger volume, and average wait time. The file also contains data for the weights assigned to each attribute in the multi-attribute utility function. Make sure to download the latest version of this file from the Drive and upload it to the Colab environment.

## Order of Execution

1. Import the necessary libraries.
2. Define functions for calculating the multi-attribute utility, intermediate variables, average wait time, availability, passenger throughput, and passenger volume.
3. Import data from the Excel file.
4. Calculate best-fit lines for the utility functions of each attribute.
5. Plot the data and the best-fit lines.
6. Calculate the multi-attribute utility for different system architectures.
7. Create vectors for the system design, fleet design, vehicle design, and bike design.
8. Calculate the attributes for each system architecture using the `calculate_attributes` function.
9. Analyze the results and draw conclusions.

## Usage

To use the notebook, follow these steps:

1. Open the notebook in Google Colab.
2. Upload the `SAU_input_multiples.xlsx` file to the Colab environment.
3. Run the cells in the notebook in sequential order.
4. Analyze the results and draw conclusions.

## Contributing

Contributions to this notebook are welcome. If you find any errors or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This notebook is licensed under the MIT License.
