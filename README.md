# ProjectHangman
This game consist of a list of word file, and code will lookup for range (5..12) of word.length and randomly selected
  <li>6 chances for guess, so game will be over </li>
  <oi></oi>
  
This "hangman" is good example for the {serialization} problem, it uses YAML.dump and YAML.load_file for file transaction.
saved file will contain some statistics of game such as guessesleft, what is right word and etc.
I suggest you to check it out as good example of YAML and File.I/O topic

there is a cheating way which you save the game and check it saved file in directory and see what is the secret code variable then load the game again :) but nothing to do because this is the what is wanted.


