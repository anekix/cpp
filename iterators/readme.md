```cpp
std::vector<int> integers{ 3, 4, 56, 6, 778 };
```
```cpp
for( std::vector<int>::iterator it = integers.begin() ; it != integers.end() ; ++it )
      {*it = 4;  std::cout << *it << std::endl; }
```
```cpp
for( std::vector<int>::const_iterator it = integers.begin() ; it != integers.end() ; ++it )
       { cout << *it << endl; }
}
```
Reverse Iterator - accessing containers in reversed manner
```cpp
for (vector<int>::reverse_iterator i = my_vector.rbegin(); i != my_vector.rend(); ++i ) { 
       cout << *it << endl;
} 
```
