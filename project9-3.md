# program3-4
example
package dasghj;

public class Tvv {
    int channnel 1;//Default channel is 1
    int volumelevel =1;//Defult volume level is 1
    boolean on = false ;//TV is off
    
   public TV(){
}
   public void turnOn(){
	   on = ture;
   }
   
   public void turnOff(){
	   on = false;
   }
   
   public void setChannel (int newChannel){
	   if(on && newChannel >=1 && newChannel <=120)
		   channel= newChannel;
   }
   
   public void setVolume (int newVolumeLevel){
	   if(on && newChannnel >=1&&newVolumeLevel <=120 )
		   channel = newVolumeLevel;
   }
   
   public void channelUp(){
	   if(on && channel <120)
		   channel++;
   }
   public void voulmeUp(){
	   if(on && channel >1)
		   channel--;
   }
   
   public void volumeUp(){
	   if(on && volumLevel < 7)
		   volumeLevel++;
   }
   
   public void volumeDown(){
	   if(on&&volumelevel>1)
		   volumeLevel--;
   }
}
