---
layout: post
title:      "Method Scopes"
date:       2020-02-23 03:35:00 +0000
permalink:  method_scopes
---


What really stuck out to me on Module 5, Section 2: Variables and Methods was the section about Method Scope. While at first glance, it seems like an obvious aspect of programming languages, it is actually to how a developer designs and plans their program. A program essentially takes various data points as variables and passes them around different methods in different files and outputs the result in some fortmat. By recognizing the scope the of these methods, a developer plans where these variables will be declared and how they will be passed around without running into any NameErrors.

Programs and applications will grow and become more complex as time goes on. Complex programs will have numerous variables and understanding where you can and can't access those variables is important to a functioning program. This subtle aspect of scope inside of a programming language forces you to think logically and plan out where you will declare, manipulate, pass through, and display your variables through your program/application. Method scope is part of the design aspect of your data when architecting how your programs functions.

In addition, eue to the scope, the names of variables becomes important too. You may not want to use a certain name as an argument for a method and use that same name for some random unrelated variable outside of that method. 

For example:

```
text = "Test Text"

def test_method(text)
   puts text
end
```

In this code snippet, the text variable outside of the method is technically different than the text argument placeholder I am using for my test_method. I feel that this can be confusing to another developer if they were reading through this however as the name "text" is used to refer to two different things with this snippet. This presents an opportunity to write better variable names due to the scope that this method creates. 

In summary, scope ended up being that subtle, yet vital aspect of this section that stuck out to me. This is due to the way if forces you to organize your varibles when designing your program as well as be smart about what those variables are called. 
