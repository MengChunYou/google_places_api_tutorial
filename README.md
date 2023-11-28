# google_places_api_tutorial

This repository contains Python code and slides for a tutorial on using the Google Places API (New), focusing on Place Details (New) and Text Search (New).

The tutorial was conducted at @NTUDAC on Nov 25, 2023, with materials written in Traditional Chinese.

## Table of Contents
- [Repository Structure](#repo-structure)
- [Required Packages](#required-packages)
- [Usage](#usage)

## Repository Structure
```plaintext
├── notebook/        
│   ├── Google_Places_API_Tutorial.ipynb
├── output/            
│   ├── cafe.csv
├── slide/     
│   ├── Google_Places_API_Tutorial_Slide.pdf
├── .gitignore
├── README.md       
```

- `slide/`: This directory contains presentation slides related to the tutorial.
  - [Google_Places_API_Tutorial_Slide.pdf](slide/Google_Places_API_Tutorial_Slide.pdf)

- `notebook/`: This directory contains the Jupyter Notebook tutorial file.
  - [Google_Places_API_Tutorial.ipynb](notebook/Google_Places_API_Tutorial.ipynb)

- `output/`: This directory contains output files generated during the tutorial.
  - [cafe_details.csv](output/cafe_details.csv)

## Required Packages
```plaintext
os
json
requests
pandas
```

## Usage

In the code, replace the `my_key` with your obtained API key:
```plaintext
my_key = "your_key_123456" 
```



