# Linux Basic Commands Assignment

## Assignment Part-3

### 1. Create a file like nano file1.txt

- Edit some data and then save the file

### 2. Now we will copy date from file1 to new file2

- cp file1.txt file2.txt
- Then see the output of file2.txt, cat file2.txt
- Give screenshot

#### **ANSWER** ->>>

<p>After doing second step, it will copy the whole data from file2 to file3, as we can see in given screenshot</p>

![Assignment 1 copy](./Images/Assignment%201%20copy%20command.png)

Note: cat command will show the file in terminal

### 3. Now we will move the file2.txt to new folder /home

- mv file2.txt /home
- Then go to home directory and check ls, file exits or not?
- Given screenshot

#### **ANSWER** ->>>

<p>
As we try to move a file to home directory, It won`t work as home is the root file of linux. if we provide a file name then it will move to the home directory.

In a linux environment, move command is work as copy all data from old file to new different file name. It will not work as move location of old file to new location.

</p>

![Assignment 2](./Images/Assignment%202.png)

### 4. Then we create a new file3.txt and file4.txt in home directory and add content in it.

- Now do echo “Hello I am newline” > file3.txt and provide the
  output of file3.txt
- Now do echo “Hello I am newline” >> file4.txt and provide the
  output of file4.txt
- Tell the different between both step you follow and the reason
  behind it

#### **ANSWER** ->>>

There is no difference in the both command.

![Assignment Question 3-1](./Images/Assignment%20question%203-1.png)

![Assignment Question 3-2](./Images/Assignment%20question%203-2.png)

### 5. For remove a file or directory you can use the below two commands

- To delete a file – rm <any_filename>
- To delete a directory - rmdir <any_directory name>

#### **ANSWER** ->>>

- -rm will remove the any file.
- -rmdir will remove the any directory in the system
