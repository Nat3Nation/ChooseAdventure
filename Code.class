/**
 *ChooseAdventure.java  @Nathan Judd
 *
 *For the lol’s
 */

import java.util.Scanner;

public class Adventure
{
   public static void main (String args[])
   {       
       /**
        *For fun
        */
       
       String name, answer = new String();
       int attack, coins, health, potions, armor, speed;
       
       Scanner input = new Scanner(System.in);
       
       System.out.println ("Hello new adventurer, what is your name?");
       name = input.nextLine();
       
       System.out.println ("Hello " + name + "!");
       System.out.println ();
       System.out.println ("Choose a Role:");
       System.out.println ("Knight: +5 Attack, +3 Speed, +7 Defence");
       System.out.println ("Assassin: +5 Attack, +7 Speed, +3 Defence");
       System.out.println ("Brute: +7 Attack, +3 Speed, +5 Defence");
       answer = input.nextLine();
       
       while (answer.equals("Knight") || answer.equals("Assassin") || answer.equals("Brute"))
       {
           if (answer.equals("Knight"))
           {
               System.out.println ("For the Brotherhood!");
               attack = 5;
               speed = 3;
               armor = 7;
               health = 10;
               break;
            }
           else if (answer.equals("Assassin"))
           {
                System.out.println ("Silent and Deadly!");
                attack = 5;
                speed = 7;
                armor = 3;
                health = 10;
                break;
           }
           else if (answer.equals("Brute"))
           {
               System.out.println ("AHHHHHHHHHH!!!!!");
               attack = 7;
               speed = 3;
               armor = 5;
               health = 10;
               break;
           }
           else
           {
               System.out.println ("Please type one of the 3 class names."); //Make it jump back to first if
               answer = input.nextLine();
               continue;
           }
       }
       
       System.out.println ();
       System.out.println ("Welcome traveler to your virtual dungeon\nAll progress will be made based on your decisions");
       System.out.println ("Would you like to enter the dungeon?");
       System.out.println ("(Type either yes or no)");
       answer = input.nextLine();
       
       while (answer.equals("yes") || answer.equals("no"))
       {
           if (answer.equals("yes"))
           {
               System.out.println ("Well choosen, you may proceed");
               break;
            }
            else
            {
               System.out.println ("Game Over (Idiot). Choose again"); //Loop back to role choosing
               answer = input.nextLine();
               continue;
            }
       }
       
       System.out.println("*italics*");
   }
}
