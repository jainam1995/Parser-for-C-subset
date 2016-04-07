# Parser-for-C-subset
A parser implemented using yacc that parses a subset of C language and outputs syntax errors
###
Type the following in Terminal : 

`lex rules.lex`  
`yacc -d parser.y`  
`c++ lex.y.c y.tab.c`  
`./a.out < test.c`
