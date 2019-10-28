# program3-4
example
package helloword;

public class TestPassObject {
 //Main memthod
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		//Create a Circle object with radius 1
		 new CircleWithPrivateDataFirlds(1);
		 
        //Print areas for radius 1,2,3,4,and 5.
		 int n=5;
		 printAreas (myCircle,n);
		 
		 //See myCircle.radius and times 
		 System.out.println("\n"+"Radius is"+myCircle.getRadius());
	}
	
	//Print a table of areas of area for radius
	public static void printAreas(
			CircleWithPrivateDataFirlds c, int times) {
		System.out.println("Radius\t\tArea");
		while(times>=1) {
			System.out.println(c.getRadius()+"\t\t"+c.getArea());
			c.setRadius(c.getRadius()+1);
			times--;
			
		}
	}

}
