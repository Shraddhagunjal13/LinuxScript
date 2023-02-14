#!/bin/bash

echo "Enter a numner"
read a

echo "Enter a numner"
read b

echo "Addition:"
var=$((a+b))
echo $var
echo "Subtraction:"
var=$((a-b))
echo $var
echo "Multiplication:"
var=$((a*b))
echo $var
echo "Divison:"
var=$((a/b))
echo $var