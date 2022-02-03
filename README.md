 public class Main {

    public static void main(String[] args) {

        int myMinInt = Integer.MIN_VALUE;
        int myMaxInt = Integer.MAX_VALUE;

        System.out.println("my minimum int value = " + myMinInt);
        System.out.println("my maximum int value = " + myMaxInt);

        System.out.println("MIN integer overflowed = " + (myMinInt - 1));
        System.out.println("MAX integer overflowed = " + (myMaxInt + 1));

        byte myMinbytevalue = Byte.MIN_VALUE;
        byte myMaxbytevalue = Byte.MAX_VALUE;
        System.out.println("my minimum byte value = " + myMinbytevalue);
        System.out.println("my maximum byte value = " + myMaxbytevalue);

        short myMinshortvalue = Short.MIN_VALUE;
        short myMaxshortvalue = Short.MAX_VALUE;
        System.out.println("my minimum short value = " + myMinshortvalue);
        System.out.println("my maximum short value = " + myMaxshortvalue);

        long myMinlongvalue = Long.MIN_VALUE;
        long myMaxlongvalue = Long.MAX_VALUE;
        System.out.println("my minimum long value = " + myMinlongvalue);
        System.out.println("my maximum long value = " + myMaxlongvalue);

        long mylong = 1234567890123L;
        byte mybyte = -128 / 2;

        // type casting...its confusing.
       
       float myfloat = 1.23f;
        byte Byte = (byte) (myMinbytevalue / 2);
        System.out.println(Byte);

        // for "never used" warnings to disappear..

        System.out.println(mybyte + mylong + myfloat);

        // 28>>

//        byte x = 100;
//        short y = 20000;
//        int z = 300000;
//        long xyz = 50000L + (10L * (x + y + z));
//        System.out.println(xyz);

        // below and above ones are same and equal , it was just a test hahahahah

        byte x = 100;  short y = 20000;  int z = 300000;
        long xyz = 50000L + (10L * (x + y + z));
        System.out.println(xyz);

        
       
         //29>>
        float myMinfloatvalue = Float.MIN_VALUE;
        float myMaxfloatvalue = Float.MAX_VALUE;
        System.out.println("my minimum float value = " + myMinfloatvalue);
        System.out.println("my maximum float value = " + myMaxfloatvalue);

        double myMindoublevalue = Double.MIN_VALUE;
        double myMaxdoublevalue = Double.MAX_VALUE;
        System.out.println("my minimum double value = " + myMindoublevalue);
        System.out.println("my maximum double value = " + myMaxdoublevalue);

        float Float = 2.2f; //or
        float orFloat = (float)2.2;
        System.out.println(Float);
        System.out.println(orFloat);

        double Double = 12.5; //or
        double orDouble = 12.5d;
        System.out.println(Double);
        System.out.println(orDouble);

        int test1 = 13 / 2;
        float test2 = 13 / 3f;
        double test3 = 14 / 3d;
        System.out.println(test1 + " ," + test2 + " ," + test3);

//        New challenge yessssss..

//        double PoundsLBS = 4d;
//        double KilogramsKGS = 0.453592;
//        double LBStoKGS = PoundsLBS * KilogramsKGS;
//        System.out.println(PoundsLBS + "LBS = " + LBStoKGS);
//        extra line of code written lets make it simpler....

        double PoundsLBS = 4d;
        double LBStoKGS = PoundsLBS * 0.453592;
        System.out.println(PoundsLBS + "LBS = " + LBStoKGS);

    }
}
