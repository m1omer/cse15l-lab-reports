
# Lab Report 5 (Favorite Tasks)

My favorite Lab report was researching the different commands in lab report 3 and deepening my understanding of those commands by exploring different applications. This lab played an integral role in helping develop my command line skills and served as the foundation of command line knowledge for the next few lab reports.


# Exploring different commands 

__Researching the grep command__

__Context 1__

You can use 'ls' in conjunction with grep. The command 'ls' is used to list the contents of a directory. 



Example 1:

In this case it returns the files which name's contain the phrase 'result'.
```
ls | grep result
```

<img width="493" alt="image" src="https://user-images.githubusercontent.com/122564032/224855836-973faaf6-71e5-45b6-8b44-0b54f4eac85b.png">




Example 2:

In this case I used ls in conjunction with grep to return all the files with a txt extension in the current working directory.
```
ls| grep txt
```

<img width="585" alt="image" src="https://user-images.githubusercontent.com/122564032/224856614-91c96cfd-53b0-4525-8cb1-17179af1c83b.png">




__Context 2__

Using the command 'cat', in conjunction with grep tells the command to search for a specific string within a file and display the results.


Example 1:
```
cat fresults.txt | grep Nepal
```

<img width="573" alt="image" src="https://user-images.githubusercontent.com/122564032/224857675-36f1e3a8-26dc-4305-b28b-db726b9a8b87.png">


Example 2:
```
cat gresults.txt | grep Hawaii
```
<img width="561" alt="image" src="https://user-images.githubusercontent.com/122564032/224857975-e69bc32d-44ac-4a61-9d0f-38766fc18bf2.png">

__Context 3__

(find)
Using the command find, in conjunction with grep tells the command to search for files or directories that match a specific pattern.


Example 1:
```
find . -type f | grep Vallarta
```
<img width="564" alt="image" src="https://user-images.githubusercontent.com/122564032/224858601-d7882403-6b4c-4b3b-ac75-062aad2bfe14.png">

Example 2:
```
find . -type f | grep Portugal
```

<img width="566" alt="image" src="https://user-images.githubusercontent.com/122564032/224858932-17385e72-19be-46c8-a818-da0ed204e8ea.png">

__Context 4__

Using the command sort, in conjunction with grep tells the command to search for a specific pattern and then sort the matching lines. In this instance it will sort them in alphabetical order. 

Example 1:
```
grep Cuba fresults.txt | sort
```
<img width="565" alt="image" src="https://user-images.githubusercontent.com/122564032/224859576-2265983a-ca81-4484-89fd-5ab6101fe3c6.png">

Example 2:
```
grep Crete gresults.txt | sort
```
<img width="578" alt="image" src="https://user-images.githubusercontent.com/122564032/224859800-dd7f4726-822f-4d16-ab5c-64eb2f0ada70.png">



