# complex
This file is a java class that allows you to do arithmetic with complex numbers. 

# usable methods 
Complex add(Complex arg)
* adds two complex numbers together

Complex subtract(Complex arg)
* subtracts two complex numbers from each other

Complex multiply(Complex arg)
* multiplies two complex numbers

Complex divide(Complex arg)
* divides two complex numbers

Complex cos()
* works out the cosine of a complex number 

Complex sin()
* works out the sine of a complex number 

static Complex cos(Complex arg)
* works out the cosine of a complex number 

static Complex sin(Complex arg)
* works out the sine of a complex number 

Complex exp()
* works out e^c where c is a complex number

double arg()
* calculates the complex argument for the complex number

double getReal()
* gets the real value of the complex number

double getImaginary()
* gets the imaginary value of the complex number

void setReal(double value)
* sets the real value of the complex number

void setImaginary(double value)
* sets the imaginary value of the complex number

Complex pow(Complex arg)
* calculates a complex number to the power of a complex number to 14 decimal places

Complex pow(Complex arg, int decimalPlaces)
* calculates a complex number to the power of a complex number to a set number of decimal places

String toString()
* converts the value of the complex number to a string

# examples of usage

code:
```
Complex c = new Complex(2, 3); 
System.out.println(c);
```
output: 
```
2.0 + 3.0i
```

code: 
```
Complex c = new Complex("1 + 2i"); 
System.out.println(c);
```
output: 
```
1.0 + 2.0i
```

code: 
```
Complex c = new Complex(1,2); 
Complex d = new Complex(2,3);
System.out.println(c.add(d));
```
output: 
```
3.0 + 5.0i
```

code:
```
Complex c = new Complex("1 + 2i"); 
System.out.println(c);
```
output: 
```
1.0 + 2.0i
```

code:
```
Complex c = new Complex("1 + 2i ^ 2"); 
System.out.println(c);
```
output: 
```
-3.0 + 0.0i 
```

code:
```
Complex c = new Complex("( 1 + 2i ) ^ ( 6 + 2i )"); 
System.out.println(c);
```
output: 
```
-5.2962564457018 + 12.58472633504645i
```
