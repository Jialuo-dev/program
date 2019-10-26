# program3-4
example
public class CircleWithStaticMmbers {
    double radius;
    /**The number of objects created*/
    static int numberOfObjects=0;
    
    /**Construct a circle with radius 1*/
    CircleWithStaticMembers(){
    	radius =1;
    	numberOfObjects++;
    }
    
    /**Construct a circle with a specified radius 1*/
    CircleWithStaticMembers(){
    	radius=nweRadius;
    	numberOfObjects++;
    }
    
    /** Return numberOfObjects*/
    static int getNumberOfObjects() {
    	return numberOfObjects;
    }
    /**Return the area of this circle*/
    double getArea() {
    	return radius*radius*Math.PI;
    }
}
