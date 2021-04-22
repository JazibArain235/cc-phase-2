# cc-phase-2
lexical specification
#CC 106395: Micro-C Compiler#

###PROJECT MEMBERS###
StdID | Name
------------ | -------------
**62155** | **Muhammad Najam Hanif** 
**60449** | **Muhammad Jazib Mahmood**
## Project Description ##
Its a simple Micro C complier, it have lex file whihch define its token, and then the yacc will parse it from left to right.

##Sample Language Used ##
i = 1;
sum = 0;
while sum < 10000 do begin
sum = sum + i;
i = 1 + i;
end;

#include <some code examples.h>
int
a
=
1
;

###Lexical Specification###
-Keyword “int,string”
-Identifier “main”
-Parentheses “(,)”
-Open brace ”{“
-return keyword “return”
-Constant “2”
-Semicolon “;”
-Close brace “}”

