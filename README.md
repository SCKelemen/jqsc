# jqsc

## Notes

+Parse
The parser is pretty simple. It is generated via yacc and bison.

+Compiler (Code Gen)

+Interpreter 
 The interpreter is implement as a stack machine.





tokens:   
INVALID_CHARACTER   
IDENT   
FIELD   
LITERAL   
FORMAT   
REC   
SETMOD   
EQ   
NEQ   
DEFINEDOR   
AS   
DEF   
MODULE   
IMPORT   
INCLUDE   
IF   
THEN   
ELSE   
ELSE_IF   
REDUCE   
FOREACH   
END   
AND   
OR   
TRY   
CATCH   
LABEL   
BREAK   
LOC   
SETPIPE   
SETPLUS   
SETMINUS   
SETMULT   
SETDIV   
SETDEFINEDOR   
LESSEQ   
GREATEREQ   
ALTERNATION   
QQSTRING_START   
QQSTRING_TEXT   
QQSTRING_INTERP_START   
QQSTRING_INTERP_END   
QQSTRING_END   
FUNCDEF   
NONOPT   
