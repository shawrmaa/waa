import java.util.*;
 
public class Monster {
 
 
	static void print(String hatdog) {
	System.out.print(hatdog);
	}
	static void println(String hatdog) {
	System.out.println(hatdog);
	}
	static void BadEnding() {
 
 
		String black = "\033[0;90m";
		String red = "\033[0;91m";
		String reset = "\033[0m";
 
		String BadEnd = "YOUR FRIEND DIDN'T GET THE JUSTICE AND THEY WILL NEVER BE ABLE TO FIND THE REAL CULPRIT.";
 
		for (char letter : BadEnd.toCharArray()) {
	       	    System.out.print(red + letter + reset);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
		println("");
		println("");
		System.out.print(black + "THE END" + reset);
        for (int i = 0; i < 3; i++) {
            try {
                Thread.sleep(1000);
                System.out.print(".");
            } catch (InterruptedException e) {
                e.printStackTrace();
            }
        }
	}
	static void GoodEnding() { 
 
		String black = "\033[0;90m";
		String green = "\033[0;92m";
		String reset = "\033[0m";
 
String GoodEnd = "JUSTICE HAS BEEN SERVED FOR THE DEATHS OF OLIVIA AND LILY, AND RONALD HAS BEEN IMPRISONED FOR LIFE.";
 
		for (char letter : GoodEnd.toCharArray()) {
	       	    System.out.print(green + letter + reset);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
		println("");
		println("");
		System.out.print(black + "THE END" + reset);
        for (int i = 0; i < 3; i++) {
            try {
                Thread.sleep(1000);
                System.out.print(".");
            } catch (InterruptedException e) {
                e.printStackTrace();
            }
        }
	}
	static void space() {
		String space = "       ";
		for (char letter : space.toCharArray()) {
            System.out.print(letter);
            try {
                Thread.sleep(20);
            } catch (InterruptedException e) {
                System.out.println("Sleep was interrupted");
            }
        }
	}
	public static void main(String[] args) {
		Scanner sk = new Scanner (System.in);
 
		String bloom = "\033[0;1m";
		String black = "\033[0;90m";
		String red = "\033[0;91m";
		String green = "\033[0;92m";
		String yellow = "\033[0;93m";
		String blue = "\033[0;94m";
		String purple = "\033[0;95m";
		String cyan = "\033[0;96m";
		String white = "\033[0;97m";
		String reset = "\033[0m";
 
        String[] usernames = {"Dindo","Joseph","Yorong","Jeiruss","Lilsey"};
        String[] passwords = {"Dinds", "Seph", "Yor","Jei","Lilsi"};
 
        boolean isLoggedin = false;
        String loggedInUser = "";
 
        System.out.println("THE DILEMMA");
        System.out.println(" ");
 
        while(true) {
    println("");
    println("o------------------o");
    println("|WELCOME.          |");
    println("|(1) LOG-IN        |");
    println("|(2) SIGN-IN       |");
    println("|(3) VIEW SYNOPSIS |");
    println("|(4) EXIT          |");
    println("o------------------o");
    System.out.println("");
    print("Answer: ");
            int action = sk.nextInt();
            sk.nextLine();
            switch(action){
                case 1:
 
                println(" ");
                print("Enter your Username:  ");
                String username = sk.nextLine();
 
                print("Enter your Password:  ");
                String password = sk.nextLine();
 
                boolean isExist = false;
                for (int i = 0; i < usernames.length; i++) {
if (usernames[i].equals(username) && passwords[i].equals(password))
{
                    isExist = true;
                    loggedInUser = usernames[i];
                    isLoggedin = true;
 
            break;
                    }
                }
                if (isExist) {
                    println(" ");
                    println(" ");
                    println("Logged in.");
                    println(" ");
                } else {
                    println(" ");
                    println("User not Found.");
                    println(" ");
                    println("Don't have an Account? Try Signing and create new Account :>");
                    println(" ");
                    continue;
                }
 
                println("");
                println("(1) PLAY");
                println("(2) LOG-OUT");
                println("");
                print("Answer: ");
                int playout = sk.nextInt();
                switch(playout) {
                case 1:
                	break;
                case 2:
                    println(" ");
                    println("Logged out.");
                    println(" ");
                    continue;
                }
 
                println("");
                println(black + "Note: It'll be better if you put 5 letters on your character's name." + reset);
                println("");
                println("");
                print("Please enter your character's name:   ");
                sk.nextLine();
                String player= sk.nextLine();
 
                println(" ");
 
                String start = "DILEMMA.";
                String the = "          ";
                for (char letter : start.toCharArray()) {
                    System.out.print(letter);
                    try {
                        Thread.sleep(20);
                    } catch (InterruptedException e) {
                        System.out.println("Sleep was interrupted");
                    }
                }
                for (char letter : the.toCharArray()) {
                    System.out.print(letter);
                    try {
                        Thread.sleep(200);
                    } catch (InterruptedException e) {
                        System.out.println("Sleep was interrupted");
                    }
                }
 
                println("");
                println("");
                print("Olivia:");
                String word1a = " Wake up " + player + "!! the class is going to start already.";
        for (char letter : word1a.toCharArray()) {
            System.out.print(letter);
            try {
                Thread.sleep(100);
            } catch (InterruptedException e) {
                System.out.println("Sleep was interrupted");
            }
        }
        println(" ");
                print(player + ": ");
        String word1b = "Really? I thought Sir Ronald was on a sick leave";
for (char letter : word1b.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        println("Sleep was interrupted");
    }
}
        println(" ");
        String word1c = "       so that he can't attend our class.";
for (char letter : word1c.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        println("Sleep was interrupted");
    }
}
        println(" ");
        print("Olivia:");
        String word1d = " Unfortunately";
for (char letter : word1d.toCharArray()) {
    System.out.print(letter);
    try {
Thread.sleep(125);
} catch (InterruptedException e) {
System.out.println("Sleep was interrupted");
}
}
print(" ");
String word1e = "he is.";
for (char letter : word1e.toCharArray()) {
System.out.print(letter);
try {
Thread.sleep(100);
} catch (InterruptedException e) {
System.out.println("Sleep was interrupted");
}
}
System.out.println("");
System.out.println("");
System.out.print(yellow + "PRESS ENTER" + reset);
sk.nextLine();
 
        System.out.println("");
        print("Professor Ronald:");
        String word2a1 = " Good morning class I want you to meet your new classmate. ";
        for (char letter : word2a1.toCharArray()) {
            System.out.print(letter);
            try {
                Thread.sleep(100); 
            } catch (InterruptedException e) {
                System.out.println("Sleep was interrupted");
            }
        }
 
        println(" ");
        print("Girl: ");
        String word2a2 ="Good Morning!!";
        String word2b = " My name is lily.";
        String word2c = "      I'm your new classmate and I hope we can all be friends.  ";
        String word2d = "      It's nice to meet you all!";
        String word2e = "...";
        for (char letter : word2a2.toCharArray()) {
            System.out.print(letter);
            try {
                Thread.sleep(100);
            } catch (InterruptedException e) {
                System.out.println("Sleep was interrupted");
            }
        }
for (char letter : word2b.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
println(" ");
for (char letter : word2c.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
println(" ");
for (char letter : word2d.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
for (char letter : word2e.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(500);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
System.out.println("");
System.out.println("");
System.out.print(yellow + "PRESS ENTER" + reset);
sk.nextLine();
 
println(" ");
println("*Bell rang*");
String word3a = "                  ";
for (char letter : word3a.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(200);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
println(" ");
 
print("Olivia: ");
 
String word3b = "Hey, what's the problem " + player;
String word3c = "        Are you okay?";
 
for (char letter : word3b.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
println("");
for (char letter : word3c.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(120);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
println(" ");
print(player + ": ");
String word3d = "I've been feeling dizzy since last night~.";
for (char letter : word3d.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
println(" ");
print("Olivia: ");
String word3e = "what? then why did you go to school today?";
for (char letter : word3e.toCharArray()) {
    System.out.print(letter);
    try {
        Thread.sleep(100);
    } catch (InterruptedException e) {
        System.out.println("Sleep was interrupted");
    }
}
println("");
print(player + ": ");
String word3f = "Ughh nevermind,.. by the way what are you doing in here?";
for (char letter : word3f.toCharArray()) {
System.out.print(letter);
try {
    Thread.sleep(100);
} catch (InterruptedException e) {
    System.out.println("Sleep was interrupted");
}
}
 
           println("");
           print("Olivia: ");
           String word3g = "I'm finding lily, the one who transfered here remember her?";		        
           String word3h = "        I think I saw her at the rooftop do you wanna come with me?";
           for (char letter : word3g.toCharArray()) {
       	    System.out.print(letter);
       	    try {
       	        Thread.sleep(100);
       	    } catch (InterruptedException e) {
       	        System.out.println("Sleep was interrupted");
       	    }
       	}
           println("");
           for (char letter : word3h.toCharArray()) {
       	    System.out.print(letter);
       	    try {
       	        Thread.sleep(100);
       	    } catch (InterruptedException e) {
       	        System.out.println("Sleep was interrupted");
       	    }
       	}
        println("");
        println("");
        println(cyan+"(1) Come with Olivia"+reset);
        println(cyan+"(2) Tell her that you want to take a rest."+reset);
        println("  ");
        print("Action: ");
        int choices1 = sk.nextInt(); 
        switch(choices1) {
        case 1:
        	println(" ");
        	print(player + ": ");
        	String word4a1 = "Sure I'll be happy to meet her too!!";
        	String word4a2 = "Really? Thankyou " + player;
        	for (char letter : word4a1.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        	println(" ");
	           print("Olivia: ");
        	for (char letter : word4a2.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
 
 
        	System.out.println("");
    		System.out.println("");
    		System.out.print(yellow + "PRESS ENTER" + reset);
    		sk.nextLine();
    		sk.nextLine();
    		   String word4a3 = "Going to the rooftop";
    		   String word4a4 = "....";
	           String word4b = "*They find lily, sitting at the rooftop bench*";	
	           String word4c = "       ";
	           String word4d = "(Whispered) Look, it's her!";
	           String word4e = "Hey! Come on be quiet..";
	           String word4f = "Oops I think she saw us.";
	           println(" ");
	           for (char letter : word4a3.toCharArray()) {
		       	    System.out.print(letter);
		       	    try {
		       	        Thread.sleep(100);
		       	    } catch (InterruptedException e) {
		       	        System.out.println("Sleep was interrupted");
		       	    }
		       	}
	           for (char letter : word4a4.toCharArray()) {
		       	    System.out.print(letter);
		       	    try {
		       	        Thread.sleep(500);
		       	    } catch (InterruptedException e) {
		       	        System.out.println("Sleep was interrupted");
		       	    }
		       	}
	           println(" ");
	           println(" ");
	           for (char letter : word4b.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
	           println("");
 
	           for (char letter : word4c.toCharArray()) {
		       	    System.out.print(letter);
		       	    try {
		       	        Thread.sleep(400);
		       	    } catch (InterruptedException e) {
		       	        System.out.println("Sleep was interrupted");
		       	    }
		       	}
	           println(" ");
	           print("Olivia: ");
	           for (char letter : word4d.toCharArray()) {
		       	    System.out.print(letter);
		       	    try {
		       	        Thread.sleep(100);
		       	    } catch (InterruptedException e) {
		       	        System.out.println("Sleep was interrupted");
		       	    }
		       	}
	           println("");
	           print(player + ": ");
	           for (char letter : word4e.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
 
            println(" ");
	           print("Olivia: ");
    		for (char letter : word4f.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
    		}
    		System.out.println("");
    		System.out.println("");
    		System.out.print(yellow + "PRESS ENTER" + reset);
    		sk.nextLine();
   		println("");
        print("Lily: ");
           String word5 = "Uhm";
		   String word5b = "....";
		   String word5c = "Lily right? My name is Olivia and this is " + player;
		   String word5d = "Hi";
		   String word5e = "Ohh.. Hello Olivia and " + player;
		   String word5f = "What are you doing here alone?";
		   String word5g = "Are you okay?";
		   String word5h = "What do you think of the school so far?";
		   String word5i = "Olivia slow down you're asking too many questions. *boink*";
		   for (char letter : word5.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
          for (char letter : word5b.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(500);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
          println("");
          print("Olivia: ");
          for (char letter : word5c.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
          println("");
          print(player + ": ");
          for (char letter : word5d.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(200);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
          println("");
          print("Lily: ");
          for (char letter : word5e.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
          println("");
          print("Olivia: ");
          for (char letter : word5f.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(30);
	       	    } catch (InterruptedException e) {
	       	        println("Sleep was interrupted");
	       	    }
	       	}
          println("");
          print("Olivia: ");
          for (char letter : word5g.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(30);
	       	    } catch (InterruptedException e) {
	       	        println("Sleep was interrupted");
	       	    }
	       	}
          println("");
          print("Olivia: ");
          for (char letter : word5h.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(50);
	       	    } catch (InterruptedException e) {
	       	        println("Sleep was interrupted");
	       	    }
	       	}
          println("");
          print(player + ": ");
          for (char letter : word5i.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
          System.out.println("");
  		System.out.println("");
  		System.out.print(yellow + "PRESS ENTER" + reset);
  		sk.nextLine();
     		String word6a = "*Giggles*";
     		String word6b = "Im just getting some fresh air and yes im doing alright, the school is uhm..";
     		String word6c = "is?";
     		String word6d = "it is very lively in here";
     		String word6e = "Everyone in this school is really full of life.";
     		println("");
            print("Lily: ");
            for (char letter : word6a.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
            println("");
            print("Lily: ");
            for (char letter : word6b.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
            println("");
            print("Olivia: ");
            for (char letter : word6c.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        println("Sleep was interrupted");
  	       	    }
  	       	}
            println("");
            print("Lily: ");
            for (char letter : word6d.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
            println("");
            print("Lily: ");
            for (char letter : word6e.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
            println(" ");
	           println("");
	      		print("PRESS ENTER");
	      		sk.nextLine();
	      		String jy = "Really? It's good to know that you like here lily.";
	      		String jyD = "Excuse me, can i ask a question?";
	      		String jyI = "Hmm, sure";
	      		String jyN = "How old are you?";
	      		String jyO = "15 years old, why?";
	      		String jyC = "Nothing, I just wanted to ask ";
 
	      		 String jyE = "Silence fills the place as they were thinking what topic they should talk about...";
 
 
	      		println("");
	           print(" Olivia: ");
	           for (char letter : jy.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	           println("");
	           print(player + " : ");
	           for (char letter : jyD.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	           println("");
	           print(" Lily: ");
	           for (char letter : jyI.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	           println("");
	           print(player + " : ");
	           for (char letter : jyN.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	           println("");
	           print(" Lily: ");
	           for (char letter : jyO.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	           println("");
	           print(player + " : ");
	           for (char letter : jyC.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	           println("");
	           for (char letter : jyE.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}       
	            println(" ");
	            println("");
	       		print("PRESS ENTER");
	       		sk.nextLine();
	   String jy1 = " I'm hungry, do you guys wanna go to the canteen to grab some food??";
	   String jy2 = "They all agree to go to the canteen..";
 
 
	       	println("");
	        print("Olivia : ");
	        for (char letter : jy1.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println("");
	        print(" ");
	        for (char letter : jy2.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        println(" ");
       		print("PRESS ENTER");
       		sk.nextLine();
	        String jy3 = "Making your way to the canteen with Olivia and Lily";
 
 
 
	        println("");
	        for (char letter : jy3.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        println(" ");
       		print("PRESS ENTER");
       		sk.nextLine();
	       		String jy4 = "While making your way way to the canteen you three crossed by your professor Ronald, \r\n"
	       				+ "   he excused Lily the moment he saw her because he needed her in her office";
	       		println("");
		        for (char letter : jy4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
	       		print("PRESS ENTER");
       		sk.nextLine();
       		String jy5 = "The 3 of them greeted their professor...";
 
       		println("");
	        for (char letter : jy5.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        println(" ");
       		print("PRESS ENTER");
   		sk.nextLine();
	        String jy6 = " Do you mind if i borrow Lily real quick? I need her in my office for something.";
	         String jy7 = " It's alright, We don't mind professor";
	         String jy8 = "I'll be back! wait for me okay?";
	         String jy9 = "We'll wait for you Lily!~";
	         String jy10 = "Lily And Professor Ronald went to his office as for you and Olivia went to go to the canteen to eat..";
 
 
 
 
	        println("");
	        print("Professor Ronald : ");
	        for (char letter : jy6.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println("");
	        print(player +  " : ");
	        for (char letter : jy7.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
 
	        println("");
	        print( "Lily : ");
	        for (char letter : jy8.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println("");
	        print( "Olivia : ");
	        for (char letter : jy9.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println("");
	        println(" ");
	        for (char letter : jy10.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        println(" ");
       		print("PRESS ENTER");
   		    sk.nextLine();
	        String jyK1 = "I'm curious..";
	        String jyK2 = "About... what? ";
	        String jyK3 = "You know.. ";
	        String jyK4 = "You know what????";
	        String jyK5 = "Why professor Ronald need Lily for.. "
	        		+ " He looked serious";
	        String jyK6 = "It's probably because he needed her to fill up something since "
	        		+ "she just transferred into our school.";
	        String jyK7 = " Do you...";
	        String jyK8 = "What? do i what?";
	        String jyK9 = "Do you wanna wait outside his office and you know maybe hear some things about Lily?";
 
	        println(" ");
	        print("Olivia : ");
	        for (char letter : jyK1.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(150);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print(player + " : ");
	        for (char letter : jyK2.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print(" Olivia : ");
	        for (char letter : jyK3.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(150);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print(player + " : ");
	        for (char letter : jyK4.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print("Olivia: ");
	        for (char letter : jyK5.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print(player + " : ");
	        for (char letter : jyK6.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print("Olivia : ");
	        for (char letter : jyK7.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(150);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print(player + " : ");
	        for (char letter : jyK8.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	        println(" ");
	        print("Olivia : ");
	        for (char letter : jyK9.toCharArray()) {
	 	       	    System.out.print(letter);
	 	       	    try {
	 	       	        Thread.sleep(100);
	 	       	    } catch (InterruptedException e) {
	 	       	        System.out.println("Sleep was interrupted");
	 	       	    }
	 	       	}
	       println("");
	       println("");
	        println("(1) Agree to wait outside Professors Ronald's office to eavesdrop");
	        println("(2) Stay in the canteen and wait for Lily");
	        println("");
            print("action: ");
	        int choicE = sk.nextInt();
	        switch(choicE) {
	        case 1:
	        	println("");
	        	String K1 = "You and Olivia went to Professors Ronald's Office to eavesdrop and accidently \r\n"
	        			+ "  heard about what he was telling Lily, hearing...";
	        	String K2 = " You know you look very pretty.";
	        	String K3 = "Ah.. Thank you..";
	        String K4 = "You and Olivia look at each other..";
	        String K5 = " I mean every boys in school tells her that, its probably normal.";	
	        String K6 = "You both continue to eavesdrop..";
	        String K7 = "You know it would be nicer if you wore a shorter skirt around the school..";
	        String K8 = "The silence fills the room..";
	        String K9 = "You and Olivia looks at each other once again with disgusted look..";
	        String K10 = "Lily speaks..";
 
 
	        	println(" ");
		        println(" ");
		        for (char letter : K1.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
	        	println(" ");
		        print("Professor Ronald : ");
		        for (char letter : K2.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print(" Lily : ");
		        for (char letter : K3.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : K4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print(player + " : ");
		        for (char letter : K5.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : K6.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Professor Ronald : ");
		        for (char letter : K7.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : K8.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : K9.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : K10.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println("");
		        println(" ");
	      		print("PRESS ENTER");
	      		sk.nextLine(); 
		        String Ki1 = "I-i think i should go professor if you don't need me for anything else..";
		        String Ki2 = "It's too early, why don't we get to know each other more since you're new. ";
		        String Ki3 = "You look at Olivia panicking beside you.";
		        String Ki4 = "Olivia: What should we do??";
		      println("");
		    print("Lily : ");
		        for (char letter : Ki1.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Professor Ronald");
		        for (char letter : Ki2.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println("");
		        for (char letter : Ki3.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Olivia : ");
		        for (char letter : Ki4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println("");
		        println("(1)Knock on the door and tell professor Ronald that another professer needs him.");
		        println("(2)Don't say anything.");
		        println("");
		        print("action: ");
		        int choice3 = sk.nextInt();
		        switch(choice3) {
		        case 1:
		        	println(" ");
		        	String kj1 = "You knocked on the door and you see a big figure opening "
		        			+ "    the door as it shows Professor Ronald giving you a \r\n"
		        			+ "    confused look, you saw Lily looking at you looking relieved. ";
		        	String kj2 = " Do you need anything mc?";
		        	String kj3 = "I heard Mrs Phia needs you in the gym room, she needs you right away.";
		        	String kj4  = "";
 
 
 
		        	println(" ");
			        for (char letter : kj1.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        print("Professor Ronald : ");
			        for (char letter : kj2.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        print(player + " : ");
			        for (char letter : kj3.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        print("Professor Ronald : ");
			        for (char letter : kj4.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println("");
			        println(" ");
		      		print("PRESS ENTER");
		      		sk.nextLine();
		        	String kl1 = "The Professor gives Lily an obscene look before walking out to go to the gym.\r\n"
		        			+ "         Lily runs up to you and hugged you while she's trembling.";
		        	String kl2 = "It's fine.. You'll be fine.";
		        	String kl3 = "Olivia joins the hug.";
 
 
		        	 println(" ");
				        print(" ");
				        for (char letter : kl1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        print(player + " : ");
				        for (char letter : kl2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        print(" ");
				        for (char letter : kl3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
		        }
	        case 2:
	        	println("");
	        	String ko = " Let's wait for her plus we haven't finished our food, stop wasting food Olivia ";
	        	String ko1 = "But im curious ";
	        	String ko2 = "There's nothing wrong about our professor calling her in his office like i said";
	        	String ko3 = "     she's probably fixing something because she transferred,";
	        	String ko4 = "     finish your food you said you we're hungry earlier?";
	        	String ko5 = " Fine fine..";
	        	String ko6 = "*giggles while looking at Olivia.";
	            String ko7 = "* The bell rang in a few minutes. *";	
 
	        	println(" ");
		        print(player + " : ");
		        for (char letter : ko.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Olovia : ");
		        for (char letter : ko1.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ko2.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ko3.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ko4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Olovia : ");
		        for (char letter : ko5.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print(player + " : ");
		        for (char letter : ko6.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print(" ");
		        for (char letter : ko7.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
 
	        	println("");
		      		print("PRESS ENTER");
		      		sk.nextLine(); 
	        	String ok = "A few classes went by You and Olivia noticed that Lily looked like she was staring into space.";
 
	           String ok1 = player + " : decided to walk up to Lily..";
 
	           println(" ");    
		        for (char letter : ok.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ok1.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        String ok2 = "Are you okay Lily? How was your talk with Professor Ronald earlier?";
		        String ok3 = "       you also came a little late so we";
		        String ok4 = "       went inside the classroom first.";
 
 
		        println(" ");
		        print(player + " : ");
		        for (char letter : ok2.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ok3.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ok4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println("");
		        println(" ");
	      		print("PRESS ENTER");
	      		sk.nextLine(); 
		        String ok5 = "Lily looks at you with no expression, you noticed that";
		        String ok6 = "she looked less livelier and she looks very pale.";
		        String ok7 = "Lily opened her mouth to respond to your questions.";
		        String ok8 = "Yea, im.. fine.";
		        String ok9 = "    Our talk was ok.";
 
		        println(" ");
		        for (char letter : ok5.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ok6.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ok7.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Lily : ");
		        for (char letter : ok8.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : ok9.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println("");
		        println(" ");
	      		print("PRESS ENTER");
	      		sk.nextLine(); 
	      		String po = "She fixes her things while telling you.";
	      		String po1 = "Olivia walks up and looks at her asking her";
	      		String po2 = "You look pale Lily, are you okay? ";
	      		String po3 = "Olivia was about to touch her cheeks to see if she was hot or not, Lily flinched.";
	      		String po4 = " I-";
	      		String po5 = " I have to go.. I'm sorry.";
	      		String po6 = "Lily runs out of the classroom..";
	      		String po7 = "    You and Olivia looked worried but shrugged it off and went home..";	
	      		println(" ");
		        for (char letter : po.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : po1.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Olivia : ");
		        for (char letter : po2.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : po3.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Olivia : ");
		        for (char letter : po4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Lily : ");
		        for (char letter : po5.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : po6.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : po7.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println("");
		        println(" ");
	      		print("PRESS ENTER");
	      		sk.nextLine();
	      		System.out.print("* Next Day *");
	            for (int i = 0; i < 3; i++) {
	                try {
	                    Thread.sleep(1000);
	                    System.out.print(".");
	                } catch (InterruptedException e) {
	                    e.printStackTrace();
	                }
	            }
		        String k2 = "You walk in the classroom to see Lily Staring into space again.";
		        String k3 = "You put your bag down in your seat and wondered to yourself why she's wearing a jacket ";
		        String k4 = "when its hot since its summer time and you don't have any ac around the school except the teachers office..";
		        String k5 = "You decided to talk to Lily again to check if she's okay.. ";
		        print(" ");
 
 
		        println(" ");
		        println("");
		        for (char letter : k2.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : k3.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        for (char letter : k4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : k5.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        String l1 = player + " : tapped Lily's shoulder, Lily's looked at" + player + "terrified and scared.";
		        String l2 = "Calm down, Are you okay??";
		        String l3 = " I-I'm fine..";
		        String l4 = "Silence fills the whole classroom as it was just the two of you right now..";
 
 
		        println(" ");
		        println(" ");
		        for (char letter : l1.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print(player + " : ");
		        for (char letter : l2.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        print("Lily : ");
		        for (char letter : l3.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println(" ");
		        println(" ");
		        for (char letter : l4.toCharArray()) {
		 	       	    System.out.print(letter);
		 	       	    try {
		 	       	        Thread.sleep(100);
		 	       	    } catch (InterruptedException e) {
		 	       	        System.out.println("Sleep was interrupted");
		 	       	    }
		 	       	}
		        println("");
		        println(" ");
	      		print("PRESS ENTER");
	      		sk.nextLine();
		        String l5 = "Lily excused herself to the bathroom..";
		        String l6 = player + " got worried so she followed Lily to the bathroom";
		         String l7 = "but she got greeted";
		         String l8 = "by Professor Ronald and Lily talking in the hallway..";
 
		         println(" ");
			        println(" ");
			        for (char letter : l5.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        println(" ");
			        for (char letter : l6.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        for (char letter : l7.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        for (char letter : l8.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println("");
			        println(" ");
		      		print("PRESS ENTER");
		      		sk.nextLine();
		      		String p1 = "What are they talking about.. ";
		      		String p2 = player + " was backing up when she bumped into the trashcan that made a noise."; 
			        String p3 =  player + " panickly looked at the trashcan then at the two of them. ";
			        String p4 = player + " saw Lily's terrified face and Professor Ronalds Angry Face as if they we're hiding something.";
 
			        println(" ");
			        println( player + " : ");
			        for (char letter : p1.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        println(" ");
			        for (char letter : p2.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        println(" ");
			        for (char letter : p3.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        println(" ");
			        for (char letter : p4.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        String p5 = "Professor Ronald's face calmed and greeted you Goodmorning";
			        String p6 = "                   and walked to his office";
			        String p7 = "                   while Lily ran back to the classroom leaving you with the messy trash you bumped into.";
			        String p8 = "Man...";
			        println(" ");
			        println(" ");
			        for (char letter : p5.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        for (char letter : p6.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        for (char letter : p7.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
 
			        println(" ");
			        print(player + " : ");
			        for (char letter : p8.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
		      		print("PRESS ENTER");
		      		sk.nextLine();
			        println("");
			        System.out.print("* Time skips to Recess. *");
		            for (int i = 0; i < 3; i++) {
		                try {
		                    Thread.sleep(1000);
		                    System.out.print(".");
		                } catch (InterruptedException e) {
		                    e.printStackTrace();
		                }
		            }
			        String h1 = "You And Olivia we're sitting on a table eating when Olivia asks you..";
		            String h2 = "Where's Lily????";
		            String h3 = "I have no idea Olivia, she's been acting strange.";
		            String h4 = "I hope she's fine..";
 
 
		            println(" ");
			        println("  ");
			        for (char letter : h1.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        print("Olivia : ");
			        for (char letter : h2.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(130);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}     
			        println(" ");
			        print(player + " : ");
			        for (char letter : h3.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(120);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	} 
			        println(" ");
			        print("Olivia : ");
			        for (char letter : h4.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(130);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	} 
			        String h5 = "Both of them shrugged it off and continued to eat and talk about a different topic.";
			        String h6 = "I have to go to the bathroom, can you wait for me? ";
			        String h7 = "Sure, just be fast the bell is about to ring we have to go to our classroom soon.";
			        String h8 = "I will!~";
			        String h9 = "You see Olivia make her way to the bathroom while you finish your food.";
 
			        println(" ");
			        print(" ");
			        for (char letter : h5.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	} 
			        println(" ");
			        print("Olivia : ");
			        for (char letter : h6.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	} 
			        println(" ");
			        print(player + " : ");
			        for (char letter : h7.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        print("Olivia : ");
			        for (char letter : h8.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	}
			        println(" ");
			        println(" ");
			        for (char letter : h9.toCharArray()) {
			 	       	    System.out.print(letter);
			 	       	    try {
			 	       	        Thread.sleep(100);
			 	       	    } catch (InterruptedException e) {
			 	       	        System.out.println("Sleep was interrupted");
			 	       	    }
			 	       	} 
			        println(" ");
		      		print("PRESS ENTER");
		      		sk.nextLine();
		      		String r1 = "* OLIVIA'S POV * ";
		      		String r2 = "Olivia went in an empty stall when she heard crying that sounded like..";	
		      		String r3 = "Lily???...";
		      		String r4 = "Olivia whispers to herself...";
		      		String r5 = "Olivia finished and decided to take a peak in a crack on the door..";
		      		String r6 = "She gasped at what she saw..";	
 
		      		 println(" ");
				        println(" ");
				        for (char letter : r1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(" ");
				        for (char letter : r2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println("Olivia : ");
				        for (char letter : r3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(200);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(" ");
				        for (char letter : r4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(" ");
				        for (char letter : r5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(" ");
				        for (char letter : r6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
			      		print("PRESS ENTER");
			      		sk.nextLine();
			      		String q1 = player + " POV ";
				        String q2 = "You see Olivia walking back to you and she looked shocked..";
				        String q3 = "Olivia, are you okay? did something happen there?";
				        String q4 = "No, I'm fine i just saw uhm..";
				        String q5 = "Saw what?? ";
				        String q6 = " I just saw Lily-";
 
				        println(" ");
				        println(" ");
				        for (char letter : q1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(" ");
				        for (char letter : q2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(player + " : ");
				        for (char letter : q3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println("Olivia : ");
				        for (char letter : q4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(player + " : ");
				        for (char letter : q5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println("Olivia : ");
				        for (char letter : q6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
			      		print("PRESS ENTER");
			      		sk.nextLine();
			      		String q7 = "Olivia gets cut off by the bell ";
			      		String  q8 = "* BELL RINGS *";
			      		String q9 = " Tell me later, Let's get to class.";
			      		String w1 = "Olivia nods.";
 
			      		println(" ");
				        println(" ");
				        for (char letter : q7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(" ");
				        for (char letter : q8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(player + " : ");
				        for (char letter : q9.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
				        println(" ");
				        println(" ");
				        for (char letter : w1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        print("PRESS ENTER");
			      		sk.nextLine();
			      		String x1 = "*During Class* ";
			      		String  x2 = "You noticed olivia looking at lily with a worried expression then you look at lily who looks so pale and staring into space again.";
			      		String x3 = " *After Class*";
 
                                        println(" ");
				        println(" ");
				        for (char letter : x1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : x2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : x3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}       
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String z1 = "You were fixing your things and you saw Olivia and Lily talking...";
                                        String z2 = "You watched them talk, not interfering in their conversation.";
                                        String z3 = "Lily pushed Olivia away as she runs out of the classroom..once again.";
                                        String z4 = "You rush to Olivia who was on the ground and helped her get up while helping her you asked..";
 
                                         println(" ");
				        println(" ");
				        for (char letter : z1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" ");
				        for (char letter : z2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" ");
				        for (char letter : z3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" ");
				        for (char letter : z4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String v1 =  "Dude.. What is with Lily?";
                                        String v2 = "I don't know.";
                                        String v3 = player + "Let's go home.";
                                        String v4 = "You and Olivia went to get your things and went home..";
                                         println(" ");
				        println("player + : ");
				        for (char letter : v1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                         println(" ");
				        println("Olivia :");
				        for (char letter : v2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println("Player + : ");
				        for (char letter : v3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : v4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println(" PRESS ENTER");
                                        sk.nextLine();
                                        String c1 = "*A WEEK HAS PASSED";
                                        String c2 = "You went inside the classroom to expect Lily sitting in her seat but she wasn't there.. again.";
                                        String c3 = "You went to put your bag down on your seat to see Olivia entering the classroom and also expectiong to see Lily in her seat.";
                                        String c4 = "Olivia pulls a chair infront of you and started a conversation about Lily.";
 
                                        println(" ");
				        println(" ");
				        for (char letter : c1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : c2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : c3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : c4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String s1 = "Do you think she's okay?";
                                        String s2 = "Who? Lily?";
                                        String s3 = "Yeah...";
                                        String s4 = "She's probably handling something she was acting so strange last week.";
                                        String s5 = "Can we visit her?";
 
                                        println(" ");
				        println(" Olivia :");
				        for (char letter : s1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" Player + :");
				        for (char letter : s2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" Olivia :");
				        for (char letter : s3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" Player + :");
				        for (char letter : s4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" Olivia :");
				        for (char letter : s5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                println("");
	       println("");
	       println("(1) Sure, let's ask Professor Ronald for her address after class.");
	       println("(2) No, we miht get in trouble.");
	       println("");
	       print("Action: ");
	       int waa = sk.nextInt();
	       switch(waa) {
	       case 2:
                   break;
               }
 
                   String mac1 = "Olivia nods and smiles and puts back the chair she pulled and goes back to her seat";
                   String mac2 = "*AFTER CLASS*";
                   String mac3 = "You and Olivia made your way to professor Ronalds office to ask for Lilys address..";
                   String mac4 = "Olivia knocks at professor Ronalds office door";
 
                                    println(" ");
				        println(" ");
				        for (char letter : mac1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : mac2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : mac3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : mac4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String sophia = "Ah.. it's just you two, w-what do you need?";
                                        String sophiaa = "We wanted to know Lily's Address Professor do you have it? ";
                                        String sophiaaa = "w-what for?.....";
                                        String sophiaaaa = "Uhm..";
                                        String sophiaaaaa = "Olivia looks at you signaling for you to make up an excuse.";
                                        String sophiaaaaaa = "Uhm we need it for uh..";
                                        String sophiaaaaaaa = "SCHOOL PROJECT! we we're assigned to be her groupmates by our teachers professor. ";
                                        String sophiaaaaaaaa = "Yea! so we need her address and she's been absent already for a week.";
                                        String sophiaaaaaaaaa = "You noticed that Professor Ronald seem paranoid about something..";
                                        String sophiaaaaaaaaaa = "Ah.. is that so.. give me a minute.";
 
                                        println(" ");
				        println("Profosser Ronald : ");
				        for (char letter : sophia.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println("Olivia : ");
				        for (char letter : sophiaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" Professor Ronald :");
				        for (char letter : sophiaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println("Olivia : ");
				        for (char letter : sophiaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : sophiaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println("Player + : ");
				        for (char letter : sophiaaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
				        println(" ");
				        for (char letter : sophiaaaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println("Olivia : ");
				        for (char letter : sophiaaaaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println(" ");
				        for (char letter : sophiaaaaaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
				        println("Professor Ronald : ");
				        for (char letter : sophiaaaaaaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String phia = "* A few minutes passes by.. *";
                                        String phiaa = "* What is taking him sooo longg.. *";
                                        String phiaaa = "Be patient you wanted to visit Lily.";
                                        String phiaaaa = "You also wanted to check on her!";
                                        String phiaaaaa = "I'm worried but i wasn't planning on going to her house!";
                                        String phiaaaaaa = "BUT-";
 
                                        println(" ");
                                        println(" ");
				        for (char letter : phia.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("Olivia : ");
				        for (char letter : phiaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                         println("Player + : ");
				        for (char letter : phiaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                         println("Olivia : ");
				        for (char letter : phiaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                         println("Player + : ");
				        for (char letter : phiaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                         println("Olivia : ");
				        for (char letter : phiaaaaaa.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String zx1 = "Professor Ronald goes out of the office and gave You and Olivia Lily's Address.";
                                        String zx2 = "Here's her address..";
                                        String zx3 = "You and Olivia both thanked Professor Ronald before leaving..";
                                        String zx4 = "* OUTSIDE THE SCHOOL * ";
 
                                        println(" ");
                                        println(" ");
				        for (char letter : zx1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println("Professor Ronald : ");
				        for (char letter : zx2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : zx3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : zx4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String xc1 = "You and Olivia are making your way to Lily's house while walking you started a conversation about Professor Ronald";
                                        String xc2 = "Don't you think Professor Ronald looked a bit...";
                                        String xc3 = "Paranoid?..";
                                        String xc4 = "It's probably just you and your silly mind playing with you.";
                                        String xc5 = "You shrugged it off while You and Olivia we're walking to Lily's house.";
                                        String xc6 = "* AT OLIVIA'S HOUSE * ";
 
                                        println(" ");
                                        println(" ");
				        for (char letter : xc1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("Player + : ");
				        for (char letter : xc1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" : ");
				        for (char letter : xc3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("Olivia : ");
				        for (char letter : xc4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : xc5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : xc6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String cv1 = "* AT LILY'S HOUSE *";
                                        String cv2 = "You knocked at their door while Olivia was behind you.";
                                        String cv3 = "You saw a small old lady figure opening the door who looks so worried";
 
                                        println(" ");
                                        println(" ");
				        for (char letter : cv1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : cv2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : cv3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String vb1 = "Is this Lily's house";
                                        String vb2 = "Who are you??";
                                        String vb3 = "We're Lily's classmates.. Can we see Lily for a school project";
                                        String vb4 = "Ah.. Lily hasn't come out of her room but come in come in";
 
                                        println(" ");
                                        println("Olivia : ");
				        for (char letter : vb1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Old lady : ");
				        for (char letter : vb2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Olivia : ");
				        for (char letter : vb3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Old lady : ");
				        for (char letter : vb4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String bn1 = "You and Olivia went inside and sat on the crouch as the small old lady was giving you water... She sat on the other couch";
                                        String bn2 = "I'm lily's Mother, She hasn't been going out of her room since last week..";
                                        String bn3 = " I wanted to go to your school to ask if something happened to her but you two came.";
                                        String bn4 = "Has she been eating?";
                                        String bn5 = "I'm not sure.. I leave her food outside her door and she takes it but today she didn't take her food. ";
                                        String bn6 = "I've been asking her to come out but she keeps saying that she's not feeling well..";
                                        String bn7 = " I'm worried about my baby..";
                                        String bn8 = "Do you have a key for her room? ";
                                        String bn9 = " I think i do.. i didn't unlock her door since i wanted her to rest..";
                                        String bn10 = "Lily's Mother stands up to find her key to her daughters room..";
 
 
                                         println(" ");
                                        println(" ");
				        for (char letter : bn1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Old lady : ");
				        for (char letter : bn2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Lily's Mother ");
				        for (char letter : bn3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("player + : ");
				        for (char letter : bn4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Lily's Mother : ");
				        for (char letter : bn5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" : ");
				        for (char letter : bn6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" : ");
				        for (char letter : bn7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Player + : ");
				        for (char letter : bn8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Lily's Mother : ");
				        for (char letter : bn9.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : bn10.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String nm1 = "Lily's Mother gave the key to MC.";
                                        String nm2 = "Please check up on her, im really worried. ";
                                        String nm3 = "Since you two are friends with her, she might open up to you.";
                                        String nm4 = "Olivia asked you to stay in the living room and only Olivia will check up on Lily to lessen the pressure for Lily..";
                                        String nm5 = "Olivia took the key and went up to her room.";
                                        String nm6 = "You we're helping Lily's mother with some food she's preparing when you heard Olivia scream ";
                                        String nm7 = "You ran up to see her shocked and crying while she fell on the floor with the door open infront of her.";
 
                                        println(" ");
                                        println(" ");
				        for (char letter : nm1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println("Lily's Mother : ");
				        for (char letter : nm2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" : ");
				        for (char letter : nm3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : nm4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : nm5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : nm6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : nm7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String se1 = "You ran to Olivia just to see Lily hanging and food scattered around her room, you can feel your legs trembling ";
                                        String se2 = "when you saw Lily's body hanging still and so many cuts around her arms and food her mom put infront of her door scattered.. ";
                                        String se3 = "everything was scattered around her room.. everything was messy..";
                                        String se4 = "her floor was full of blood with a chair on the middle.. her phone was on the floor, and it was open";
                                        String se5 = "You looked her at her face terrified..Her face was pale.. ";
                                        String se6 = "Her eyes looked swollen which made it look like she's been crying for days..";
                                        String se7 = "You can't help but also cry with what you witnessed.. ";
                                        String se8 = "You tell yourself while looking at her that you wanted to be her friend..you wanted to laugh with her..you wanted to be close to her.. ";
                                        String se9 = "All you can hear was Olivia's sob.. ";
                                        String se10 = "you saw her mother walking up the stairs with food tray in her hand..";
 
                                         println(" ");
                                        println(" ");
				        for (char letter : se1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se9.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : se10.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
 
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String jk1 = "Lily's mother walked up to you to see the same thing.. ";
                                        String jk2 = "silence fills the room all you can hear was the food tray dropped and a mother running up to her daughter";
                                        String jk3 = "* YOU CALLED AN AMBULANCE *";
                                        String jk4 = "You saw Lily's dead body getting taken.";
                                        String jk5 = "All you can hear around you was ambulance sirens and the sobbing of Olivia and Lily's mother behind you.";
                                        String jk6 = "The police also arrived to investigate some things in Lily's room.";
                                        String jk7 = "Her death came out as Suicide that makes the case closed since she didn't die because of murder";
                                        String jk8 = "but here are the things we found in her room";
                                        String jk9 = "The police gave you Lily's Phone and A book.";
 
                                         println(" ");
                                        println(" ");
				        for (char letter : jk1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : jk2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : jk3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : jk4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : jk5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : jk6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("Police : ");
				        for (char letter : jk7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" : ");
				        for (char letter : jk8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : jk9.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                        println(" ");
                                        println("PRESS ENTER");
                                        sk.nextLine();
                                        String abc1 = "That's it? are you not going to investigate further?";
                                        String abc2 = player + "we're only here to investigate, not why she did it";
                                        String abc3 = "We'll take our leave. My deepest condolences to you and their family"; 
                                        String abc4 = "You looked at Lily's Mother who was crying nonstop aswell as Olivia";
                                        String abc5 = "You excused Olivia and gave her some tissues";
                                        String abc6 = "Stay with her for now is that okay? i have to get home.";
                                        String abc7 = "O-okay..";
                                        String abc8 = "You excused yourself to get home";
                                        String abc9 = "* AT YOUR HOUSE *";
                                        String abc10 = "You walked in your room with Lily's book and phone in your hands to look through it";
                                        
                                        println(" ");
                                        println("player + : ");
				        for (char letter : abc1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                         println(" ");
                                        println("Police : ");
				        for (char letter : abc2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                         println(" ");
                                        println("Police 2: ");
				        for (char letter : abc3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                         println(" ");
                                        println(" ");
				        for (char letter : abc4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("player = : ");
				        for (char letter : abc5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                         println(" ");
                                        println("player + : ");
				        for (char letter : abc6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                         println(" ");
                                        println("Olivia : ");
				        for (char letter : abc7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : abc8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : abc9.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : abc10.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                         println("");
	       println("");
	       println("(1) Look at the Phone.");
	       println("(2) Look at the Book.");
	       println("");
	       print("Action: ");
	       int waaa = sk.nextInt();
	       switch(waaa) {
	       case 2:
                   break;
               }
               String qwe1 = "its Lily's diary";
               String qwe2 = "You opened the diary";
               String qwe3 = " DEAR DIARY ";
               String qwe4 = "I got bullied again";
               String qwe5 = "I asked my mother for me to transfer to other school since the bullying got worse..";
               String qwe6 = "i don't know why they would do this me.. ah! My Mother is calling me to eat dinner. I'll write again later after i finish my dinner! bye bye!~";
               String qwe7 = "What...";
               String qwe8 = "You flip to the next page";
               String qwe9 = " DEAR DIARY ";
               String qwe10 = "They threw my things out of the window today.. I really want to leave this school and transfer to a better school";
               String qwe11 = "i worked hard to save money and to buy these cute things too... it's fine i'll just save money again!";
               String qwe12 = "I hope they'll say sorry tomorrow hopefully...";
               String qwe13 = " DEAR DIARY ";
               String qwe14 = "i'll be transferring to another school tomorrow! I'm so excited to meet my new classmates and make new friends!";
               String qwe15 = "I hope they aren't as mean as my classmates here..";
               String qwe16 = " DEAR DIARY ";
               String qwe17 = "People were so nice inside the school, there are a lot of boys calling me pretty.. I feet the girls eyes look at me deadly";
               String qwe18 = "I hope they don't get mad at me like my other classmates in my old school";
               
              
                                        println(" ");
                                        println("player + : ");
				        for (char letter : qwe1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                println(" ");
                                        println(" ");
				        for (char letter : qwe2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : qwe3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : qwe4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : qwe5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : qwe6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println("player + : ");
				        for (char letter : qwe7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                       println(" ");
                                        println(" ");
				        for (char letter : qwe8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : qwe9.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : qwe10.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : qwe11.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
   println(" ");
                                        println(" ");
				        for (char letter : qwe12.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : qwe13.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : qwe14.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : qwe15.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : qwe16.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : qwe17.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : qwe18.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println("do you wish to continue?");
                                        println("1. Yes");
                                        println("2. No");
                                        int nyee = sk.nextInt();
                                        while (true){
                                            if(nyee == 2);
                                            println("");
	       println("");
	       println("(1) Look at the Phone.");
	       println("(2) Look at the Book.");
	       println("");
	       print("Action: ");
	       int missuu = sk.nextInt();
	       switch(missuu) {
                   case 2:
                       break;
               }
               
               String ert1 = "You flip to the next page tearing up.";
               String ert2 = "My professor.. raped me.. i feel so dirty..He was touching me everywhere..";
               String ert3 = "I feel his hands around my body..I feel so disgusted in myself.. ";
               String ert4 = "Why did i let this happen...How can a person do this";
            
               println(" ");
                                        println(" ");
				        for (char letter : ert1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : ert2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : ert3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println(" ");
                                        println(" ");
				        for (char letter : ert4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        println("do you wish to continue?");
                                        println("1. Yes");
                                        println("2. No");
                                        int nye = sk.nextInt();
                                        while (true){
                                            if(nye == 2);
                                            println("");
	       println("");
	       println("(1) Look at the Phone.");
	       println("(2) Look at the Book.");
	       println("");
	       print("Action: ");
	       int missuuu = sk.nextInt();              
               
	       switch(missuuu) {
                   case 2:
                       break;
               }
                       String aww1 = player + "saw me and professor talking in hallway.. I'm scared..";
                       String aww2 = player + "might heard something.. He was blackmailing to be quiet...";
                       String aww3 = "He has the video of me while doing it.. please.. i'm so disgusted with myself..";
                       String aww4 = "You flipped the page crying in anger.";
                       String aww5 = "Olivia saw my cuts..";
                       String aww6 = "I didn't mean to push her away.. I'm sorry I'm sorry";
                       String aww7 = "I'm sorry I'm sorry I'm sorry I'm sorry I'm sorry I'm sorry..";
                       String aww8 = "You see an enveloped labeled MOTHER ";
                       
                        println(" ");
                                        println("Lily ");
				        for (char letter : aww1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                       
                println(" ");
                                        println(" ");
				        for (char letter : aww2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : aww3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : aww4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : aww5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : aww6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : aww7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                          println(" ");
                                        println(" ");
				        for (char letter : aww8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                           println("do you wanna read it?");
                                        println("1. Yes");
                                        println("2. No");
                                        int nyeee = sk.nextInt();
                                        while (true){
                                            if(nyeee == 2);
                                            println("");
	       println("");
	       println("(1) Look at the Phone.");
	       println("(2) Look at the Book.");
	       println("");
	       print("Action: ");
	       int missuuuu = sk.nextInt();              
               
	       switch(missuuuu) {
                   case 2:
                       break;
               }
               String wat1 = "Dear Mother..";
               String wat2 = "I'm sorry.. I'm sorry i left you here in this cruel world..I know how father left us for another family..";
               String wat3 = "Mother I can't do this anymore i feel so disguted with myself and I feel nothing at all..";
               String wat4 = "Mother im tired of crying and feeling disgusted..";
               String wat5 = "I can feel his hands on my body mother..";
               String wat6 = "I don't wanna feel this anymore.";
               String wat7 = "Mother I love you, know that you raised me well and treated me the best..";
               String wat8 = "you were the best mother out there! the world was just too cruel to me.. I'm sorry. ";
               String wat9 = "Goodbye, ma.";
               
                println(" ");
                                        println("Lily : ");
				        for (char letter : wat1.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                     
                                             println(" ");
                                        println(" ");
				        for (char letter : wat2.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : wat3.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : wat4.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : wat5.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : wat6.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : wat7.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : wat8.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                         println(" ");
                                        println(" ");
				        for (char letter : wat9.toCharArray()) {
				 	       	    System.out.print(letter);
				 	       	    try {
				 	       	        Thread.sleep(100);
				 	       	    } catch (InterruptedException e) {
				 	       	        System.out.println("Sleep was interrupted");
				 	       	    }
				 	       	}
                                        
                                        }
                     
                                        }
                                        }
                                        
                                        
                                        
                                        
               
	        }//END OF DINDO'S PART.
        	break;
        case 2:
        	String bad1a = "Sorry I really wanted to take a rest.";
        	String bad1b = "I see, I'll go now "+player+"! Bye.";
        	String bad1c = "Yea, take care Olivia";
        	println("");
            print(player + ": ");
            for (char letter : bad1a.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
        	println("");
            print("Olivia: ");
            for (char letter : bad1b.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        println("Sleep was interrupted");
  	       	    }
  	       	}
            println("");
            print(player + ": ");
            for (char letter : bad1c.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
            System.out.println("");
    		System.out.println("");
    		System.out.print(yellow + "PRESS ENTER" + reset);
    		sk.nextLine();
    		sk.nextLine();
       		String bad2a = "Walking back home";
       		String bad2b = "....";
       		String bad2c = "Maybe I should take a sleep.";
       		println("");
       		for (char letter : bad2a.toCharArray()) {
       		    System.out.print(letter);
       		    try {
       		        Thread.sleep(100);
       		    } catch (InterruptedException e) {
       		        System.out.println("Sleep was interrupted");
       		    }
       		}
       		for (char letter : bad2b.toCharArray()) {
       		    System.out.print(letter);
       		    try {
       		        Thread.sleep(500);
       		    } catch (InterruptedException e) {
       		        System.out.println("Sleep was interrupted");
       		    }
       		}
       		println("");
       		println("");
            print(player + ": ");
            for (char letter : bad2c.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
 
            System.out.println("");
    		System.out.println("");
    		System.out.print(yellow + "PRESS ENTER" + reset);
    		sk.nextLine();
       		String bad3a = "yawning~";
       		String bad3b = "       ohh it's already 6:00.";
       		String bad3c = "*the phone rang*";
       		String bad3d = "Dang it, I missed her call.";
       		String bad3e = "       Wait she left a message.";
       		String bad3f = "      Come here at St. Imy Street in muntinlupa";
       		String bad3g = "         It's raining and I can't go home.";
       		String bad3h = "Ohh really?!...";
       		println("");
            print(player + ": ");
            for (char letter : bad3a.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
            println("");
            for (char letter : bad3b.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
            println("");
            println("");
            for (char letter : bad3c.toCharArray()) {
  	       	    System.out.print(letter);
  	       	    try {
  	       	        Thread.sleep(100);
  	       	    } catch (InterruptedException e) {
  	       	        System.out.println("Sleep was interrupted");
  	       	    }
  	       	}
        println("");
        println("");
        print(player + ": ");
        for (char letter : bad3d.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        for (char letter : bad3e.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
 
        System.out.println("");
        System.out.println("");
		System.out.println("");
		System.out.print(cyan + "PRESS ENTER TO VIEW THE MESSAGE." + reset);
		sk.nextLine();
   		println("");
        for (char letter : bad3f.toCharArray()) {
       	    System.out.print(letter);
       	    try {
       	        Thread.sleep(100);
       	    } catch (InterruptedException e) {
       	        System.out.println("Sleep was interrupted");
       	    }
       	}
        println("");
        for (char letter : bad3g.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        println("");
        print(player + ": ");
        for (char letter : bad3h.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        System.out.println("");
		System.out.println("");
		System.out.print(yellow + "PRESS ENTER" + reset);
		sk.nextLine();
 
   		String bad4a = "*Walking*";
   		String bad4b = "         ";
   		String bad4c = "*knocks at the door*               ";
   		String bad4d = "Olivia?! Hello?!";
   		String bad4e = "       Is anyone there?!";
   		String bad4f = "       Is this the right house?";
   		String bad4g = "       Ohh the door is open.";
   		//changed part.
   		String bad4i = "*" + player + " saw body of olivia and another girl lying on the ground*.";
   		String bad4j = "      ";
   		String bad4k = "Wha-";
   		String bad4l = "       You're joking me right?";
   		String bad4m = "       Is this some sort of a prank?";
 
   		println("");
        for (char letter : bad4a.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        println("");
        System.out.print("encountered a man in a coat");
        for (int i = 0; i < 3; i++) {
            try {
                Thread.sleep(1000);
                System.out.print(".");
            } catch (InterruptedException e) {
                e.printStackTrace();
            }
        }
        println("");
        println("");
        for (char letter : bad4b.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(200);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        for (char letter : bad4c.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        println("");
        print(player + ": ");
        for (char letter : bad4d.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(200);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        for (char letter : bad4e.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(200);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        for (char letter : bad4f.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        for (char letter : bad4g.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        println("");
        System.out.print("Entering the House");
        for (int i = 0; i < 3; i++) {
            try {
                Thread.sleep(1000);
                System.out.print(".");
            } catch (InterruptedException e) {
                e.printStackTrace();
            }
        }
        println("");
        println("");
        for (char letter : bad4i.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        println("");
        for (char letter : bad4j.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(200);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        print(player + ": ");
        for (char letter : bad4k.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
 
        println("");
        for (char letter : bad4l.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        for (char letter : bad4m.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        println("");
        println("");
        println("(1) Try and check if it's some sort of a prank.");
        println("(2) Call the police.");
        println("");
        print("Action: ");
        int idyot = sk.nextInt();
        switch(idyot) {
        case 1:
        	String wrath1a = "Hey..";
        	String wrath1b = "       Stop it Olivia";
        	String wrath1c = "*Saw a lot of bleeding*";
        	String wrath1d = "Just what happe-..";
        	String wrath1e = "*sudden noise*";
        	String wrath1f = "It's still here.";
        	String wrath1g = "*Runs outside*";
        	String wrath1h1 ="Where is it..";
        	String wrath1h2 ="Huh?";
        	String wrath1i = "*the neighbor saw " + player + " infront of the house.*";
        	String wrath1j = "*Saw a blood on " + player + "'s hand and started to freak out.*";
        	String wrath1k = "There is a someone who's infront of my neighbor's house";
        	String wrath1l = "          there is blood on it's hand, I'm scared please come immediately.";
        	println("");
            print(player + ": ");
            for (char letter : wrath1a.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            for (char letter : wrath1b.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            for (char letter : wrath1c.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            print(player + ": ");
            for (char letter : wrath1d.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            for (char letter : wrath1e.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            print(player + "'s thought: ");
            for (char letter : wrath1f.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            for (char letter : wrath1g.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            print(player + ": ");
            for (char letter : wrath1h1.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            print("Neighbor: ");
            for (char letter : wrath1h2.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            for (char letter : wrath1i.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            for (char letter : wrath1j.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
            System.out.print("Dialing");
            for (int i = 0; i < 3; i++) {
                try {
                    Thread.sleep(1000);
                    System.out.print(".");
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
            }
            println("");
            println("");
            print("Neighbor: ");
            for (char letter : wrath1k.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            for (char letter : wrath1l.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            System.out.println("");
    		System.out.println("");
    		System.out.print(yellow + "PRESS ENTER" + reset);
    		sk.nextLine();
    		sk.nextLine();
 
            println("");
            System.out.print("The police came");
            for (int i = 0; i < 3; i++) {
                try {
                    Thread.sleep(1000);
                    System.out.print(".");
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
            }
            println("");
            println("");
            println("(1) Run away");
            println("(2) Stay");
            println("");
            print("Action: ");
            int Thrill = sk.nextInt();
            switch(Thrill) {
            case 1:
            	println("");
                System.out.print("Running");
                for (int i = 0; i < 3; i++) {
                    try {
                        Thread.sleep(1000);
                        System.out.print(".");
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                }
                println("");
                println("");
                println("at the bottom of the bridge.");
 
                String wait = "          ";
 
                for (char letter : wait.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(200);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
 
                println("");
            	String act1a = "Ohh is it you " + player + "? what are you doing here?";
 
            	println("");
                print("Professor Ronald: ");
                for (char letter : act1a.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
 
                println("");
                println("");
            	println("(1) lie");
                println("(2) Tell him what's happening");
                println("");
                print("Action: ");
                int saytell = sk.nextInt();
            	switch(saytell) {
            	case 1:
            		String in1 = "Nothing Sir Ronald, I'm just passing by.";
            		String in2a = "Stop it "+player+ ", you're all over the news.";
            		String in2b = "                  also,";
            		String in3 = "                  the police is already here to pick you up.";
            		String in4 = "Wait, huh?";
            		String in5 = "You have the right to remain silent.";
            		String in6 = "          Anything you say can and will be used against you in a court of law.";
            		String in7 = "          You have the right to an attorney.";
            		String in8 = "          If you cannot afford one, one will be provided for you.";
            		String in9 = "          Do you understand the rights I have just read to you?";
            		println("");
                    print(player + ": ");
                    for (char letter : in1.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                	println("");
                    print("Professor Ronald: ");
                    for (char letter : in2a.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : in2b.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                    for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
                	println("");
                    for (char letter : in3.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    print(player + ": ");
                    for (char letter : in4.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    print("Officer : ");
                    for (char letter : in5.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(50);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : in6.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(50);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : in7.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(50);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : in8.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(50);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : in9.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(50);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    System.out.println("");
            		System.out.println("");
            		System.out.print(yellow + "PRESS ENTER" + reset);
            		sk.nextLine();
            		sk.nextLine();
 
                    String nonsense =  "    You notice something as you go by the police officers.";
                    String nonsense2 = "The man you encountered and your professor both wore the same coat.";
                    println("");
                    println("");
                    for (char letter : nonsense.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                    println("");
                    for (char letter : nonsense2.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                    println("");
                    println("");
                    println("(1) Resist and confront the mastermind");
                    println("(2) Tell them that he's the one who killed your bestfriend");
                    println("(3) Do nothing");
                    println("");
                    print("Action: ");
                    int nosense = sk.nextInt();
 
                    switch(nosense) {
                    case 1:
                    	println("");
                        print("You resist and attack ronald.");
                        for (int i = 0; i < 3; i++) {
                            try {
                                Thread.sleep(1000);
                                System.out.print(".");
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
                        println("");
                        println("");
                        println("*The police use a stun rod on you, and you fall asleep.*");
                        String a1 =  "         ";
                        for (char letter : a1.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                        System.out.println("");
                		System.out.println("");
                		System.out.print(yellow + "PRESS ENTER" + reset);
                		sk.nextLine();
                		sk.nextLine();
                        println("");
                    	break;
                    case 2:
                    	String a2 =  "It's not me it's him!! He killed my friend!!";
                    	String a2b = "*Nobody believed whatever you said.*";
                    	println(" ");
                    	print(player + ": ");
                    	 for (char letter : a2.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
                    	 println("");
                    	 println(" ");
                    	 for (char letter : a2b.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
                    	 System.out.println("");
                 		System.out.println("");
                 		System.out.print(yellow + "PRESS ENTER" + reset);
                 		sk.nextLine();
                 		sk.nextLine();
                    	break;
                    case 3:
                    	println("");
                    	String a2c = "*You didn't do anything else and accepted that you'd been framed.*";
                    	for (char letter : a2c.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
                        for (int i = 0; i < 3; i++) {
                            try {
                                Thread.sleep(1000);
                                System.out.print(".");
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
                        System.out.println("");
                		System.out.println("");
                		System.out.print(yellow + "PRESS ENTER" + reset);
                		sk.nextLine();
                		sk.nextLine();                    	
                        break;
                    }
                    println("");
                    println("");
                	print("At the Prison");
                    for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
 
                    String arch1 = "I promise, I'll help you.";
                    String arch2 = "Help?";
                    String arch3 = "       Help..";
                    String arch4 = "       I don't care anymore.";
                    String arch5 = "       My friend died and now I'm here..";
                    String arch6 = "       There's nothing I can do anymore.";
 
                    println("");
                    println("");
                    print("Attorney: ");
                	for (char letter : arch1.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : arch2.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : arch3.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : arch4.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : arch5.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : arch6.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	String arch100 = "There is..";
                	String arch101 = "No, There's nothing I can do anymore!!";
                	String arch102 = "Your friend will never get the justice they need if you keep doing that.";
                	String arch103 = "But...";
 
                	println("");
                    print("Attorney: ");
                	for (char letter : arch100.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : arch101.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print("Attorney: ");
                	for (char letter : arch102.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : arch103.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
 
 
                	System.out.println("");
            		System.out.println("");
            		System.out.print(yellow + "PRESS ENTER" + reset);
            		sk.nextLine();
 
                    String archa = "I'll help you";
                    String archb = "Help me?";
                    String archc = "yes, I'm the most smart attorney you can find.";
                    String archd = "          so dont worry..";
                    String arche = "          trust me okay?.";
 
                    println("");
                    print("Attorney: ");
                	for (char letter : archa.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : archb.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print("Attorney: ");
                	for (char letter : archc.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : archd.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : arche.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	System.out.println("");
            		System.out.println("");
            		System.out.print(yellow + "PRESS ENTER" + reset);
            		sk.nextLine();
 
                    println("");
                    println("");
                    print("At the attorney's room");
                    for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
                    println("");
                    String hm = "Such a horrible event.. is that child going to be okay?";
 
                    println("");
                    print("Attorney: ");
                	for (char letter : hm.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    println("");
                    print("Someone clicked the doorbell");
                    for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
                    println("");
                    String hmm = "Hmm..";
                    String hmmm = "      ";
                    println("");
                    println("");
                    print("Attorney: ");
                	for (char letter : hmm.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
 
                    println("");
                	for (char letter : hmmm.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
 
                	println("");
                	println("");
                    print("*Sound of Gunshots*");
                    for (int i = 0; i < 5; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
                    println("");
                    println("");
                    String deathofatt = "Three days later after the attorney died..";
                    for (char letter : deathofatt.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                    println("");
                    println("");
                    print("At the court.");
                    for (int i = 0; i < 5; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
 
                    String court = "Having been found guilty of two counts of first-degree murder,";
                    String court2 = "       it is the judgment of this court that you are sentenced to death";
                    String court3 = "       by the method prescribed by law.";
 
                    println("");
                	println("");
                    print("Judge: ");
                    for (char letter : court.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : court2.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : court3.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    System.out.println("");
            		System.out.println("");
            		System.out.print(yellow + "PRESS ENTER" + reset);
            		sk.nextLine();
                    println("");
                    BadEnding();
                    println("");
                    println("");
                    print(bloom + "PRESS ENTER TO GO BACK IN THE MAIN MENU." + reset);
                    sk.nextLine();
                	 continue;
            	case 2:
 
            		String c2 = "Sir ronald help! I'm being chased by the police.";
            		String c2a = "What? why?";
            		String c2b = "Olivia was murdered, and they framed me, believing I was the perpetrator.";
            		String c2c = "I understand, Come with me " + player + " I'll help you.";
 
            		println("");
                    print(player + ": ");
                	for (char letter : c2.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
 
            		println("");
                    print("Professor Ronald: ");
                    for (char letter : c2a.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    print(player + ": ");
                	for (char letter : c2b.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print("Professor Ronald: ");
                    for (char letter : c2c.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
 
                    System.out.println("");
             		System.out.println("");
             		System.out.print(yellow + "PRESS ENTER" + reset);
             		sk.nextLine();
             		sk.nextLine();
 
             		println("");
                    println("");
                    print("At Professor Ronald's House");
                    for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
 
                	println("");
                	String err = "You okay boy?";
 
                	println("");
                    print("Professor Ronald: ");
                    for (char letter : err.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
 
                    println("");
                    println("");
                    println("(1) Do I look okay?");
                    println("(2) Yep thanks a lot sir.");
                	println("");
                	print("Action: ");
                    int aa = sk.nextInt();
                	switch(aa) {
                	case 1:
                		String aa1 = "Okay? Do I look Okay to you?";
                		String aa2 = "       My friend died and now I'm being hunt by the police.";
                		println("");
                        print(player + ": ");
                    	for (char letter : aa1.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
                    	println("");
                    	for (char letter : aa2.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
                    	System.out.println("");
                 		System.out.println("");
                 		System.out.print(yellow + "PRESS ENTER" + reset);
                 		sk.nextLine();
                    	sk.nextLine();
 
                		break;
                	case 2:
                		String aa3 = "Yep, thanks a lot sir.";
                		String aa4 = "Don't worry about that kid.";
 
                		println("");
                		print(player + ": ");
                    	for (char letter : aa3.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
                    	println("");
                    	print("Professor Ronald: ");
                    	for (char letter : aa4.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
 
                		break;
                	}
 
                	String lucien1 = "Wait there, I'll make you a coffee.";
                    String lucien2 = "Wait isn't that..";
 
 
                	println("");
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : lucien1.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
 
                	println("");
                    println("");
                    print("While waiting");
                    for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
                    println("");
                    println("");
                    print(player + "'s thought: ");
                	for (char letter : lucien2.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
 
                	String lucien =  "                          You noticed that";
                    String loujhille = "The man you encountered and your professor both wore the same coat.";
                    println("");
                    println("");
                    for (char letter : lucien.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                    println("");
                    for (char letter : loujhille.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                	println("");
                	String loujhille1 = "Thankyou for waiting, here's your coffee.";
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : loujhille1.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	System.out.println("");
             		System.out.println("(1) Attack him");
             		System.out.println("(2) Stay calm");
             		System.out.println("");
             		println("");
             		print("Action: ");
             		int sc = sk.nextInt();
             		switch(sc) {
 
             		case 1:
                    println("");
                    println("");
                    println("*You pushed him onto the floor*");
                    space();
 
                    String lol = "You monster!!";
                    String lol2 = "So you already notice huh? HAHAHAHAH";
                    String lol3 = "Why did you do that?!!";
                    String lol4 = "Why you say?";
                    String lol5 = "                  you know what? I really like Lily";
                    String lol6 = "the new student?";
                    String lol7 = "yea, but your friend started to hang out with her.";
                    String lol8 = "huh?";
                    String lol9 = "I can't have fun with her because of that.";
                    String lol10 = "Is that the reason why you killed them both?";
                    String lol11 = "yes, I mean your friend deserve that you know?";
                    String lol12 = "You piece of-..";
                    String lol13 = "*laugh without feeling a single guilt*";
                    String g = "*The professor grabbed something and hit you*";
 
 
                    println("");
                    print(player + ": ");
                	for (char letter : lol.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : lol2.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : lol3.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : lol4.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : lol5.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : lol6.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : lol7.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : lol8.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : lol9.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : lol10.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : lol11.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                    print(player + ": ");
                	for (char letter : lol12.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : lol13.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
                	}
                	println("");
                	println("");
                	for (char letter : g.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
                	}
                	space();
 
 
                	System.out.println("");
             		System.out.println("");
             		System.out.print(yellow + "PRESS ENTER" + reset);
             		sk.nextLine();
             		sk.nextLine();
 
                    break;
             		case 2:
 
             			String spedup = "*Silence";
             			println("");
             			for (char letter : spedup.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }
             	       	}
             			println("");
                    	print("You drank the coffee.");
                    	for (int i = 0; i < 3; i++) {
                            try {
                                Thread.sleep(1000);
                                System.out.print(".");
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
 
                    	String ask = "What's happening?";
                    	String ask2 = "       I suddenly felt sleepy.";
 
                    	println("");
                        print(player + ": ");
                    	for (char letter : ask.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }  
             	       	}
                    	println("");
                    	for (char letter : ask2.toCharArray()) {
             	       	    System.out.print(letter);
             	       	    try {
             	       	        Thread.sleep(100);
             	       	    } catch (InterruptedException e) {
             	       	        System.out.println("Sleep was interrupted");
             	       	    }  
             	       	}
                    	println("");
                    	print(player + " fell off the chair.");
                    	for (int i = 0; i < 3; i++) {
                            try {
                                Thread.sleep(1000);
                                System.out.print(".");
                            } catch (InterruptedException e) {
                                e.printStackTrace();
                            }
                        }
 
                    	System.out.println("");
                 		System.out.println("");
                 		System.out.print(yellow + "PRESS ENTER" + reset);
                 		sk.nextLine();
 
 
             			break;
             		}
 
             		String ab = "What happen?";
             		String ac = "       Where am I..";
             		String ad = "       Ohh right..";
             		String ae = "Where are you!";
             		String af = "       you demonic being!!";
             		String ag = "       How dare you killed my friend!!";
             		String ah = "       you monster..";
 
             		println("");
                    print(player + ": ");
                	for (char letter : ab.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : ac.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : ad.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	println("");
                	print("*started to go berserk*");
                	for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
                	println("");
                	println("");
                	print(player + ": ");
                	for (char letter : ae.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(80);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : af.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(70);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : ag.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(90);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : ah.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	print("*" + player + "cried*");
                	for (int i = 0; i < 3; i++) {
                        try {
                            Thread.sleep(1000);
                            System.out.print(".");
                        } catch (InterruptedException e) {
                            e.printStackTrace();
                        }
                    }
 
                	String mm = "Ohh stop it " + player;
                	String mm1 = "                  Don't cry..";
 
                	println("");
                    print("Professor Ronald: ");
                    for (char letter : mm.toCharArray()) {
            	       	    System.out.print(letter);
            	       	    try {
            	       	        Thread.sleep(100);
            	       	    } catch (InterruptedException e) {
            	       	        System.out.println("Sleep was interrupted");
            	       	    }
            	       	}
                    println("");
                    for (char letter : mm1.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
 
                	String mm2 = "Olivia, I'm so sorry. this isn't going to happen if I join you to find lily.";
                	String mm3 = "       You're not going to die.. ";
                	String mm4 = "       if only..";
                	String mm5 = "       If only I was there with you..";
                	String mm6 = "*smirked*";
 
                	space(); space();
 
                	println("");
                    print(player + ": ");
                	for (char letter : mm2.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : mm3.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : mm4.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
                	println("");
                	for (char letter : mm5.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
         	       	}
 
                	println("");
                	print("Professor Ronald: ");
                	for (char letter : mm6.toCharArray()) {
         	       	    System.out.print(letter);
         	       	    try {
         	       	        Thread.sleep(100);
         	       	    } catch (InterruptedException e) {
         	       	        System.out.println("Sleep was interrupted");
         	       	    }
                	}
                	space();
                	println("");
                	println("");
                	println("*Gunshots*");
                	println("");
                	println("");
                	space();
                	System.out.println("");
             		System.out.println("");
             		System.out.print(yellow + "PRESS ENTER" + reset);
             		sk.nextLine();
                    println("");
                    BadEnding();
                    print(cyan + "PRESS ENTER TO GO BACK IN THE MAIN MENU." + reset);
                    sk.nextLine();
 
 
            		continue;
            	}
 
            case 2://another damn thing
            	println("");
            	print("You stayed and wait for the police to come");
            	for (int i = 0; i < 3; i++) {
                    try {
                        Thread.sleep(1000);
                        System.out.print(".");
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                }
 
            	String in5 = "You have the right to remain silent.";
        		String in6 = "          Anything you say can and will be used against you in a court of law.";
        		String inhalf = "But sir?";
        		String in7 = "You have the right to an attorney.";
        		String in8 = "          If you cannot afford one, one will be provided for you.";
        		String in9 = "          Do you understand the rights I have just read to you?";
        		println("");
            	println("");
                print("Officer : ");
                for (char letter : in5.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(50);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                println("");
                for (char letter : in6.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(50);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                println("");
                print(player + ": ");
            	for (char letter : inhalf.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
 
                println("");
                print("Officer : ");
                for (char letter : in7.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(50);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                println("");
                for (char letter : in8.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(50);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                println("");
                for (char letter : in9.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(50);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                System.out.println("");
         		System.out.println("");
         		System.out.print(yellow + "PRESS ENTER" + reset);
         		sk.nextLine();
         		sk.nextLine();
                println("");
                println("");
            	print("At the Prison");
                for (int i = 0; i < 3; i++) {
                    try {
                        Thread.sleep(1000);
                        System.out.print(".");
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                }
 
                String arch1 = "I promise, I'll help you.";
                String arch2 = "Help?";
                String arch3 = "       Help..";
                String arch4 = "       I don't care anymore.";
                String arch5 = "       My friend died and now I'm here..";
                String arch6 = "       There's nothing I can do anymore.";
 
                println("");
                println("");
                print("Attorney: ");
            	for (char letter : arch1.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
                print(player + ": ");
            	for (char letter : arch2.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
            	for (char letter : arch3.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
            	for (char letter : arch4.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
            	for (char letter : arch5.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
            	for (char letter : arch6.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
            	String arch100 = "There is..";
            	String arch101 = "No, There's nothing I can do anymore!!";
            	String arch102 = "Your friend will never get the justice they need if you keep doing that.";
            	String arch103 = "But...";
 
            	println("");
                print("Attorney: ");
            	for (char letter : arch100.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
                print(player + ": ");
            	for (char letter : arch101.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
                print("Attorney: ");
            	for (char letter : arch102.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
                print(player + ": ");
            	for (char letter : arch103.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
 
 
            	System.out.println("");
         		System.out.println("");
         		System.out.print(yellow + "PRESS ENTER" + reset);
         		sk.nextLine();
 
                String archa = "I'll help you";
                String archb = "Help me?";
                String archc = "yes, I'm the most smart attorney you can find.";
                String archd = "          so dont worry..";
                String arche = "          trust me okay?.";
 
                println("");
                print("Attorney: ");
            	for (char letter : archa.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
                print(player + ": ");
            	for (char letter : archb.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
                print("Attorney: ");
            	for (char letter : archc.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
            	for (char letter : archd.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
            	for (char letter : arche.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	System.out.println("");
         		System.out.println("");
         		System.out.print(yellow + "PRESS ENTER" + reset);
         		sk.nextLine();
                println("");
                println("");
                print("At the attorney's room");
                for (int i = 0; i < 3; i++) {
                    try {
                        Thread.sleep(1000);
                        System.out.print(".");
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                }
                println("");
                String hm = "Such a horrible event.. is that child going to be okay?";
 
                println("");
                print("Attorney: ");
            	for (char letter : hm.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
            	println("");
                println("");
                print("Someone clicked the doorbell");
                for (int i = 0; i < 3; i++) {
                    try {
                        Thread.sleep(1000);
                        System.out.print(".");
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                }
                println("");
                String hmm = "Hmm..";
                String hmmm = "      ";
                println("");
                println("");
                print("Attorney: ");
            	for (char letter : hmm.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
 
                println("");
            	for (char letter : hmmm.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
 
            	println("");
            	println("");
                print("*Sound of Gunshots*");
                for (int i = 0; i < 5; i++) {
                    try {
                        Thread.sleep(1000);
                        System.out.print(".");
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                }
                println("");
                println("");
                String deathofatt = "Three days later after the attorney died..";
                for (char letter : deathofatt.toCharArray()) {
     	       	    System.out.print(letter);
     	       	    try {
     	       	        Thread.sleep(100);
     	       	    } catch (InterruptedException e) {
     	       	        System.out.println("Sleep was interrupted");
     	       	    }
     	       	}
                println("");
                println("");
                print("At the court.");
                for (int i = 0; i < 5; i++) {
                    try {
                        Thread.sleep(1000);
                        System.out.print(".");
                    } catch (InterruptedException e) {
                        e.printStackTrace();
                    }
                }
 
                String court = "Having been found guilty of two counts of first-degree murder,";
                String court2 = "       it is the judgment of this court that you are sentenced to death";
                String court3 = "       by the method prescribed by law.";
 
                println("");
            	println("");
                print("Judge: ");
                for (char letter : court.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                println("");
                for (char letter : court2.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                println("");
                for (char letter : court3.toCharArray()) {
        	       	    System.out.print(letter);
        	       	    try {
        	       	        Thread.sleep(100);
        	       	    } catch (InterruptedException e) {
        	       	        System.out.println("Sleep was interrupted");
        	       	    }
        	       	}
                System.out.println("");
         		System.out.println("");
         		System.out.print(yellow + "PRESS ENTER" + reset);
         		sk.nextLine();
                println("");
                BadEnding();
                println("");
                println("");
                print("PRESS ENTER TO GO BACK IN THE MAIN MENU.");
                sk.nextLine();
            	continue;
            }
 
        	continue;
        case 2:
        	String endo3 = "Hello?";
        	String endo4 = "*Stabbed*";
        	String endo5 = "Wait.. what's this? I've been stabbed?";
        	String endo6 = "      ";
        	String endo7 = "You?";
        	String endo8 = "       Why have you done this?! you monster!!";
        	String endo9 = "*Smiled*";
        	String endo10 = "       ";
 
        	println("");
        	System.out.print("Dialing");
            for (int i = 0; i < 3; i++) {
                try {
                    Thread.sleep(1000);
                    System.out.print(".");
                } catch (InterruptedException e) {
                    e.printStackTrace();
                }
            }
            println("");
        	println("");
            print(player + ": ");
            for (char letter : endo3.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            println("");
        	for (char letter : endo4.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        	println("");
        	println("");
            print(player + "'s thought: ");
            for (char letter : endo5.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
        	for (char letter : endo6.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        	println("");
            print(player + ": ");
            for (char letter : endo7.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
        	for (char letter : endo8.toCharArray()) {
	       	    System.out.print(letter);
	       	    try {
	       	        Thread.sleep(100);
	       	    } catch (InterruptedException e) {
	       	        System.out.println("Sleep was interrupted");
	       	    }
	       	}
        	println("");
            print("Culprit: ");
            for (char letter : endo9.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(100);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
            println("");
            for (char letter : endo10.toCharArray()) {
    	       	    System.out.print(letter);
    	       	    try {
    	       	        Thread.sleep(200);
    	       	    } catch (InterruptedException e) {
    	       	        System.out.println("Sleep was interrupted");
    	       	    }
    	       	}
 
            System.out.println("");
     		System.out.println("");
     		System.out.print(yellow + "PRESS ENTER" + reset);
     		sk.nextLine();
     		sk.nextLine();
            println("");
            BadEnding();
            println("");
            println("");
            print("PRESS ENTER TO GO BACK IN THE MAIN MENU.");
            sk.nextLine();
        	 continue;
        }
 
        break;
        }
           break;
 
            case 2:
         do{
                    System.out.println(" ");
                    System.out.print("Enter the Username:  ");
                    String newUsername = sk.nextLine();
                    System.out.print("Enter the Password:  ");
                    String newPassword = sk.nextLine();
 
                    String[] newUsers = new String[usernames.length + 1];
                    String[] newPasswords = new String[passwords.length + 1];
 
                    for (int i = 0; i < usernames.length; i++) {
                        newUsers[i] = usernames[i];
                        newPasswords[i] = passwords[i];
                    }
 
                    newUsers[newUsers.length - 1] = newUsername;
                    newPasswords[newPasswords.length - 1] = newPassword;
 
        usernames = newUsers;
        passwords = newPasswords;
                    println(" ");
                    println("Account Created!!");
                    println(" ");
                    println("Do you want to add another account?");
                    println("(yes/no)");
                    System.out.println(" ");
                    print("Answer: ");
                    String continueAddUser = sk.nextLine();
 
                    if (continueAddUser.equalsIgnoreCase("no")) {
                        break;
                    }
     }while(true);
         break;
            case 3:
 
            	println("");
            	println("(1) Text Only");
            	println("(2) With Animation");
            	println("");
            	print("Answer: ");
            	int synopsis = sk.nextInt();
            	switch(synopsis) {
 
            	case 1:
            	println("");
            	println("Title: The Dilemma\r\n"
            			+ " \r\n"
            			+ " \r\n"
            			+ "Synopsis:\r\n"
            			+ " \r\n"
            			+ "\"The Dilemma\" is a gripping and emotionally charged story that follows the harrowing \r\n"
            			+ " \r\n"
            			+ "journey of a child who, after the tragic murder of their two best friends, \r\n"
            			+ " \r\n"
            			+ "takes it upon themselves to investigate and uncover the truth behind their deaths.\r\n"
            			+ " \r\n"
            			+ "In this heart-wrenching tale, the protagonist finds themselves caught in a web of uncertainty and conflicting emotions. \r\n"
            			+ " \r\n"
            			+ " \r\n"
            			+ "\"The Dilemma,\" reflects the moral and emotional challenges they face throughout their investigation.\r\n"
            			+ " \r\n"
            			+ "As the child delves deeper into their quest for justice,\r\n"
            			+ " \r\n"
            			+ "they encounter a series of dilemmas that test their courage and determination.\r\n"
            			+ " \r\n"
            			+ "The first dilemma arises from their desire to seek justice for their friends. \r\n"
            			+ " \r\n"
            			+ "They must grapple with the decision of whether to trust the authorities or take matters into their own hands.\r\n"
            			+ " \r\n"
            			+ "This internal conflict weighs heavily on their young shoulders as they navigate the complexities of right and wrong.\r\n"
            			+ " \r\n"
            			+ " \r\n"
            			+ "Another dilemma emerges as the child uncovers clues and suspects, realizing that the pursuit of justice may lead them\r\n"
            			+ " \r\n"
            			+ "into dangerous territory. They must confront the dilemma of balancing their own safety with their unwavering determination\r\n"
            			+ " \r\n"
            			+ "to find the truth. This internal struggle pushes them to question their own limits and the sacrifices they are willing to make.\r\n"
            			+ " \r\n"
            			+ "\"The Dilemma\" explores the profound impact of grief, loss, and the pursuit of justice on a young child.\r\n"
            			+ " \r\n"
            			+ "It delves into themes of friendship, resilience, and the power of determination. As the child unravels the mystery,\r\n"
            			+ " \r\n"
            			+ "they encounter unexpected twists and turns that challenge their beliefs and force them to make difficult choices.\r\n"
            			+ " \r\n"
            			+ "Through this gripping narrative, \"The Dilemma\" invites readers to reflect on the complexities of justice,\r\n"
            			+ " \r\n"
            			+ "the consequences of our actions, and the moral dilemmas that arise in the face of tragedy.\r\n"
            			+ " \r\n"
            			+ "It showcases the strength and resilience of a child who refuses to let their friends' deaths go unanswered,\r\n"
            			+ " \r\n"
            			+ "even when faced with overwhelming challenges.\r\n"
            			+ " \r\n"
            			+ " \r\n"
            			+ " \r\n"
            			+ black + "Note: The synopsis provided is a fictional scenario and does not involve any real-life events or individuals." + reset);
 
            	println("");
            	print(cyan + "Press Enter to Exit" + reset);
            	sk.nextLine();
            	sk.nextLine();
            	continue;
            	case 2:
            		println("");
                	println("Title: The Dilemma");
                	String krs1 = "\"The Dilemma\" is a gripping and emotionally charged story that follows the harrowing ";
                	String krs2 = "journey of a child who, after the tragic murder of their two best friends";
                	String krs3 = "takes it upon themselves to investigate and uncover the truth behind their deaths.";
                	String krs4 = "In this heart-wrenching tale, the protagonist finds themselves caught in a web of uncertainty and conflicting emotions.";
                	String krs5 = "\"The Dilemma,\" reflects the moral and emotional challenges they face throughout their investigation.";
                	String krs6 = "As the child delves deeper into their quest for justice,";
                	String krs7 = "they encounter a series of dilemmas that test their courage and determination";
                	String krs8 = "The first dilemma arises from their desire to seek justice for their friends.";
                	String krs9 = "They must grapple with the decision of whether to trust the authorities or take matters into their own hands.";
                	String krs10 = "This internal conflict weighs heavily on their young shoulders as they navigate the complexities of right and wrong.";
                	String krs11 = "Another dilemma emerges as the child uncovers clues and suspects, realizing that the pursuit of justice may lead them";
                	String krs12 = "into dangerous territory. They must confront the dilemma of balancing their own safety with their unwavering determination";
                	String krs13 = "to find the truth. This internal struggle pushes them to question their own limits and the sacrifices they are willing to make.";
                	String krs14 = "\"The Dilemma\" explores the profound impact of grief, loss, and the pursuit of justice on a young child.-";
                	String krs15 = "It delves into themes of friendship, resilience, and the power of determination. As the child unravels the mystery,";
                	String krs16 = "they encounter unexpected twists and turns that challenge their beliefs and force them to make difficult choices.";
                	String krs17 = "Through this gripping narrative, \\\"The Dilemma\\\" invites readers to reflect on the complexities of justice,";
                	String krs18 = "the consequences of our actions, and the moral dilemmas that arise in the face of tragedy.";
                	String krs19 = "It showcases the strength and resilience of a child who refuses to let their friends' deaths go unanswered,";
                	String krs20 = "even when faced with overwhelming challenges.";
                	String krs21 = "\"Note: The synopsis provided is a fictional scenario and does not involve any real-life events or individuals.";
 
 
                	println("");
                	for (char letter : krs1.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs2.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}	
                	println("");
                	for (char letter : krs3.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	println("");
                	for (char letter : krs4.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs5.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	println("");
                	for (char letter : krs6.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs7.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs8.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs9.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs10.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	println("");
                	for (char letter : krs11.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs12.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs13.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
 
                	println("");
                	println("");
                	for (char letter : krs14.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs15.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs16.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	println("");
                	for (char letter : krs17.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs18.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs19.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	for (char letter : krs20.toCharArray()) {
                   	    System.out.print(letter);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
                	println("");
                	println("");
                	for (char letter : krs21.toCharArray()) {
                   	    System.out.print(black + letter + reset);
                   	    try {
                   	        Thread.sleep(50);
                   	    } catch (InterruptedException e) {
                   	        System.out.println("Sleep was interrupted");
                   	    }
                   	}
 
                	println("");
                	System.out.print(cyan + "Press Enter to Exit" + reset);
                	sk.nextLine();
            		continue;
            	}
            case 4:
 
            	sk.close();
                return;
 
        }
    }
}
 
 
}
