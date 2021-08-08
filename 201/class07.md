# What is a table?

A table is a structured set of data made up of rows and columns (tabular data). A table allows you to quickly and easily look up values that indicate some kind of connection between different types of data, for example a person and their age, or a day of the week, or the timetable for a local swimming pool.

## How does a table work?

The point of a table is that it is rigid. Information is easily interpreted by making visual associations between row and column headers. Look at the table below for example and find a Jovian gas giant with 62 moons. You can find the answer by associating the relevant row and column headers.

## basic Table strucTure

\<table>

The \<table> element is used to create a table. The contents of the table are written out row by row.

\<tr>

You indicate the start of each row using the opening \<tr> tag. (The tr stands for table row.)
It is followed by one or more \<td> elements (one for each cell in that row).
At the end of the row you use a closing \</tr> tag.

\<td>

Each cell of a table is represented using a \<td> element. (The td stands for table data.)
At the end of each cell you use a closing \</td> tag.

## Long Tabel

There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content).
These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table (as you will see when you learn about CSS).

\<thead>

The headings of the table should sit inside the \<thead> element.
\<tbody>

The body should sit inside the \<tbody> element.

\<tfoot>

The footer belongs inside the \<tfoot> element.
By default, browsers rarely treat the content of these elements any differently than other elements however designers often use CSS styles to change their appearance.

## JS

- What is memory ?

- On a hardware level, computer memory consists of a large number of
flip flops. Each flip flop contains a few transistors and is capable of storing one bit. Individual flip flops are addressable by a unique identifier, so we can read and overwrite them. Thus, conceptually, we can think of our entire computer memory as a just one giant array of bits that we can read and write.

- Using values
Using values basically means reading and writing in allocated memory. This can be done by reading or writing the value of a variable or an object property or even passing an argument to a function.

- Garbage collection
As stated above, the general problem of automatically finding whether some memory "is not needed anymore" is undecidable. As a consequence, garbage collectors implement a restriction of a solution to the general problem. This section will explain the concepts that are necessary for understanding the main garbage collection algorithms and their respective limitations.

- What is an object in js ?

- an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.

- What are Built-in objects?

- The built-in objects are Date, Math, String, Array, and Object. Each is used in a unique and not-quite-consistent way. Furthermore, newer versions of JavaScript (as found in Netscape "Atlas," currently in beta) implement several of these objects in a different manner than in Netscape 2.0.
