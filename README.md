Justin Nguyen
CSC 4351
Professor Baumgartner
22 April, 2022

unCx()
The program uses the native implementation provided by the skeleton packages. 

unEx() 
This function uses unCx() on the condition node and its child nodes a/b. After this, the function returns an ESEQ with a tree structure similar to the tree in the textbook.
![image](https://user-images.githubusercontent.com/76065821/233818993-a36f7ec3-9e88-400a-99c8-939c43e1c73f.png)
For the example conditional “if a < b then c < d else 0” a tree that looks like the following is produced. 
![image](https://user-images.githubusercontent.com/76065821/233819007-e55b4a26-beb5-4e65-9a10-7413598e8ca0.png)



unNx( )
unNx() is just a copy of the provided unNx() method. 
![image](https://user-images.githubusercontent.com/76065821/233819026-28040f5f-1d44-45a5-a21a-e29c4b39f4cf.png)


Output

I did very little in terms of modifying Translate.Translate very little was changed. I don’t really understand the implementation so the output is missing all of the trees that are created by “IfThenElseExp.java” 

This is all that the implemented functions would print.
![image](https://user-images.githubusercontent.com/76065821/233819153-c43234f3-254c-4e34-b84c-326eb32364f4.png)
