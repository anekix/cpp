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
	return 0;
}
```
