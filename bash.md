"# bash-script-notes" 
 ## : (COLON) Operator

### Explanation:  

#### This oeprator is mainly used to check whether the value alread present in the variable,  

if variable present -> No change of the new value.  
else if value Not Present ->  Assign it to a new  a value.   

#Example: 
 
>echo "value for variable before assigning $variabe"   

>variable=${variable:-superman}    

>echo "Value for variable after assigning $variable"   

>echo "Now changing the value with checking whether it is null"  

>variable=spiderman  

>echo "changing the variable which has $variable to superman again"  

>variable=${variable:-superman}  

>echo "Printing the variable after checking : $variable"  

## CheatSheet : 

> https://devhints.io/bash

## Print command inside echo on the same line:

> echo "Operating System: " $(uname)  

> echo "Operating System: " \`uname\`
