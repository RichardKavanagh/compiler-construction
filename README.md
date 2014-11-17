## Description

JavaCC is an open source parser generator and lexical analyzer generator written in Java.

This project will use JavaCC to generate a lexical analyzer and a top-down parser with semantic analysis for a simple language called SimpL.


SimpL is comprised of the following tokens.

Case is insignificant in simpL. The lexical analyser should recognise the following tokens:

**keywords:** and, bool, const, do, else, false, if, int, main, not, or, real, return, string, then, true, var, void, while.

**Identifiers:** Any other string of letters, digits or underscore character ('_') beginning with a letter.

**strings**: As in C string are delimited by double quotes. Strings may contain any alphanumeric found on a standard keyboard or punctuation characters listed below. Strings may contain quotes, backslashes or newlines only if escaped by a backslash.

**numbers**: A string of (decimal) digits. Real numbers are represented by a string of digits, a period character "." and a string of digits. Examples of valid numbers are 123, 0.123 and 1.23. Numbers such as 123. and .123 are invalid.

**operators, relations and punctuation marks:** +  -  *  /  %  =  !=  <  >  <=  >=  (  )  {   }   ,  ;  :  .  :=  ?  !

**Comments:** can appear between any two tokens. There are two forms of comment: one is delimited by "/*" and "*/" and can be nested; the other begins with -- and is delimited by the end of line and this type of comments may not be nested. 
