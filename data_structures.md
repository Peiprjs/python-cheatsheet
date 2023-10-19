# Data structures in Python

## Type conversion

| Method	| Explanation					| Usage		  |
|---------------|-----------------------------------------------|-----------------|
|`type()`	|Read the type of a variable			|`type(var)`	  |
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

## List operations

| Method and usage  			 | Explanation 							 |  
|----------------------------------------|---------------------------------------------------------------|
| `list=["value1","value2"]` 	 	 | Define a list 		 				 |
| `list[position]` 			 | Read value of list at position (starts at 0)	(can be negative)|
| `list.append(value)` 			 | Add items to the end of the list				 |
| `list.extend(sequence)`		 | Add a sequence of items at the end				 |
| `list.insert(index,value)`		 | Insert value at index position				 |
| `list.remove(value)`			 | Remove the first item with value value			 |
| `list.pop(index)`			 | Remove the value at index and return it. Default index: -1 	 |
| `list.sort(reverse=Bool, key=funct)`	 | Sort the list. Default Bool: false. Default key: ascending	 |
 
## Dictionary operations

| Method and usage  			 | Explanation 							 			|  
|----------------------------------------|--------------------------------------------------------------------------------------|
| `dict={"Key": value,"Key": value}` 	 | Define a dictionary 		 				 			|
| `dict=dict(Key=value, Key=value)`	 | Define a dictionary without quoting the keys			 			|
| `dict[key]=value`			 | Modify the value of an existing value or create a new one 	 			|
| `del dict[key]`			 | Remove the key key and associated value 			 			|	
| `dict.update(pairs)`			 | Inserts items to the dictionary. Can add multiple at the same time 			|
| `dict[key]`				 | Return the value of key item					 			|
| `dict.get(key)`			 | Return the value of key item								|
| `dict.setdefault(key,value)`		 | Return the value of key item. If key item does not exist, insert key with value.	|
| `dict.keys()				 | Return a tuple containing a list of keys. Updates automatically.			|
| `dict.values()			 | Return a tuple containing a list of values. Updates automatically.			|
| `dict.items()			 	 | Return a tuple containing a list of key-value pairs. Updates automatically. 		|
| `dict.pop(key)`			 | Removes the specified item, returns the removed value				|
| `dict.popitem()`			 | Removes the last item inserted, returns the removed value				|
| `len(dict)`				 | Return the length of a dictionary or tuple			 			|
| `dict.clear()				 | Clear the entire dictionary.								|
