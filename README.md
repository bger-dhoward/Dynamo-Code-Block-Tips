# Dynamo Code Block Tips
Tips for syntax and shortcuts with code block nodes in Dynamo

### Quick If-Then-Else Statements
Syntax:
```
<expression> ? <result if true> : <result if false>
```
Example:
```
a = 0;
b = 1;
a < b ? "a less than b": "b less than a";

--> "a less than b"
```
### Multi-Line Comments
Write multi-line comments following the Javascript block comment notation:
```
\* 
Write lots of comments here.
And even more comments.
So... many... comments...
*\;
```
One advantage of this is it allows you to write a code block that takes no inputs and has no outputs, which is ideal for writing general notes and comments in your graph.
