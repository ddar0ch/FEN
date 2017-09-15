#!/bin/zsh

toCut=
for file in [[:digit:]]*
do 
    toCut="${#${file#*[[:alpha:]]}}-1"
    mv $file ${file: -${toCut}}
done
