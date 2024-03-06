# cs155labex01
CS 155 Lab Repository Exercise 1

## Name
Ralph Bryllemond Y. Diaz  
202000356  
CS 155 LAB 3 (TUE)

## Compilation Notes
Compilation: `flex le1-202000356.flex` && `gcc lex.yy.c -o lexer.out`   
Execution: `./lexer.out <TESTCASE>.ec`

## Token Types
### KEYWORDS SECTION (RESERVED)
| Token Type | Token Value |
| --- | --- |
| PROCEDURE | RESERVED |
| VAR | RESERVED |
| INTEGER | RESERVED |
| REAL | RESERVED |
| BOOLEAN | RESERVED |
| STRING | RESERVED |
| WRITELN | RESERVED |
| BEGIN | RESERVED |
| END | RESERVED |
| TO | RESERVED |
| DOWNTO | RESERVED |
| NOT | RESERVED |
| OR | RESERVED |
| DIV | RESERVED |
| MOD | RESERVED |
| AND | RESERVED |
| IF | RESERVED |
| THEN | RESERVED |
| ELSE | RESERVED |
| WHILE | RESERVED |
| DO | RESERVED |
| FOR | RESERVED |
  
### NUMBERS SECTION 
| Token Type | Token Value |
| --- | --- | 
| DIGIT | INTEGER (Ex: 123, 5, 20) |
| REAL | REALNUMBER (Ex: 123.24, 5.3, 9.0) |
  
### STRING SECTION
| Token Type | Token Value |
| --- | --- | 
| STRING | STRING (Ex: "W", "Hello", "yes 23") |
| IDENT | IDENT (Ex: w, circle2, areaSquare) |
  
### RELATION OPERATORS
| Token Type | Token Value |
| --- | --- | 
| = | EQUAL |
| <> | NOTEQUAL |
| > | GREATERTHAN |
| >= | GREATERTHANEQ |
| < | LESSTHAN |
| <= | LESSTHANEQ |

### MATH OPERATORS
| Token Type | Token Value |
| --- | --- | 
| * | MULTI |
| + | PLUSSYM | 
| - | NEGSYM | 
| / | DIV | 

### SPECIAL CHARACTERS
| Token Type | Token Value |
| --- | --- | 
| := | ASSIGNMENT |
| ; | SEMICOLON |
| : | COLON | 
| ( | OPENPAR |
| ) | CLOSEPAR |
| \ | QUOTATION |
| , | COMMA | 
