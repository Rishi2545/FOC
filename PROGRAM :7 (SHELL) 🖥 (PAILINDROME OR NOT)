#!/bin/bash
echo "enter a number"
read n
sum=0
temp=$n
while [ $n -gt 0 ]
do
        r=$((n%10))
        sum=$((r+sum*10))
        n=$((n/10))
done
if [ $temp -eq $sum ]
then
        echo "palindrome"
else
        echo "not a palindrome"
fi
