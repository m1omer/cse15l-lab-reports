
# Lab Report 3

__Researching the grep command__

__Context 1__

Using '-i' which is ignore case, in conjunction with grep tells the command to ignore the case sensitivity of the pattern. 
This is useful in situations when you are unawarre of the case sensitivity.

Example 1:
For this example I used the skill demo 1 files on my account of the ieng6 server. 

```
grep -i "equation" ./ch9.txt*
```
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/122564032/218660187-28085185-8df3-490e-98d1-6caf3c4838aa.png">


Example 2:

```
grep -i "EQUATION" ./ch9.txt*
```
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/122564032/218660396-a8a5945b-a2c4-43cc-a617-69c619ecb49f.png">

__Context 2__

Using the command '-v' which is inverted match, in conjunction with grep tells the command to print out lines which do not match the search pattern. 
<img width="1512" alt="Screen Shot 2023-02-13 at 10 51 21 PM" src="https://user-images.githubusercontent.com/122564032/218660942-6e90d891-0501-448c-9262-62d2b9ca0601.png">

