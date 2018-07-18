# String Operations
```
      class Groovy_String{
            static void main(String[] args){
            
                def name = "PRADY";

             //----------------------------------------------------------------------------------------------------------------------                
             //Single quotes: -> value inside is taken literally
                
                println( 'Hi ${name}\n' ) ;                           // Hi ${name}
                println( "Hi ${name}\n" ) ;                           // Hi PRADY
                
             //----------------------------------------------------------------------------------------------------------------------                
             // Multi-Line / Triple Quotes:
                
                def multiLine = ''' This 
                                is
                                a 
                                Multiline 
                                string''';
                println(multiline);                                 // This is a Multiline string
             //----------------------------------------------------------------------------------------------------------------------
             // Using Index:
             
                println("3rd Index of name " + name[2] );                      // 3rd Index of name R 
                println("some chars in between " + name[2..5] );               // some chars in between RADY
                println("some specific chars in between " + name[1,5] );       // some specific chars in between PY
                println("Index of Letter " + name.indexOf['r'] );              //  Index of Letter 3
                println("Substring @ 1:" + name.substring(1) );                // Substring  @ 1: RADY
                println("Substring @ 1:" + name.substring(1,3) ) ;               // Substring  @ 1: RAD
 
             //----------------------------------------------------------------------------------------------------------------------                
             // Concat:
             
                println("ABC" + "XYZ" );                // ABCXYZ
                println("ABC".concat("XYZ") );          // ABCXYZ
    
             //----------------------------------------------------------------------------------------------------------------------                
             // Repeat String:
             
                def repeat = "What the Hell";
                println( repeat  * 3 );                // What the Hell What the Hell What the Hell
                println( repeat  - "Hell" );           // What the
                
                println( repeat.split(' ') );          // [What , the , Hell]
                println( repeat.toList(' ') );          // [W,h,a,t, ,t,h,e, ,H,e,l,l]
                
                println( repeat.replaceAll('Hell', 'F***!') );          // What the F***! 
                println( repeat.Uppercase() );                          // WHAT THE F***!
                println( repeat.Lowercase() );                          // what the f***!
                
             //----------------------------------------------------------------------------------------------------------------------                             
             // Equality:
             
                println("Check equality:" +'PRADY'.equals(name) ));                  // Check equality: PRADY == PRADY true
                println("Check equality:" +'PRADY'.equalsIgnoreCase('prady') ));     // Check equality: PRADY == prady true

              //----------------------------------------------------------------------------------------------------------------------                
              // Compare:
              
                 println( "ABC <=> XYZ" + ('ABC <=> XYZ)  );                       // ABC <=> XYZ -1
                 println( "ABC <=> ABC" + ('ABC <=> ABC') );                       // ABC <=> ABC  0
                 println( "XYZ <=> ABC" + ('XYZ <=> ABC') );                       // XYZ <=> ABC  1
             
             //----------------------------------------------------------------------------------------------------------------------                
             // Length:
             
                println("Length:" +'PRADY'.length() ));                               // Length: 5
                
             //----------------------------------------------------------------------------------------------------------------------
             
             }
      }
```
