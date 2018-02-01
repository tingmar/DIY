# Notes--What they forgot to teach you about R

##Set up Github on local shell

```r
pwd 
/Users/tma/Desktop/Training/R_conference  
git clone https://github.com/tingmar/test.git
ls
README.md
```

```r
git remote show origin
```

>>`* remote origin`    
>>`Fetch URL: https://github.com/tingmar/test.git`   
>>`Push  URL: https://github.com/tingmar/test.git`   
>>`HEAD branch: master` 

make some changes on the README.md file and save it and 
then push it to the gitHub

```r
git add -A   
git commit -m "A commit from my local computer"   
git push
```
Reload gitHub repo and the file will be updated there.







Markdown is an **easy to use** format for writing reports. It resembles what you naturally write every time you compose an email. In fact, you may have already used markdown *without realizing it*. These websites all rely on markdown formatting

* [Github](www.github.com)
* [StackOverflow](www.stackoverflow.com)
* [Reddit](www.reddit.com)
