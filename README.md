# Java_EE_Udemy34
Named Queries On Entity classes

In Flight: 

      @NamedQuery(name="Flight.findById", query="SELECT f FROM Flight f WHERE f.id = :id") 
      
In Pilot:

      @NamedQuery(name = "Pilot.findById", query="SELECT p FROM Pilot p WHERE p.id = :id")


