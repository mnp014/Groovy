# Airthmatic Operations:

### Code:
```
    class GroovyABC{
        static void main(String[] args){
        
        
        //--------------------------------------------------------------------
        // 1. Basic Operations:
        
              println("1 + 2 = " + (1 + 2));
              println("2 - 1 = " + (2 - 1));
              println("1 * 2 = " + (1 * 2));
              println("7 / 2 + " + (7.intdiv(2)));
              println("3 % 2" + (3 % 2));
              
        //--------------------------------------------------------------------
        // 2. Decimal Operations:
        
              println("1.3 + 2.3 = " + (1.3.plus(2.3)));
              println("2.3 - 1.3 = " + (2.3.minus(1.3)));
              println("1.3 * 2.3 = " + (1.3.multiply(2.3)));
              println("7.3 / 2.3 + " + (7.3 / 2.3) ));
              
        //--------------------------------------------------------------------              
        // 3. BODMAS Operations:
        
              println("(1 + 2)*3 = " + ((1 + 2)*3));
              
        //--------------------------------------------------------------------                            
        // 4. Increment & Decrement:
        
        int num =10;
              println("num++ = " + (num++));      // 10
              println("++num = " + (++num));      // 12
              println("num-- = " + (num--));      // 12
              println("--num = " + (--num));      // 10
              
        //--------------------------------------------------------------------  
        // 5. Get Largest & Smallest ( Integer/Float/Double )
        
              println("Large Int" + Integer.MAX_VALUE );        
              println("Small Int" + Integer.MIN_VALUE );
        
              println("Large Float" + Float.MAX_VALUE );
              println("Small Float" + Float.MIN_VALUE );
        
              println("Large Double" + Double.MAX_VALUE );
              println("Small Double" + Double.MIN_VALUE );
        
        //--------------------------------------------------------------------      
        // 6. Large decimal value
        
              println("Decimal 1+ Decimal 2 = " + (1.00000000000000000000000000000000000111111111111111111111 +
                                                    0.00000000000000000000000000000000000000000000000000000001) );
                                                    
        //--------------------------------------------------------------------                            
        // 7. Math Functions
        
              def randNum =3.0;
              
              println(" Math.abs(-3.45)= ")  +  Math.abs(-3.45)));            //  Math.abs(-3.45)= 3.45 
              println(" Math.round(3.45)= ") +  Math.abs(3.45)));
              println(" randNum.pow(2) = ")  +  randNum.pow(2)));
              println(" 4.0.equals(5.0) = ") +  4.0.equals(5.0)));
              println(" randNum.equals(Float.Nan) = ")+  randNum.equals(Float.Nan)));
              println(" Math.cbrt(8) = ")    +  Math.cbrt(8)));
              println(" Math.ciel(3.45) = ") +  Math.ciel(3.45)));
              println(" Math.floor(3.45)= ") +  Math.floor(3.45)));
              println(" Math.min(3,4) = ")   +  Math.min(3,4)));
              println(" Math.min(3,4) = ")   +  Math.min(3,4)));
              println(" Math.PI= ")          +  Math.PI));
              
              println(" Math.log(2) = ")     +  Math.log(2)));                   //Base 2
              println(" Math.log10(2)= ")    +  Math.log10(2)));                //Base 10
              
              println(" Math.toDegrees(Math.PI)= ") +  Math.toDegrees(Math.PI)));
              println(" Math.toRadians(Math.PI) +  Math.toRadians(Math.PI)));
             
              println(" Math.sin(0.5)= ")    +  Math.sin(0.5)));
              println(" Math.cos(0.5)= ")    +  Math.cos(0.5)));
              println(" Math.tan(0.5)= ")    +  Math.tan(0.5)));
              println(" Math.asin(0.5)= ")   +  Math.asin(0.5)));
              println(" Math.atan(0.5)= ")   +  Math.atan(0.5)));
              println(" Math.sinh(0.5)= ")   +  Math.sinh(0.5)));
              println(" Math.cosh(0.5)= ")   +  Math.cosh(0.5)));
              println(" Math.tanh(0.5)= ")   +  Math.tanh(0.5)));

        // Random value [1-100]              
              println(" Random Value = ")    +  Math.abs(new Random().nextInt() % 100 + 1)));

        //--------------------------------------------------------------------                            
        
        }
    }
```
___
