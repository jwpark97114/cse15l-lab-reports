# Command : Grep Report

All the commands are found at 
> https://recipes4dev.tistory.com/157

**Recursive search : -r**

  When we want to search all the files within the target directory, we can use recursive option.
  Command : `grep -r "String" Target-Directory`

  Examples:
  
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
  Command : `grep -n "String" Target-Directory.File.Extension`
  
  Examples:
   
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


  


