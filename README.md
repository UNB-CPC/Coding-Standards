# Coding Standards
UNB CPC coding standards for collaboration.

## Naming conventions:
Give as descriptive a name as possible, within reason. 
Do not worry about saving horizontal space as it is far more important to make your code immediately understandable by a new reader. 
Do not use abbreviations that are ambiguous or unfamiliar to readers outside your project, and do not abbreviate by deleting letters within a word.

This are universal naming conventions unless specified for a specific languange
```java
// Constants:
int CAPS_SNAKE_CASE;

// Classes:
class PascalCase{}

// Variables:
int camelCase;
```

## Comments:
Though a pain to write, comments are absolutely vital to keeping our code readable. The following rules describe what you should comment and where. 

But remember: while comments are very important, the best code is self-documenting. 
- Giving sensible names to types and variables is much better than using obscure names that you must then explain through comments.

When writing your comments, write for your audience: the next contributor who will need to understand your code.

1. Be consistent.
2. File comments describe the contents of a file.
   - If a file declares, implements, or tests exactly one abstraction that is documented by a comment at the point of declaration, file comments are not required.
   - All other files must have file comments
3. Follow language specific commenting standards.

## Languages
This are the recognised coding conventions of the langauges used by the club:
- **C++** - [Google C++ style guide](https://codiepp.github.io/styleguide/cppguide.html)
- **Java** - [Java coding standards](https://www.javaspring.net/blog/java-coding-standard/)
- **JavaScript** - [React handbook](https://reacthandbook.dev/project-standards)
- **C** - [GNU coding standards](https://www.gnu.org/prep/standards/html_node/Writing-C.html)
