# Bisection-Method
this repository will demonstrate how to implement the Bisection method with Python

# How it works? 
This is an algorithm for finding the roots of a function, the method is iterative that divides the segment into small parts and each time divides it into the middle of the segment.
This process continues until the difference in the range is small enough or until the inertia tax exceeds the predetermined tax.
</br>
</br>

We will check if (𝑓 (𝑋_𝐿) ∗ 𝑓 (𝑋_𝑚)) <0
If so it means our root will be between 𝑋_𝐿 and 𝑋_𝑚
Therefore we will set the new 𝑋_𝑅 as 𝑋_𝑚
Divided into two again
Repeat the process until we reach zero
Or until we reach a really small difference

ilustration:</br>
![ilustration](https://i.ibb.co/NLS0ZBK/bis.jpg)

the algorithem logic will spin around the following: 
```bash
while(b-a):
  c = (a+b)/2
  if f(a)*f(c) > 0:
    a = c
  else:
    b = c
```

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install sympy and Texttable.

```bash
pip install sympy
```

```bash
pip install Texttable
```




## Contributing
I built the algorithm in the form of object-oriented programming, in order to simplify the idea behind it. <br/>
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
