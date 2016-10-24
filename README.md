#Slaughterhouse simulation

This application is a 3 - tier distributed service application that I am implementing in Java and will be simulated with RMI and WSI. 
On developing this application, I went to throught the following stage.
 1.  I analyse and gathered requirements, that was given an applicaiton on paper
 2. I describe the application in details, and better approach architecture that I thought would suite the application
 3. I describe the intereactions
 4. I created a Class diagram

Description

In the slaughterhouse there are three positions where smaller parts of the whole process take place. At the first position the animals 
 arrive, are weighted and registered.
 
 At the second position the animals are cut into smaller parts. Each part is weighted and registered, including a reference to the animal 
 it comes from. The parts are put into trays. Each tray contains only one type of parts and  has a maximum weight that it is allowed to
 put in it.
 
At the third position products are packed for distribution. One product might be a package with a number of the same kind of parts intended
for repackaging in supermarkets. Another kind of product might be “half an animal” where all the expected parts are included, but not 
necessarily coming from the same animal. All products are registered including references back to the trays, the parts came from.

If it is later discovered, that there is some kind of trouble with a slaughtered animal, it should be possible to withdraw from the market
all products, which might contain a part from the animal. This function should be accessible outside the slaughterhouse.
        
  By 
    Daniel Mangowi <br>
    Visit my site for more details about my [portifolio](http://www.mangowi.com)
