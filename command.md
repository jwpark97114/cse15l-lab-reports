# **Command : Find Report**


# Pattern search :  `*`

  When it come to searching for files that start with certain strings, we can use `*` to find anything that matches the pattern.
  
 * Command : `find Target-Directory "String*"`
  
 * Source: https://recipes4dev.tistory.com/156
  
 * Examples:
  
> First input : `find . -name "Bahama*"`
> 
> Output :
> <img width="581" alt="스크린샷 2023-03-13 오후 7 11 37" src="https://user-images.githubusercontent.com/66867608/224874884-0cb7dce2-fe1e-4678-a4a5-55528a88e0e1.png">
> 
> 
> Second input : `find . -name "Athe*"`
> 
> Output : <img width="581" alt="스크린샷 2023-03-13 오후 7 13 00" src="https://user-images.githubusercontent.com/66867608/224875033-b200045d-931c-494a-a54d-ae4b1b834169.png"> 


# Delete the found files :  `-delete`

  Surprisingly I have realized that the find command can directly used to delete the files found with the command using `-delete` at the end of the command. It can be used with `*` to delete all the files that matches the pattern, which seems to be a really convenient feature.
  
*  Command : `find Target-Directory "String" -delete`
  
*  Source: https://recipes4dev.tistory.com/156
  
*  Examples:
   
> First input : `find . "Athens-W*" -delete`
> 
> Output :
> <img width="581" alt="스크린샷 2023-03-13 오후 7 17 58" src="https://user-images.githubusercontent.com/66867608/224875745-2f64144c-f821-462f-9bdb-5e5e7ce06c7b.png">
> 
> Second input : `find . "Athens*" -delete`
> 
> Output : 
> <img width="581" alt="스크린샷 2023-03-13 오후 7 19 17" src="https://user-images.githubusercontent.com/66867608/224875906-2d95e3e5-bee2-40f8-b604-874dab59eb41.png">



# Find directory or file only : `-type`

*  When you have to differenciate file and directory you can use `-type d` and `-type f` to find directories and files respectively.
  
*  Command : `find Target-Directory "String" -type [d or f]`
  
*  Source: https://recipes4dev.tistory.com/156
  
> First input : `find . -name "Baha*" -type f`
> 
> Output :
> <img width="581" alt="스크린샷 2023-03-13 오후 7 35 28" src="https://user-images.githubusercontent.com/66867608/224878187-cd419205-eb90-4ec0-b989-48ac27d02829.png">
> 
> Second input : `find . -name "Baha*" -type d`
> 
> Output : 
> <img width="581" alt="스크린샷 2023-03-13 오후 7 37 02" src="https://user-images.githubusercontent.com/66867608/224878413-23741236-3b46-45da-bfc7-92d4dc875071.png">


# Find empty directory or file that has zero size : `-empty`

*  If you want to find directories or files that have nothing inside whether because it is not supposed to be empty or it has to be empty, you can use this command to detect them.
  
*  Command : `find Target-Directory -empty`
  
*  Source: https://recipes4dev.tistory.com/156
  
> First input : `find . -empty -type f`
> 
> Output :
> <img width="581" alt="스크린샷 2023-03-13 오후 7 45 54" src="https://user-images.githubusercontent.com/66867608/224879827-b53f0a60-f3b9-4a18-8f9d-54b37ebf0a3b.png">
> 
> Second input : `find . -empty -type d`
> 
> Output :
> <img width="581" alt="스크린샷 2023-03-13 오후 7 46 34" src="https://user-images.githubusercontent.com/66867608/224879936-46be5312-7220-4bb6-870f-7c3041b647f5.png">

 

