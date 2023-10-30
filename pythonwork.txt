neighbour=[ "vishal","dev","pavan"]
               
print(neighbour)
               
['vishal', 'dev', 'pavan']
neighbour.append("prem")
               
neighbour.insert(0,"Mohan vamsi")
               
print(neighbour)
               
['Mohan vamsi', 'vishal', 'dev', 'pavan', 'prem']
neighbour.append("Rishi")
               
neighbour.insert(0,"Mohan vamsi")
               
SyntaxError: multiple statements found while compiling a single statement
neighbour.append("Rishi")
               
neighbour.insert(0,"chakri")
               
print(neighbour)
               
['chakri', 'Mohan vamsi', 'vishal', 'dev', 'pavan', 'prem', 'Rishi']
neighbour.remove("Mohan vamsi")
               
print(neighbour)
               
['chakri', 'vishal', 'dev', 'pavan', 'prem', 'Rishi']
neighbour.pop(3)
               
'pavan'
print(neighbour)
               
['chakri', 'vishal', 'dev', 'prem', 'Rishi']
neighbour.sort(reverse=True)
               
print(neighbour)
               
['vishal', 'prem', 'dev', 'chakri', 'Rishi']
neighbour.reverse=True
               
Traceback (most recent call last):
  File "<pyshell#71>", line 1, in <module>
    neighbour.reverse=True
AttributeError: 'list' object attribute 'reverse' is read-only
neighbour.reverse()
               
print(neighbour)
               
['Rishi', 'chakri', 'dev', 'prem', 'vishal']
neighbour.copy()
               
['Rishi', 'chakri', 'dev', 'prem', 'vishal']
print(neighbour.copy)
               
<built-in method copy of list object at 0x000001C61A3E7F80>
b=neighbour.copy()
               
print(b)
               
['Rishi', 'chakri', 'dev', 'prem', 'vishal']
