# java-pattern
### .1.Create programme for the given pattern:
````
*****
*****
*****
*****
*****
````
````
public class Squarepattern {
        public static void main(String[] args) {

            // size of the square
            int size = 5;
            // outer loop
            for (int i = 0; i < size; i++) {
                // inner loop
                for (int j = 0; j < size; j++) {
                    System.out.print("*");
                }
                System.out.println();
            }
        }
}
````
![1](https://user-images.githubusercontent.com/93587823/224885625-9691cdd7-edb0-4ef6-98cd-f309627894ff.png)
### 2.Create programme for the given pattern:
```
*********
 *******
  *****
   ***
    *
```
````
public class Inverted
{
    public static void main(String[] args)
    {
        int rows=5;
        for (int i= 0; i<= rows-1 ; i++)
        {
            for (int j=0; j<=i; j++)
            {
                System.out.print(" ");
            }
            for (int k=0; k<=rows-1-i; k++)
            {
                System.out.print("*" + " ");
            }
            System.out.println();
        }
    }
}
````
![2](https://user-images.githubusercontent.com/93587823/224885678-a39919f0-6961-4d31-994d-18fcd6b24b86.png)
### 3.Create programme for the given pattern:
````
*
**
***
****
*****
****
***
**
*
````
````
public class Pascaltriangle {
    public static void main(String[] args) {
        int size = 5;

        for (int i = 1; i <= size; i++) {
            for (int j = 0; j < i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }

        for (int i = 1; i <= size - 1; i++) {
            for (int j = 0; j < size - i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}

````
![3](https://user-images.githubusercontent.com/93587823/224886015-aebed581-ba2c-4a91-a222-c558ca1c83c6.png)

