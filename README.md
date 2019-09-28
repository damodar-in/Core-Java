# Core-Java
core java concept's in details <br/>
Program to calling return-type & non-parameterized method
### Main Class
```
public class Pen11 {
	public static void main(String[] args) {
		Pen1 obj=new Pen1();  
                /* Method one : bcz it occupied more memory and time taking program program */
                /* int ab=obj.redPen(); */
		
                /* Method-2 : this methosd short & saves memory */
		System.out.println(obj.redPen());
	}
}
```
### Child Class
```
 class Pen1
{
	int redPen()
	{
  //int a=2
		return 2;
	}
}

```
#steps
1. Child class object create in main method.
   - We can use child class method by two step.
2. Method-1 : Using variable catch object return value.
3. Method-1 : Print that value.
