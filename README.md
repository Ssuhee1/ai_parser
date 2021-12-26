# Welcome to PDF and HTML file parser
Project name : Ai shuree
Founder : Shuree  
Worker : USPM [buya.psh@gmail.com]  
Code writer : B.Sukhbat [1998bsuhe@gmail.com]  
Used language : Linux bash script  

## Introduction
This code can parse pdf and html file by specified rule

## Rule


## Dependecies
1) pdftotext
```
    sudo apt install pdftotext
```

2) html2text
```
    sudo apt install html2text
```

## How to run 
1) Put your file into uploads directory
2) Put ./parser shell in same directory with uploads
3) Change parser shell mode 
```
    chmod +x parser
```
4) Run following script 
```
    ./parser '<filename>' '<parse rule>'
```
    
## Usage example 
```
    rm -rf result* final* ; time ./parser-v1 '1.pdf' 'Part@I@start@roman 1\.@620\.@mid@range (1)@(18)@start-mid@sub'
```