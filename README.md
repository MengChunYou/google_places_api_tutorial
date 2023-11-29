# google_places_api_tutorial

This repository contains Python code and slides for a tutorial on using the Google Places API (New), focusing on Place Details (New) and Text Search (New).

The tutorial was conducted at @NTUDAC on Nov 25, 2023, with materials written in Traditional Chinese.

## Table of Contents

- [google\_places\_api\_tutorial](#google_places_api_tutorial)
  - [Table of Contents](#table-of-contents)
  - [Repository Structure](#repository-structure)
  - [Required Packages](#required-packages)
  - [Usage](#usage)

## Repository Structure

```plaintext
root/
 ├── notebook/      
 │    └── Google_Places_API_Tutorial.ipynb
 ├── output/          
 │    └── cafe.csv
 ├── slide/   
 │    └── Google_Places_API_Tutorial_Slide.pdf
 ├── .gitignore
 ├── requirements.txt
 └── README.md     
```

- `slide/`: This directory contains presentation slide related to the tutorial.
- `notebook/`: This directory contains the Jupyter Notebook tutorial file.
- `output/`: This directory contains output file generated during the tutorial.

## Required Packages

- os
- json
- requests
- pandas
  
Download the required packages by running the following command in the terminal:

```plaintext
pip3 install -r requirements.txt
```

## Usage

In the code, replace the `my_key` with your obtained API key:

```plaintext
my_key = "your_key_123456" 
```
