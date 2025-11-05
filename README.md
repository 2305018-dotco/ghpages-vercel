Q3) analysis , Evaluate
VM => mysql: create database , create table , insert into , select * 
‘Host machine => create a form -> index.html & upload it on github , deploy it using vercel ( git commands ) 
1.	Create folder in C : ghpages-vercel
2.	Open in vs code
3.	Create file index.html
4.	Create  a repository => ghpages-vercel
5.	Gitbash:
Commands:
1.	To get into C: cd ..
2.	cd
3.	cd ghpages-vercel
4.	to show the index.html file exist in folder: ls
5.	initialize empty git repository: git init
6.	master: git add *
7.	git config --global user.email 2305018@fragnelcollege.edu.in
8.	git config --global user.name “2305018-dotco”
9.	git commit -m “upload success”
search : C:/ghpages-vercel/index.html
 
10.	git remote add origin https://github.com/2305018-dotco/ghpages-vercel.git
11.	git push origin master => authenticate 
12.	create token: 
profile token > settings > developer settings > personal aceess token:token(classic) > generate token (classic) > Note:demToken > check all the options given below > generate token > copy url
 git remote set-url origin https:// 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@github.com/2305018-dotco/ghpages-vercel.git
13.	git commit -m :Upload Success”
14.	git push origin master
 
 
 
Go to vercel.com > start deploy > continue with google > install > 
Only select repository > install> import > deploy > continue to dashboard >  click domains link

