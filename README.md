# CrossNELP's Data parser

Parse raw data from NCBI Blastp to pair-wise similarity matrices stored in csv 

## Installation

- Clone the repository
- Make sure you have JDK 1.7 or above installed

## Usage

- Put hitTable.csv and alignment.txt in ```Parser/protein data/layer_name/protein_name/```
- Navigate to src/Parser/driver.java
- Run the main method, the result will be in ```Parser/Result/layer_name/protein_name-layer_name.csv```
