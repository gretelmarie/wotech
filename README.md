# Wotech program 💪🏼 👸🏼

# Welcome to my repository!
## My skills
(...learning in progress 💁🏼‍♀️)
- Java
- Python
- Github


## My favourite code so far 👩🏼‍💻
```java
public class Main {
  public static void main(String[] args) {

    // winter, spring, summer, autumn
    // warm jacket, t-shirt, swimming suite, rain coat
    String season = "winter";
    

    if (season == "winter"){
      System.out.println("Wear a warm jacket!");
    }
    else if (season == "spring"){
      System.out.println("Wear a t-shirt!");
    }
    else if (season == "summer"){
      System.out.println("Wear a swimming suit!");
    }
    else if (season == "autumn"){
      System.out.println("Wear a rain coat!");
    }
  }
  ```

```java
  public class Main {
  public static void main(String[] args) {
    System.out.println("Let's go and check out what is in the fridge!");
    var isFridgeOpen = true;
    String result; // no results in String, we decleared but we didn't assign
    
    if (isFridgeOpen) {
      var item1 = "Cheese";
      var item2 = "Milk";
      var item3 = "Eggs";
      result = item1 + item2 + item3; // we assign a value to the result here
    } else {
      result = "Fridge is closed, open the fridge"; // we assign a value to the result here
    }

    System.out.println(result);
  } 
}
```
```java
public class Main {
  public static void main(String[] args) {

    
    System.out.println("hh");

    int i = 1;
    boolean isEven = false;
    //counts from 0 to 10
    //provides wether or not the number is even or odd
    
    while (i < 10) {
      String result = ""; 
      //me anname sellele var-ile value based on if else conditions
      if(isEven == true){
        result = "even";
      }else{
        result = "odd";
        }
      
      System.out.println(i + " " + result);
      i = i + 1;
      isEven = !isEven; 
      // isEven value is flipped to opposite value in the end of circle. 
      //isEven == true 1st circle -> isEven == false 2nd circle
      }

  }
}
```

```java

  import java.util.Scanner;  // Import the Scanner class

class Main {
    public static void main(String[] args) {
        Scanner number = new Scanner(System.in);
        System.out.println("How big is the triangle?");

        int triangle = number.nextInt();
        int row = 1;

        while (row <= triangle) {
            int column = 1;
            while (column <= row) {
                System.out.print("_");
                column = column + 1; //või column++
            }
            System.out.println(); // Move to the next line after printing underscores for each row
            row = row + 1; //või row++
        }
    }
}
```
