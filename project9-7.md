# program3-4
example
public class TestCircleWithStaticMembers {
/**Main method*/
	public static void main(String[] args) {
		// TODO Auto-generated method stub
    System.out.println("Before creatig objects");
    System.out.println("The number of circle object is"+
    Circle WitheStaticMembers,numberOfobjects);
    
    //create C1;
    CricleWithStartMembers c1= new CircleWithStaticMembers();
    
    //Display c1 BEFORE c2 is created
    System.out.println("\nAfter creating c1");
    System.out.println("c1: radius (" + c1.radius +") and number of Circle object ("+ c1.numberOfObjects+")");
    
    
    //Create c2
    CircleWithStaticMembers c2 = new CircleWithStaticMembers(5);
    
    //Modify c1
    c1.radius = 9;
    //Display c1 and c2 AFTER c2 created
    System.out.println("\nAfter creating c2 and modifying c1");
    System.out.println("c1: radius (" + c1.radius +") and number of Circle object ("+ c1.numberOfObjects+")");
    System.out.println("c1: radius (" + c2.radius +") and number of Circle object ("+ c2.numberOfObjects+")");
	}
}

