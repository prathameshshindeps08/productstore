# productstore
<h1>HELLO DEAR LEARNER!!</h1></p>
<h1>This is github platform...</h1>
<ol>
  <l>PG DAC</l>
  <l>PG DITISS</l>
  <l>PG DBDA</l>
  <l>PG IOT</l>
  <l>PG AI</l>

</ol>

sudo apt update
git clone
sudo apt install git
sudo apt install docker 

https://github.com/Praveerpratap2803/CDAC_All_Mudule_Contents/tree/master/239535_Praveer_Linux/Loops

https://github.com/Madhuram9890/Linux


From exam point of view following commands would be enough i guess:

git init 
git status
git add
git commit -m"the message you want to give during commit"
git push
git clone <url of the GitHub repository you want to clone>
git rebase (if needed)


#!/bin/bash
read -p "Enter the input n " n
for ((i=1;i<=n;i++))
do
            for ((j=1;j<i+1;j++))
            do
                       echo -n "*"
           done
           echo ""

done


#!/bin/bash

read -p " Enter the id number " id

case $id in
	
              1)
              echo " mechanical department "
 ;;
 2)
 echo " civil department "
 ;;
 3)
 echo " entc department "
 ;;
 4)
 echo " cs department "
 ;;
esac


triangle
rows=5
for((i=1;i<=rows;i++))
do
for((j=1;j<=rows-i;j++))
do
echo -n "   "
done
for((j=1;j<=2*i-1;j++))
do
echo -n " * "
done
echo
done


sum=0
for((i=200;i<300;i++))
do
if [$((i%5)) -eq 0] && [$((i%7)) -eq 0];
then
sum=$((sum+i))
fi
done
echo "$sum"


triangle
read -p "Enter the number of rows for the right-angle triangle: " rows

# Use nested loops to display the right-angle triangle pattern
for ((i = 1; i <= rows; i++)); do
  for ((j = 1; j <= i; j++)); do
    echo -n "*"
  done
  echo
done
------------------------------------------------
#!/bin/bash

# Prompt the user to enter the number of rows for the triangle
read -p "Enter the number of rows for the right-angle triangle: " rows

# Use nested loops to display the right-angle triangle pattern with numbers
for ((i = 1; i <= rows; i++)); do
  for ((j = 1; j <= i; j++)); do
    echo -n "$j"
  done
  echo
done
----------------------------------------------------
#!/bin/bash

# Prompt the user to enter the number of rows for the triangle
read -p "Enter the number of rows for the right-angle triangle: " rows

# Use nested loops to display the right-angle triangle pattern with repeating numbers
for ((i = 1; i <= rows; i++)); do
  for ((j = 1; j <= i; j++)); do
    echo -n "$i"
  done
  echo
done
-----------------------------------------------------
#!/bin/bash

# Prompt the user to enter the number of rows for the triangle
read -p "Enter the number of rows for the right-angle triangle: " rows

current=1

# Use nested loops to display the right-angle triangle pattern with increasing numbers
for ((i = 1; i <= rows; i++)); do
  for ((j = 1; j <= i; j++)); do
    echo -n "$current "
    current=$((current + 1))
  done
  echo
done

 
