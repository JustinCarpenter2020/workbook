# Day 46
__2/15/21__

## What are the three categories of data types? How are they different?
1. Reference: reference types hold the address to the value they contain, they do not hold the value directly. This allows the value to be manipulated and then seen wherever this type is used, as the address wasn't altered just the value. 
2. Value: value types directly hold their value. These types cannot be null as they have a value on creation, and when changed in separate functions will not change the base value. 
3. Pointer: pointer types simply point to the value they are matched with, they cannot alter or change that value. 
## What are the Value-type data types? What differences do you notice from JavaScript?
<ul>
<li>bool
 <li>byte
 <li>char
 <li>decimal
 <li>double
 <li>enum
 <li>float
 <li>int
 <li>long
 <li>sbyte
 <li>short
 <li>struct
 <li>uint
 <li>ulong
 <li>ushort
 </ul>
 There seems to be much more variety in the types of value data types. It might've been we just used less in javascript because there was no need for it, but this is much more strict and specific.

## In your own words how do Reference types get stored in memory? How does this differ from Value types?
Reference types when stored the variable holding that memory has an address on where to find the actual value. Where as in value types that memory is stored directly on the variable which means it has a defined value.


daily Project:
https://github.com/JustinCarpenter2020/cSharpGregslist