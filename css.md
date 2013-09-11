(S)CSS Style Guide
===
**by Robin Thrift**


###General

*Tab Width*: 4 spaces  
*Syntax*: Use the SCSS syntax, not the SASS syntax

###Variables

Variable names should be **camel case** in general, using underscores to determine modifiers.


```scss
$varName = #9d9d9d;
$varName_mod = blue;
			
selector {
	color: $varName;
}
			
selector:hover {
	color: $varName_mod;
}
```