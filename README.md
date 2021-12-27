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
    sudo apt install pdftotext -y
```
2) htmltopdf (A)
```
    pip install pdfkit
```
3) htmltopdf (B)
```
    sudo apt install wkhtmltopdf -y
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
16948 rows data ===> 5 lvl ==> 23m19,789s  
```
    rm -rf result* final* ; time ./parser-v1 '1.pdf' 'Part@I@start@roman 1\.@620\.@mid@range (1)@(18)@start-mid@sub'
```
1219 rows data ===> 5 lvl ==> 2m13,278s  
```
    rm -rf result* final* ; time ./parser-v1 '2.pdf' 'PART@I@start@roman 1\.@67\.@mid@range (1)@(18)@start-mid@sub (z)@mid@abc (i)@mid@lroman'
```
