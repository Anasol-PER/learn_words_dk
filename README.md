# Learning Danish Words
## Introduction

This tool creates, registers and storages the words that you have read in Danish Language with their english meaning, grammatical type, sound, phoneme and the sentence where it come from and the translation of the complete sentence. 

## Source

- Danish Dictionary
https://ordnet.dk

- English-Danish Dictionary
https://en.bab.la/dictionary/danish-english

## Procedure

A way to read is passing through each word in a sentence, trying to find the meaning of each word and also the tense of the sentence.
For that reason in this tool it is necessary to add the sentence we want to understand as main input.

### Input Files:

- Excel Sheet with specified columns
- ASSCCI Text, where you add the sentence to translate and to register

### Output File:
- Excel Sheet with the words  and properties of the words added

![sheetJPG](https://user-images.githubusercontent.com/52880203/90572036-58986780-e1b3-11ea-8695-4f7faa48e8c2.JPG)

### Steps

 - Modify the path name with the one you have your excel sheet file and text file in line29 .

# 			READ FORMER EXCEL 

# ----------------- P A T H -----------------------------------
PATH_XLS_FILE='C:\\Users\\Ana Maria\\Documents\\DS\\APP_DK_ord\\'
# ----------------- P A T H -----------------------------------

- Modify the name of your excel sheet as the one you have in line 43

book = open_workbook('DK_WORDS_0.xlsx')

- Run the script in an cmd, it will ask you the name of your txt file, where it is the sentence you want to get the words. Write down the file name.
