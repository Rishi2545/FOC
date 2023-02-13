#!/bin/bash
echo "enter number of students: "
read n
a=1
for((a=1;a<=n;a++))
do
        echo "enter student name: "
        read student
        echo "english marks"
        read english
        echo "maths marks"
        read maths
        echo "science marks"
        read science
        sum=$(($english+$maths+$science))
        per=$((100*$sum/300))
        echo "total=" $sum
        echo "percentage=" $per
done
