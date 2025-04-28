# Assignment-1
# Programming  Language and Structure
# 1)Fixed Dynamic:
In C++ [new int[size] (here,size decided at runtime, but fixed after creation)]
and In JAVA [new int[size] (same; size fixed after creation)]
Both allow size at runtime but cannot resize after allocation.
# 3)Fixed Heap Dynamic: 
In C++ [new int[fixed_size]; allocated on heap] and  In JAVA it is similar to the C++ 
# Comparison Category-wise between two types of languages:
# 2)Stack Dynamic:
In C++	[int arr[size]; (Variable Length Array — supported only in some C++ compilers)]
But In JAVA ( Not truly possible — arrays are always heap objects; but method-local arrays look similar.)
So,C++ supports real stack arrays, Java does not.
# 4)Heap Dynamic:
In C++ [	vector<int> (from STL; dynamically grows/shrinks automatically)] but In JAVA[	ArrayList<Integer> (dynamic array from Java Collections Framework) ]. Here,syntax and type-safety are stricter in Java.
So, we can say that,C++ gives more control but also more responsibility,can manage memory.Java gives less control but automatic management like garbage collection, bounds checking.For heap dynamic arrays, both are similar in functionality but different in syntax and behavior.


