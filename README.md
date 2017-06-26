Jasmine is a behavior-driven development framework for testing your JavaScript code \[Jasmine\].

This is an IntelliJ IDEA Live Template for the Jasmine JavaScript BDD Framework and Jasmine JQuery extention.

# About

This is are IntelliJ IDEA Live Templates for working with the Jasmine Framework. It contains two files. These files work with any JavaScript file as specified in the File Types.

##Jasmine.xml
This is the main template for the Jasmine Framework

##Jasmine_jquery.xml
This is the additional template for working with the Jasmine jquery extention. 

# Commands
The commands are delemited by <tab>. Hitting <tab> goes to the next $VALn$ where n is the number of tab presses until $END$ is reached. For instance typing in typing in ec<tab> will put you at $VAL0$ in `expect($VAL0$).toContain($VAL1$);$END$`. Hitting <tab> again will take you to $VAL1$ hitting <tab> one last time will take you to the $END$ from here tab becomes a tab character. 

## Jasmine Commands
### aft 
After each


``` javascript
afterEach(() => {  
	$END$  
});

`````

### any 
any


``` javascript
jasmine.jasmine.any($VAL0$);$END$
```

### bef 
before each


``` javascript
beforeEach(() => {  
    $END$      
});
```

### des 
describe jasmine


``` javascript
describe('$VAL0$', () => {  
    $END$  
});
```

### ec
expect to contain


``` javascript
expect($VAL0$).toContain($VAL1$);$END$
```

### ed
expect to be defined


``` javascript
expect($VAL0$).toBeDefined();$END$
```

### ee
expect to equal


``` javascript
expect($VAL0$).toEqual($VAL1$);$END$
```

### ef
expect to match


``` javascript
expect($VAL0$).toBeFalsy();$END$
```

### ehc
expect have been called


``` javascript
expect($VAL0$).toHaveBeenCalled();$END$
```

### ehcw
expect have been called with


``` javascript
expect($VAL0$).toHaveBeenCalledWith($VAL1$);$END$
```

### em
expect to match

``` javascript
expect($VAL0$).toMatch();$END$
```

### en
expect to be null

``` javascript
expect($VAL0$).toBeNull();$END$
```

### et
expect to be truthy

``` javascript
expect($VAL0$).toBeTruthy();$END$
```

### ex
expect

``` javascript
expect($VAL0$)$END$;
```

### it
it

``` javascript
it('$VAL0$', () => {  
    $END$  
});
```

### notc
expect not to contain

``` javascript
expect($VAL0$).not.toContain($VAL1$);$END$
```

### notd
expect not to be defined

``` javascript
expect($VAL0$).not.toBeDefined();$END$
```

### note
expect not to equal

``` javascript
expect($VAL0$).not.toEqual($VAL1$);$END$
```

### notf
expect not to be falsy

``` javascript
expect($VAL0$).not.toBeFalsy();$END$
```

### notm
expect not to match

``` javascript
expect($VAL0$).not.toMatch($VAL1$);$END$
```

### notn
expect not to be null

``` javascript
expect($VAL0$).not.toBeNull();$END$
```


### nohc
expect have been called


``` javascript
expect($VAL0$).not.toHaveBeenCalled();$END$
```

### nott
expect not to be truthy

``` javascript
expect($VAL0$).not.toBeTruthy();$END$
```

### notx
expect not

``` javascript
expect($VAL0$).not$END$;
```

### s
spy on

``` javascript
spyOn($VAL0$, '$VAL1$')$END$;
```

### scf
spy on and call fake

``` javascript
spyOn($VAL0$, '$VAL1$').and.callFake($VAL2$);$END$
```

### sct
spy on and call through

``` javascript
spyOn($VAL0$, '$VAL1$').and.callThrough();$END$
```

### sr
spy on and return

``` javascript
spyOn($VAL0$, '$VAL1$').and.returnValue($VAL2$);$END$
```

### st
spy on and throw

``` javascript
spyOn($VAL0$, '$VAL1$').and.throwError($VAL2$);$END$
```


# More

 * \[1\][Jasmine](http://github.com/pivotal/jasmine)


# Live Template Installation

Copy the xml file(s) to the live templates directory:

 * Windows: `<your home directory>\.<product name><version number>\config\templates`
 * Linux: `~\.<product name><version number>\config\templates`
 * MacOS: `~/Library/Preferences/<product name><version number>/templates`
