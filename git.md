# CLDQ

* First step: Logging into Ieng6

<img width="960" alt="스크린샷 2023-02-27 오후 9 48 48" src="https://user-images.githubusercontent.com/66867608/221767321-70914939-cee4-4ffb-98f5-8f22dabc2de8.png">

  Keys pressed : `<up>,<enter>`
  
  It immediately poped the most recent command on my terminal which was ssh. I believe the Ieng6 terminal and my local terminal have different logs despite the fact that I'm typing it in my local terminal.

* Second step: cloning the repository, and getting into the directory

<img width="960" alt="스크린샷 2023-02-27 오후 9 48 18" src="https://user-images.githubusercontent.com/66867608/221767459-ad7a4938-8033-4c35-9e0c-2dc4c99b4244.png">

 Keys pressed : `<up>,<enter>`
 
  At the end of the last practice I typed every command in reverse order so that I won't have to press multiple ups. So it poped the clone command.

<img width="973" alt="스크린샷 2023-02-27 오후 9 47 51" src="https://user-images.githubusercontent.com/66867608/221767635-c0202c89-9fc7-4a82-bb02-0fed69aa4e11.png">

  Keys pressed : `<up>,<up>,<up>,<enter>`
  
 The using the reverse ordered history started to get complicated because I have not considered the fact that the newly typed ones are added to the log, so instead of `<up>,<up>`, I had to type `<up>,<up>,<up>`.
  
* Third step: Running the test and showing it fails

<img width="973" alt="스크린샷 2023-02-27 오후 9 47 33" src="https://user-images.githubusercontent.com/66867608/221767861-44576c41-27b6-434e-aff4-a7a5a69a7d29.png">

  Keys pressed for compilation: `<up>,<up>,<up>,<up>,<up>,<enter>`
  Keys pressed for running: `<Ctrl>+R, java , <enter>`
 
 At this point I gave up on using `<up>` as the commands were piling up pushing commands from previous practices so far behind. So I used `<Ctrl> + r` to find java. But the problem was that it only gave me `javac` not `java` so I had to re-type it and found that I should type `java<space>` to find java command.
 
* Fourth step: Editing the file

<img width="960" alt="스크린샷 2023-02-27 오후 9 50 11" src="https://user-images.githubusercontent.com/66867608/221768652-8f4ff944-d674-4a72-aee2-7b66deb90204.png">

  Keys pressed for opening the file: `vim L, <Tab>, ., <Tab>, <enter>`
  
As I have used `vim` command on other files to practice, I also had to manually type it instead of using `<Ctrl>+R`
  
<img width="960" alt="스크린샷 2023-02-27 오후 9 50 28" src="https://user-images.githubusercontent.com/66867608/221768798-adb56379-7910-4fc5-a2b0-8dfa377472d1.png">

  Keys pressed : `<i>,<click>,<backspace>, 2 , <esc>, :, x, <enter>`
  
* Fifth step: Running test again

<img width="963" alt="스크린샷 2023-02-27 오후 9 46 13" src="https://user-images.githubusercontent.com/66867608/221769081-5933c15f-0b16-494b-9623-7061cd68b595.png">

  Keys pressed : `<Ctrl>+R, javac, <enter>` and `<Ctrl>+R, java, <space>, <enter>`
  
This time I was able to do it fast as I found out that `<space>` can be used to differentiate `javac` and `java`. 
  
* Sixth step: Add, commit, and push

<img width="963" alt="스크린샷 2023-02-27 오후 9 46 27" src="https://user-images.githubusercontent.com/66867608/221769424-d83760ec-e950-4fb2-ba92-436f12cdbf75.png">

  Keys pressed : `git, <Ctrl> + R, a, <enter>` and `git, <Ctrl>+R, c, <enter>`
  
I searched command log files to bring `add` and `commit`.
  
<img width="963" alt="스크린샷 2023-02-27 오후 9 46 38" src="https://user-images.githubusercontent.com/66867608/221769696-b8f1749f-dce3-40c4-95aa-e516c80c421f.png">

  Keys pressed : `git, <Ctrl> + R, p, <enter>` 
  
I used log files again to search `push` using `p`.

