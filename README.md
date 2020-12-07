# COGNIZANCE2020

# **Task-4**

># _Description_:-
* This is a c programme for odd,even game
  
># _Rules to play_ :-
1. There must be only two players and it is played by fingers of hand(only one hand)
2. Before showing the numbers the children should predict the sum.
3. This game is like both the guys should show numbers from 0-5.
4. We should sum the both numbers shown by 2 children.
5. Now if the number which we sum is even then the guy predicted even wins the game and vice-versa.

># _Pseudo Code_ :-
1. Now we should enter the numbers which are chosen by children.
2. Now the scanf part of program which we typr reads the numbers wich we entered.
3. As numbers are read so we should add the numbers now.
4. Now we have the number so now the program says whether it is even odd.
5. when we declare the even or odd soo we got the winner of this game.
   
># The Program Of The Game :-
 
```c 
#include<stdio.h>
int main ()
{
       
       int a,b,c;
       printf("enter the numbers which are chosen by children");
       scanf("%d%d",&a,&b);
              c=a+b;
       printf("the sum of numbers chosen is %d\n",c);

         if(c%2==0)
       printf("the number is even\n sooooo.... now the gut who predicted the sum  as even wins the game");

         else
       printf("the number is odd\n sooooo....noe the guy who predicted the sum to be odd wins the game");

}
```
># _An Example_ ;-
                 Let we have  two children named Mike and Veronica. So they are playig odd and even game soo they both agree that if the out put is odd veronica wins and if even mike wins so genraly they shake hands and represents the numbers so veronica shows 4 and mike shows 2. When they add he number is 6 as it is even ,soo now mike wins the game!!.  

># _Related Images_ ;-

1. ![possibilities of numbers](https://image.shutterstock.com/image-vector/one-two-three-four-five-600w-1111524644.jpg)
2. ![couting numbers to display their numbers](https://www.wikihow.com/Play-Odds-and-Evens#/Image:Play-Odds-and-Evens-Step-3.jpg)
3. ![win of odd]https://www.shutterstock.com/image-vector/number-nine-made-fingers-3603048)
4. ![win of even](https://www.pinterest.ca/pin/152770612330070236/)
5. ![making score card](https://www.wikihow.com/Play-Odds-and-Evens#/Image:Play-Odds-and-Evens-Step-2.jpg)

># _Some Of Possiblilities_ ;-
  ## table :-
        heree let us assume that mike choses odd and verinica choses even in all cases
  |mike   |veronica   | sum   | winner   |
  |-------|-----------|-------|----------|
  |5      |3          |8      |veronica  |
  |3      |2          |5      |mike      |
  |1      | 3         |4      |veronica  |
   
   soo, from the above table we can see that number of times of odd is greater soo verinica is winner of game.




   





                    
