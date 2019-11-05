# program3-4
example

public class RectangleFromSimpleGeometricObject 
 extends SimpleGeometricObject {
	 private double width;
	 private double height;
	 
	 public RectangleFromSimpleGeometricObject(){
	 }
	 public RectangleFromSimpleGeometricObject(double width,double height){
		 this.width=width;
		 this.height =height;
	 }
	 
	 public RectangleFromSimpleGeometricObject(
			 double width,double height,String color ,boolean filled){
		 this.width=width;
		 this.height =height;
		 setColor(color);
		 setFilled(filled);
	 }
	 /**return width*/
	 public double getWidth(){
		 return width;
	 }
	 
	 /**set s new width*/
	 public void setWidth(double width){
		 this.width=width;
	 }
	 /**return heighhht*/
	 public double getHeight(){
		 return height;
	 }
	 
	 /**set a new height*/
	 public void setHeight(double height){
		 this.height=height;
	 }
	 /**return area*/
	 public double getArea(){
		 return width*height;
	 }
	 /**return perimeter*/
	 public double getPerimeter(){
return 2*(width+height); 
}
}
