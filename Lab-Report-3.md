
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

Example 1:
```
grep -i "jeans" ./ch9.txt*
```
<img width="1512" alt="Screen Shot 2023-02-13 at 10 51 21 PM" src="https://user-images.githubusercontent.com/122564032/218660942-6e90d891-0501-448c-9262-62d2b9ca0601.png">

Example 2:
```
grep -i "jeans" ./ch9.txt*
```
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/122564032/218661453-295f6fd0-f378-4658-8dc5-7e6d802ac8a5.png">


__Context 3__


Using the command '-c' which is count, in conjunction with grep tells the command to count the number of matches rather printing the matching lines.


Example 1:
```
grep -c "a" ./ch8.txt*
```
<img width="449" alt="image" src="https://user-images.githubusercontent.com/122564032/218662224-ba6237cf-ca07-467d-81d9-3d06e585f82f.png">

Example 2:
```
grep -c "z" ./*
```

<img width="488" alt="image" src="https://user-images.githubusercontent.com/122564032/218662513-84c8af44-b616-457f-949c-7156f541f48c.png">


__Context 4__

Using the command '-r'  which is recursive, in conjunction with grep tells the command to search for a pattern recursively in all file and directories in the given path.

Example 1:
```
grep -r "Yantai" ./written_2/*
```
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/122564032/218664007-d25ab869-029a-4257-ae25-aa0ce78ff897.png">

Example 2:
```
grep -r "1,700" ./written_2/*
```
<img width="1512" alt="image" src="https://user-images.githubusercontent.com/122564032/218664278-8432a67a-864d-4dd6-8efe-abcb3439a930.png">




