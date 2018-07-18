# Input
```
    class GroovyInput{
          static void main(String[] args){
              
              def str;
              print("Enter a String");
              str = System.console().readLine();
              println(str);
              
          //--------------------------------------------------------
          // Casting
              
              def num1, num2;
              print("Enter a number 1);
              num1 = System.console().readLine().toDouble;
              print("Enter a number 2);
              num2 = System.console().readLine().toDouble;
              println("%.2f + %.2f = %.2f \n ", [num1, num2, (num1+num2)]);
           //--------------------------------------------------------
              
          }
    } 
```
