# The Smoking Gun: Unveiling GPT-4’s memorisation of Polish Texts and Implications for Copyright Infringement

## Overview
This repository consists of part of the code used for my Master's thesis. The data could not be shared due to its copyrighted nature. 
To access the dataset that I used email me at budzikwjoanna@gmail.com

## Dataset preparation

Data was collected for Polish books. However the code can be appled to other languages. Remember to change the language of tokenization. 
The dataset for test and baseline were prepared by legally accessing different books and poems, through kindle subscriptions and creating a dataset from the furst few pages, name of the literary work and the author.
Test dataset is created out of books that were released before gpt-4 model was created and baseline data is created out of literary works from 2024 - after gpt-4 was traied.

## Books Processing with GPT Models

This code is designed to automate the process of generating text prompts from book excerpts and analyzing the results using OpenAI's GPT models. 
The aim is to facilitate whether gpt-4 memorises Polish data. There are visualisations comparing the test and baseline. There is also a statistical test checking the significance of the results.

## Installation

To run this notebook, ensure you have Python installed along with the necessary libraries. You can install all required dependencies with the following command:

```bash
pip install pandas openai matplotlib

