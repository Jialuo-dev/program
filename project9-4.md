# program3-4
example
package aaa;

public abstract class TestTV{

	public static void main(String[] args) {
		// TODO Auto-generated method stub
       TV tv1= new TV();
       tv1.turnOn();
       tv1.setChannel(30);
       tv1.setVolume(3);
       
       TV tv2 = new TV();
       tv2.turnOn();
       tv2.channelUp();
       tv2.channelUp();
       tv2.volumeUp();
       
       System.out.println("tvl's channel is "+ tv1.channel
    		   +" and volume level is " +tv1.volumeLevel);
       System.out.println("tv2's channle is "+tv2.channel 
    		   +"  and volume level is" =tv2.volumeLevel);
	}

}
