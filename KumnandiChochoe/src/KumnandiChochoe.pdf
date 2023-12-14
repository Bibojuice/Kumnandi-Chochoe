
import javax.swing.JOptionPane;

/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 * Click nbfs://nbhost/SystemFileSystem/Templates/Classes/Class.java to edit this template
 */

/**
 *
 * @author Ntsaki
 */
public class KumnandiChochoe
{   //Madimetsa Chochoe
    //Global variables
    String menu, fstName,sndName, animal;
    char letter;
    Double stat1= 0.0, stat2= 0.0,stat3=0.0;
    int adults ,child;
    int totalCost;
    int totalAnimal = 0;
    
    
    KumnandiChochoe()
    {
        
        while ( letter == 'x')
        {
        menu = JOptionPane.showInputDialog("Kumnandi Game Reserve\n a)Ticket for game drive\n b)Animals seen on game drive\n c)Record weather data x)Exit ").toLowerCase();
        letter = menu.charAt(0);
        
//        switch(letter){
//            
//        }
        if(letter == 'a')
        {
            adults = Integer.parseInt(JOptionPane.showInputDialog("How many adults are attending"));
            child = Integer.parseInt(JOptionPane.showInputDialog("How many children will be attending"));
          processTickets  
        }else
        if(letter == 'b')
        {
            seeAnimals();
        }else
        if(letter == 'c')
        {
          
        }
        if (letter == 'a' )
        {
            
        }
       
    }

   
    public void processTickets()
    {
      
        int totalMem = adults + child;
        if( totalMem >= 5)
        {
            totalCost = adults* 650 + child *430 ;
            totalCost = (int) (0.01* totalCost); 
            
        }else
        {
           totalCost = adults * 650 + child * 430;
        }
        System.out.println("Adults: " + adults + "Children: "+ child + "Total cost of tickets: " + totalCost);
        
        fstName = JOptionPane.showInputDialog("Enter first name");
        sndName = JOptionPane.showInputDialog("Enter surname");
        char lettCde1 = fstName.charAt(0) ;
        char lettCde2 = sndName.charAt(0);
        int numCde =(int) (1000+ Math.random () * 10);
        System.out.println("Reference: " + lettCde1 + lettCde2 + numCde);
    }
     public void seeAnimals()
    {   
        while(animal == "stop")
        {
         animal = JOptionPane.showInputDialog("Which animal did you see(enter a single animal name)");
        int numAnimal = Integer.parseInt(JOptionPane.showInputDialog(" How many " + animal + "s" + "did you see.\n Type 'Stop' when done"));
        totalAnimal = totalAnimal + numAnimal;
        }
        if(totalAnimal > 40)
        {
            System.out.println("Congrats! You have been awarded an Elephant Certificat for spotting " + totalAnimal + "animals");
        }else
        if( totalAnimal >= 20 )
        {
            System.out.println("Congrats! You have been awarded an Eland Certificat for spotting " + totalAnimal + "animals");
        }else
        if(totalAnimal >= 10)
        {
              System.out.println("Congrats! You have been awarded an Impala Certificat for spotting " + totalAnimal + "animals");
        }else
            System.exit(0);
    }
    public void perfectWeatherDay()
    {
        
        stat1 = Double.parseDouble(JOptionPane.showInputDialog("Enter temperature for weather station 1"));
        stat2 = Double.parseDouble(JOptionPane.showInputDialog("Enter temperatures for weather staion 2"));
        stat3 = Double.parseDouble(JOptionPane.showInputDialog("Enter the temperatures for weather station 3"));
       
            
    }
    
    
    public static void main(String[] args)
    {
       new KumnandiChochoe();
    }
}
