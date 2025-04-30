1) In line 9, what would be printed is "values added: 20"
2) Line 13 would print "final result: 20"
3) You should not use var as it raises a lot of errors in many ways. First, var is scoped through blocks, meaning you are able to use a variable defined outside of any if and while blocks. In addition it is able to be redeclared, which is considered malpractice. 
4) Line 9 prints "values added: 20
5) Line 13 would not print anything and would raise an error. Since we are using the Let keyword, result is not scoped outside of the first if block it is declared inside of
6) Line 9 would not print anything and would raise an error. Trying to reassign a constant is errorous
7) Line 13 would also not print anything. Constants have the same scope as let, meaning it is not obtainable outside the first if block
