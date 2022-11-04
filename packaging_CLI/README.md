
# DESCRIPTION:
CLI application that takes a string and returns the number of unique characters in the string or text file.

  
  

## HOW TO USE:
Create file, for example ```app.py``` with following content:
```
from unique_characters_counter_Barvynska import main

print(main())
```
  
  

After that run following command in console:

  

```
py app.py --string "Python" 
# 6
``` 
or
```py app.py --file <path/to/file>```

  

### Note: 
Only first string in a file will be processed. Also, when given both ```--string``` and ```--file ``` arguments, ```--string``` will be ignored.
