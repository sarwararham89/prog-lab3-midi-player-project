Project: midi-player
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.
Question 41: After calling the method, i see the instrument number which gives me 0 but under that i see this "C (12) C (12) C (12) C (12) C (12) C (12) C (12) C (12)" which was the amount  of times that i called the method. i dont think it could play this tune. 
Question 43: Yes you can play it multiple times. 
Question 45: tune.getTune() 
             startPlaying()
Question 47: // instance variables - replace the example below with your own
    private int x;
    private MidiPlayer player;

    /**
     * Constructor for objects of class TuneCreator
     */
    public TuneCreator()
    {
        // initialise instance variables
        x = 0; 
        player = new MidiPlayer();
    }
Question 48 and 49: /** 
     * Create a tune, add notes to it, and play it.  
     */
    public void CreateAndPlay()
    {
        SimpleTune tune = new SimpleTune();
        tune.addNote("C",12);
        tune.addNote("D",14);
        tune.addNote("A",17);
        player.playTune(tune); 
    } 

