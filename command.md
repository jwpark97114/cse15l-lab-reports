# Command : Grep Report

As I could not copy from my terminal for reasons I do not understand, I took screenshots for the outputs.

**Recursive search : -r**

  When we want to search all the files within the target directory, we can use recursive option.
  
 * Command : `grep -r "String" Target-Directory`
  
 * Source: https://recipes4dev.tistory.com/157
  
 * Examples:
  
> First input : `grep -r Lucayans .`
> 
> Output :
> ![1](https://user-images.githubusercontent.com/66867608/218648126-82006f63-e6ce-4609-8b52-b0866d8bed89.png)
> 
> Second input : `grep -r Horseshoe .`
> 
> Output : 
> <img width="1486" alt="스크린샷 2023-02-13 오후 8 53 36" src="https://user-images.githubusercontent.com/66867608/218648769-e988d366-03ed-46d8-a516-7ba110e3639d.png">


**Print line numbers : -n**

  If you need at which line the target string is, you can use `-n` command.
  
*  Command : `grep -n "String" Target-Directory/File.Extension`
  
*  Source : https://recipes4dev.tistory.com/157
  
*  Examples:
   
> First input : `grep -rn Lucayans .`
> 
> Output :
> ![3](https://user-images.githubusercontent.com/66867608/218649337-655a4d21-eb92-4d49-9aa1-9cb21979238e.png)
> 
> Second input : `grep -rn Horseshoe .`
> 
> Output : 
> <img width="1486" alt="스크린샷 2023-02-13 오후 8 54 55" src="https://user-images.githubusercontent.com/66867608/218649390-e9e38065-d9b9-4d5f-b712-48b18500b112.png">


**Find patterns with numbers within certain range : [0-100]**

*  If you want to find a pattern with numbers at the end, like "page 160" in our data files, you can use the following commands.
  
*  Command : `grep 'String [0-100]' Target-Directory/File.Extension`
  
*  Source : https://recipes4dev.tistory.com/157
  
> First input : `grep 'page [0-100]' written_2/travel_guides/berlitz2/Berlin-WhatToDo.txt`
> 
> Output :
> ![5](https://user-images.githubusercontent.com/66867608/218650157-62822872-9db8-484c-b15f-a66866174995.png)
> 
> Second input : `grep 'page [0-150]' written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt`
> 
> Output : 
> ![6-2](https://user-images.githubusercontent.com/66867608/218651172-a97e3e81-e6e0-4980-8964-e2bb3354f597.png)


**Find string at the start of lines : ^**

*  If you want to check strings at the start of lines, use
  
*  Command : `grep "^String" Target-Directory/File.Extension`
  
*  Source : https://recipes4dev.tistory.com/157
  
> First input : `grep "^Ho" written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt`
> 
> Output :
> ![7](https://user-images.githubusercontent.com/66867608/218652812-63d4692b-9e1b-4fc3-8433-9d9b352cde2f.png)

> 
> Second input : `grep "^What" written_2/travel_guides/berlitz2/Nepal-WhatToDo.txt`
> 
> Output :
> ![8](https://user-images.githubusercontent.com/66867608/218652831-3e539eea-b06d-40ba-9066-1dd2da38d920.png)
 

