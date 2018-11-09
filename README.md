###### Iterations
**do**
Executes  while a specified boolean expression evaluates to `true`; executes one or more times.
```csharp
int n =0;
do
{
  Console.WriteLine(n);
  n++;
} while (n < 100);
```

**for**
The for statement defines an initializer, condition and iterator; all optional.
Executes while a specified boolean expression evaluates to `true`;  different from a while loop because it requires an iterator and thus specifies an end.

Break out of the loop with `break`, or step to the next iteration with `continue`.  `goto`, `return`, or `throw` statements also accepted.
```csharp
for (int n = 0; n < 100; n++) // (initializer; condition; iterator)
{
  Console.Writeline(n);
}
```
**foreach, in**
Executes for each element in an instance of a collection.

Break out of the loop with `break`, or step to the next iteration with `continue`.  `goto`, `return`, or `throw` statements also accepted.
```csharp
var primeNumbers = new List<int> { 2, 3, 5, 7, 11, 13, 17, 19 };
foreach (int element in primeNumbers)
{
  Console.WriteLine("Element: {0}", element);
}
```
**while**
Executes while a specified boolean expression evaluates to `true`; executes zero or more times.
```csharp
int n = 1;
while (true) // while (n <= 100)
{
  if (n <= 100) { Console.WriteLine(n); } else { break; }
  n++;
}
```
###### Collections & Data Structures

**Arrays**
Declare a single-dimensional array:
```csharp
string[] myArray = new string[8];
```
Initialize upon declaration:
```csharp
string=[] planets = {"Netpune", "Pluto", "Saturn"};
```
**Hashtables**
```csharp
using System.Collections;
Hashtable myAlbums = new Hashtable();
```