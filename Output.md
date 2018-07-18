```
    class GroovyOutput{
          static void main(String[] args){
              
              def str = "abc";
              
              println(" a random $str);
              printf(" a random %s ", str);
              printf("%-10s %d %.2f %10s \n", ['xyz', 20, 3.1478, 'str']);             //xyz----------20-3.14----------abc
              
          }
    } 
```
