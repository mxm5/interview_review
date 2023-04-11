[(35) Java Wave - YouTube](https://www.youtube.com/@javawave7003/videos)

1. what is class loader in java
[(35) Class Loader in Java |Core java interview question - YouTube](https://www.youtube.com/watch?v=ujzdaojdZ6k)
![[Pasted image 20230409092726.png]]
3 types of class loader in java

/lib `bootstrap` /lib / util / 
/ext `extentions`
env_var `system`
![[Pasted image 20230409093153.png]]

loadclass ( `fully qualified name` )

---
array list
threshold is when it is full and grows to `cc*1.5 +1`
linked list is just normal nodes pointing forward and backword

---
why strings have 2 hash codes
FB Ea have same hash code

![[Pasted image 20230409103525.png]]

same objects same hash codes
![[Pasted image 20230409103544.png]]
same names ? same 2 persons ?
![[Pasted image 20230409103608.png]]
Nooo

https://www.youtube.com/watch?v=n-KC2WqvG_k&t=609s
https://www.youtube.com/watch?v=JqOCsnu-Ios




![[Pasted image 20230409111053.png]]
ref variable is just pointing to the first object not the second one
https://www.youtube.com/watch?v=WQfCYBJU2gg&list=PL3NrzZBjk6m_9c3_U9VKNuV4Xe6mRGKFW&index=2

heap stores all the things in the runtime


stack and heap
![[Pasted image 20230409114123.png]]
for every call of every method there is one stack created
![[Pasted image 20230409114149.png]]
it falls down into it so picking up the topest gets destroyed
![[Pasted image 20230409114241.png]]


CGPT :
```prompt
where is javas static area of the memory
```

In Java, the static area of memory is called the "Method Area" or "Class Area". This area is a part of the Java heap and is used to store class-level data, such as static variables, static methods, and class-level constants.

![[Pasted image 20230409122820.png]]
i give to my self more than 100 out of 10 yup! that is it ! 

inner classes always are static to be made new objects of ...

what is @ required in spring 
explain all kinds of autowiring































