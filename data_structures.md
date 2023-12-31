# Data structures in Python

## Type conversion

| Method	| Explanation					| Usage		  |
|---------------|-----------------------------------------------|-----------------|
|`type()`	|Read the type of a variable			|`type(var)`	  |
| `str()`| Set a variable to be a string | `string(var)`|
|`int()`	|Set a variable to be an integer (truncate)	| `int(var)`	  |
|`float()`	|Set a variable to be a float 			|`float(var)`	  |
|`complex()`	|Set a variable to be a complex			|`complex(var)`	  |

## Arithmetic operations

| Method       	 | Explanation 					| Usage		  |
|----------------|----------------------------------------------|-----------------|
| `+` 	 	 | Addition 			 		| `x+y` 	  |
| `-`		 | Subtraction   				| `x-y`		  |
| `*`    	 | Multiplication 				| `x*y`		  |
| `/` 		 | Division			 		| `x/y`	 	  |
| `%` 	 	 | Modulus (remainder of division) 		| `x%y` 	  |
| `**`		 | Exponentiation   				| `x**y`	  |
| `//`    	 | Floor division (equivalent to `int(x/y)`) 	| `x//y`	  |

## Random values
[TBD]

## Assignment operations

| Method       	 | Explanation 					| Usage 	  |
|----------------|----------------------------------------------|-----------------|
| `=` 	 	 | Assign value to variable	 		| `x=value` 	  |
| `+=`		 | Equivalent to `x=x+value`   			| `x+=value`	  |
| `-=`    	 | Equivalent to `x=x-value` 			| `x-=value`	  |
| `*=` 		 | Equivalent to `x=x*value`	 		| `x*=value` 	  |
| `/=` 	 	 | Equivalent to `x=x/value`	 		| `x/=value` 	  |
| `**=`		 | Equivalent to `x=x**value` 			| `x**=value`	  |
| `//=`    	 | Equivalent to `x=x//value`		 	| `x//=value`	  |

## Comparison operations

| Method       	 | Explanation 					| Usage		  |
|----------------|----------------------------------------------|-----------------|
| `==` 	 	 | Equal to 			 		| `x==y` 	  |
| `!=`		 | Not equal to   				| `x!=y`	  |
| `>`    	 | Greater than 				| `x>y`		  |
| `<` 		 | Less than			 		| `x<y`	 	  |
| `>=` 	 	 | Greater than or equal to 	 		| `x>=y` 	  |
| `<=`		 | Less than or equal to			| `x<=y`	  |
| `and`		 | If both statements are true = true		| `x=y and y=z`	  |
| `or`		 | If one of the statements is true = true	| `x=y or y=z` 	  |
| `not`		 | Reverse the result				| `not(x=y)`	  |
| `is`		 | Strict equality (same object)		| `x is y`	  |
| `is not`	 | Reverse strict equality (not same object)	| `x is not y`    |
| `in`		 | Sequence is present in object		| `x in y`	  |
| `not in`	 | Sequence is not present in object		| `x not in y`    |

## List operations

| Method and usage  			 | Explanation 							 |  
|----------------------------------------|---------------------------------------------------------------|
| `list=["value1","value2"]` 	 	 | Define a list 		 				 |
| `list[index]` 			 | Read value of list at index (starts at 0)	(can be negative)|
| `list[index]=value`		 | Update the value at index index with value value	 |
| `list.append(value)` 			 | Add items to the end of the list				 |
| `list.extend(sequence)`		 | Add a sequence of items at the end				 |
| `list.insert(index,value)`		 | Insert value at index index				 |
| `list.remove(value)`			 | Remove the first item with value value			 |
| `list.pop(index)`			 | Remove the value at index and return it. Default index: -1 	 |
| `list.sort(reverse=Bool, key=funct)`	 | Sort the list. Default Bool: false. Default key: ascending	 |
| `list.reverse()` 			 | Reverses the order of the list				 |
| `len(list)` 				 | Returns the length of the list				 |
| `list.count(value)			 | Returns how many times a value appears in the list	 	 |


## Tuple operations

| Method and usage  			 | Explanation 							 |  
|----------------------------------------|---------------------------------------------------------------|
| `tuple=("value",value, value, "value")`| Define a tuple 		 				 |
| `tuple[index]` 			 | Read value of tuple at index (starts at 0)(can be negative)	 |
| `tuple+tuple2` 			 | Concatenate tuples						 |
| `del tuple`				 | Deletes the entire tuple					 |
| `len(tuple)` 				 | Returns the length of the tuple			 	 |
| `tuple.count(value)			 | Returns how many times a value appears in the tuple	 	 |

## Set operations

| Method and usage  			 | Explanation 							 |  
|----------------------------------------|---------------------------------------------------------------|
| `tuple=("value",value, value, "value")`| Define a tuple 		 				 |
| `tuple[index]` 			 | Read value of tuple at index (starts at 0)(can be negative)	 |
| `tuple+tuple2` 			 | Concatenate tuples						 |
| `del tuple`				 | Deletes the entire tuple					 |
| `len(tuple)` 				 | Returns the length of the 				 |
| `tuple.count(value)			 | Returns how many times a value appears in the tuple	 	 |
| `list.index(value)` | Return the first index with value value|
 
## Dictionary operations

| Method and usage | Explanation |  
|----------------------------------------|--------------------------------------------------------------------------------------|
| `dict={"Key": value,"Key": value}` 	 | Define a dictionary 		 				 			|
| `dict=dict(Key=value, Key=value)`	 | Define a dictionary without quoting the keys			 			|
| `dict[key]=value`			 | Modify the value of an existing value or create a new one 	 			|
| `del dict[key]`			 | Remove the key key and associated value 			 			|
| `dict.update(pairs)`			 | Inserts items to the dictionary. Can add multiple at the same time 			|
| `dict[key]`				 | Return the value of key item					 			|
| `dict.get(key)`			 | Return the value of key item								|
| `dict.setdefault(key,value)`		 | Return the value of key item. If key item does not exist, insert key with value.	|
| `dict.keys()`	 | Return a tuple containing a list of keys. Updates automatically.			|
| `dict.values()`			 | Return a tuple containing a list of values. Updates automatically.			|
| `dict.items()`			 	 | Return a tuple containing a list of key-value pairs. Updates automatically. 		|
| `dict.pop(key)`			 | Removes the specified item, returns the removed value				|
| `dict.popitem()`			 | Removes the last item inserted, returns the removed value				|
| `len(dict)`				 | Return the length of a dictionary or tuple			 			|
| `dict.clear()`				 | Clear the entire dictionary.								|
