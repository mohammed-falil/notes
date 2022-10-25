"# bash-script-notes" 
 ## : (COLON) Operator
 
echo "value for variable before assigning $variabe"   

variable=${variable:-superman}    

echo "Value for variable after assigning $variable"   

echo "Now changing the value with checking whether it is null"  

variable=spiderman  

echo "changing the variable which has $variable to superman again"  

variable=${variable:-superman}  

echo "Printing the variable after checking : $variable"  
