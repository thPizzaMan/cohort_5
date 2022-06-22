### Rock Paper Scissors Pseudocode

1. explain how the game works(how the user has to press there key board r for Rock etc.. )

- in the html at the top of the page write instruction in a P tag

2. player chooses R,P,S on the keyboard

- using the document on key up event capture the the user key
- console log the key selected
- capture player selection and store in variable => playerSelection

3. computer chooses random R,P,S

- create array with computer options of "r","p","s"
- store array in variable
- get random number with javascript between 0 and including 0 all the way up to and including 2
- capture user selection and store in a variable => computerChoice

4. determine winner:

   - If user picks rock and if computer picks scissors then  
      user wins
     end

   - If user picks rock and if computer picks paper then
     user loses
     end

   - If user picks scissors and if computer picks rock then
     user loses
     end

   - If user picks scissors and if computer picks paper then  
      user wins
     end

   - If user picks paper and if computer picks rock then
     user wins
     end

   - If user picks paper and if computer picks scissors then
     user loses
     end

   - else
     user picks the same as computer then they tie
     end

5. if player ties then
   add 1 to ties
   end
6. if player losses then
   add 1 to losses
   end
7. if player wins then
   add 1 to wins
   end
8. player presses E,P,S to play again
