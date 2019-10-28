# program3-4
example
public class TestCircleWithPrivateDataFields {
/**Main method*/
	public static void main(String[]args) {
		//Create a circle with radius 5.0
		CircleWithPrivateDataFields myCircle=
				new CircleWithPrivateDataFields myCircle(5.0);
		System.out.println("The area of the circle of radius")
		+myCircle.getRadius()+"is"+myCircle.getArea());
		
		//INcrease myCircle's radius by 10%
		myCircle.getRadius(myCircle.getRadius()*1.1);
		System.out.println("The area of the circle of radius")
		+myCircle.getRadius()+"is"+myCircle.getArea());
		System.out.println("The number of the objects created is"
				+ CircleWithPrivateDataFields.getNUmberOfObjects());
	}
}
