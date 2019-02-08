Java provides a number of access modifiers to set access levels for classes, variables, methods, and constructors. 
The four access modifiers are: Default, Public, Private, & Protected. 

*Classes*
Classes can only use two of the access modifiers: Default & Public

A public class limits the scope of the .java file to the package (folder?) it is in. Say you have ProgramA in Package1 and ProgramB in Package2. You also place a template.java file in Package1 along with ProgramA. You have set both ProgramA & ProgramB to use a class from template.java. If you remove the *public* modifier from template.java, only ProgramA (which is in the same folder/package as template.java) will be able to access that class. Public simply means it's visible to the entire word. If you remove that keyword, the default is that it's only visible to the package it's currently in. 

*Variables*
Variables work no differently from classes when it comes to Public vs Default access modifiers. Variables, however, can also use the Protected modifier. A Protected variable is visible to the package and all subclasses. See ***LINK TO INHERITENCE*** this link to learn more about inheritence (Or should we explain it simply right here and now?). 

Variables are also given the fourth access modifier of private. Private variables are visible to the class only. This is the most restrictive access type. 
https://www.youtube.com/watch?v=aRQRV2PMHtk
I like this explanation. maybe we can find a way to word this more succinctly that won't require a video lecture?
