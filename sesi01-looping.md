### Sesi 1 ###

#### Looping ####

`Looping` adalah struktur kontrol yang memungkinkan Anda untuk mengulangi tugas beberapa kali.
Mungkin ada situasi ketika kita perlu mengeksekusi blok kode beberapa kali, dan sering disebut sebagai `looping`.
Java memiliki tiga mekanisme perulangan. Anda dapat menggunakan salah satu dari tiga perulangan berikut:


### 1. while ###

#### Syntax: ####

``` java
while(Boolean_expression)
{
   //Statements
}
```

#### Contoh: ####

``` java
public class Test {

   public static void main(String args[]) {
      int x = 10;

      while( x < 20 ) {
         System.out.print("value of x : " + x );
         x++;
         System.out.print("\n");
      }
   }
}
```

#### Output: ####

``` 
value of x : 10
value of x : 11
value of x : 12
value of x : 13
value of x : 14
value of x : 15
value of x : 16
value of x : 17
value of x : 18
value of x : 19
```


### 2. do ... while ###

#### Syntax: ####

``` java
do
{
   //Statements
}while(Boolean_expression);
```

#### Contoh: ####

``` java
public class Test {

   public static void main(String args[]){
      int x = 10;

      do{
         System.out.print("value of x : " + x );
         x++;
         System.out.print("\n");
      }while( x < 20 );
   }
}
```

#### Output: ####

``` 
value of x : 10
value of x : 11
value of x : 12
value of x : 13
value of x : 14
value of x : 15
value of x : 16
value of x : 17
value of x : 18
value of x : 19
```


###  3. for ###

#### Syntax: ####

``` java
for(initialization; Boolean_expression; update)
{
   //Statements
}
```

#### Contoh: ####

``` java
public class Test {

   public static void main(String args[]) {

      for(int x = 10; x < 20; x = x+1) {
         System.out.print("value of x : " + x );
         System.out.print("\n");
      }
   }
}
```

#### Output: ####

``` 
value of x : 10
value of x : 11
value of x : 12
value of x : 13
value of x : 14
value of x : 15
value of x : 16
value of x : 17
value of x : 18
value of x : 19
```


###  Contoh `for` dalam bentuk lain ###

#### Syntax: ####

``` java
for(declaration : expression)
{
   //Statements
}
```

#### Contoh: ####

``` java
public class Test {

   public static void main(String args[]){
      int [] numbers = {10, 20, 30, 40, 50};

      for(int x : numbers ){
         System.out.print( x );
         System.out.print(",");
      }
      System.out.print("\n");
      String [] names ={"James", "Larry", "Tom", "Lacy"};
      for( String name : names ) {
         System.out.print( name );
         System.out.print(",");
      }
   }
}
```

#### Output: ####

``` 
10,20,30,40,50,
James,Larry,Tom,Lacy,
```

###  Contoh `for` dengan `break;` ###

#### Syntax: ####

``` java
break;
```

#### Contoh: ####

``` java
public class Test {

   public static void main(String args[]) {
      int [] numbers = {10, 20, 30, 40, 50};

      for(int x : numbers ) {
         if( x == 30 ) {
	      break;
         }
         System.out.print( x );
         System.out.print("\n");
      }
   }
}
```

#### Output: ####

``` 
10
20
```

###  Contoh `for` dengan `continue;` ###

#### Syntax: ####

``` java
continue;
```

#### Contoh: ####

``` java
public class Test {

   public static void main(String args[]) {
      int [] numbers = {10, 20, 30, 40, 50};

      for(int x : numbers ) {
         if( x == 30 ) {
	      continue;
         }
         System.out.print( x );
         System.out.print("\n");
      }
   }
}
```

#### Output: ####

``` 
10
20
40
50
```
