```java
/**************************************************************************
 * 
 * Copyright (c) Unterrainer Informatik OG.
 * This source is subject to the Microsoft Public License.
 * 
 * See http://www.microsoft.com/opensource/licenses.mspx#Ms-PL.
 * All other rights reserved.
 * 
 * (In other words you may copy, use, change and redistribute it without
 * any restrictions except for not suing me because it broke something.)
 * 
 * THIS CODE AND INFORMATION IS PROVIDED "AS IS" WITHOUT WARRANTY OF ANY
 * KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE
 * IMPLIED WARRANTIES OF MERCHANTABILITY AND/OR FITNESS FOR A PARTICULAR
 * PURPOSE.
 * 
 ***************************************************************************/
```
 
# data-structures

This jar contains several classes designed to do common tasks.

Currently this contains the following classes:

* ##### Tuple2  
This class is a simple generic implementation of a two-tuple.
* ##### Interval  
Is exactly what the name suggests. An interval defined by a minimum and a maximum with getters and setters.
* ##### Fader  
The fader consists of an interval and adds a value (double) to it. The value is always in between the interval.  
It adds a percentage getter and setter as well allowing you to do conversions from a percentage-value to your interval and backwards.

#### Apache Maven artifact to use in your pom
```xml
<dependency>
    <groupId>info.unterrainer.java.tools</groupId>
    <artifactId>data-structures</artifactId>
    <version>0.2</version>
</dependency>
```