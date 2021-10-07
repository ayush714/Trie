# Trie  

Welcome to my repo, I have built a trie system that can do the following tasks:- 
- Add keyword to trie
- Delete a keyword from trie
- Search for a keyword in trie [True/False]
- Return list of autocomplete suggestion based on an input prefix
- Display the trie

This trie is available as a package or a CLI tool, you can download this trie package using this command:- 

`pip install triefunc==0.0.1` 

## Using Triefunc 

``` 
from trie import main  
main()
``` 

and run this file using `python NAMEOFTHEFILE --populate "Ayush, Singh"`

Here's how you can use this? 

First command should be to populate a trie uisng --populate "ARGUMENT", you can add as many words over here make sure after every command, you have some space.  
It will ask you whether you want to continue or not, you can enter `T`.  

***It will ask:-*** 

Enter the function you want to perform: --insert

Enter the parameters you want to pass for the function: Aryan

Enter the function you want to perform: --autocomplete   
Enter the parameters you want to pass for the function: A

Enter the function you want to perform: --delete  
Enter the parameters you want to pass for the function: Ayush 

Enter the function you want to perform: --display   
Enter the parameters you want to pass for the function:

Enter the function you want to perform: --search   
Enter the parameters you want to pass for the function: Ayush

You can watch the video https://1drv.ms/u/s!Av5zWn1bWPXagSXSHAeAa_0Hafzh?e=VbfyeA. 
