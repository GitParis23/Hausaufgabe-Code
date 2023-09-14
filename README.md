# Hausaufgabe-Code

public class Hund
{
    private String farbe;
    private boolean redner;
    private boolean schlafender;
    private int ohrLänge;
    private long einwohner;
    
    public Hund(String Farbe, boolean redner, boolean schlafender,int ohrLänge, long einwohner)
    {
      this.farbe = farbe;
      this.redner = redner;
      this.schlafender = schlafender;
      this.ohrLänge = ohrLänge;
      this.einwohner = einwohner;
    }
    
    public String hundFarbe()
    {
        System.out.println("Farebe des Hundes:"+farbe);
        return farbe;
    }
    public boolean rednerH()
    {
        System.out.println("Ist der ein sprechender Hund?"+redner);
        return redner;
    }
    public boolean hypnoH()
    {
       System.out.println("Ist der Hund Hypnos?"+schlafender);
       return schlafender;
    }
    public int ohrLangH()
    {
        System.out.println("Länge der Ohren des Hudes:"+ohrLänge);
        return ohrLänge;
    }
    public long einwohner()
    {
        System.out.println("Einwohner anzahl inder wellt:"+einwohner);
        return einwohner;
    }
}
