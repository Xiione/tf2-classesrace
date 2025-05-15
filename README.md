# TF2 classes race pub minigame
## Download and installation
1. Click the green "Code" button -> click "Download ZIP"
2. Extract the contents of `tf2-classesrace-main.zip`
3. Copy the `classesrace` folder to the `tf/cfg` folder of your TF2 installation
4. Add the following line to your `tf/cfg/autoexec.cfg`:  
   ```
   exec "classesrace/setup"
   ```
5. (Optional) Adjust the keybinds in `classesrace/setup.cfg` to your liking if you use your F1-F11 keys. The config includes an alternate set of binds using the numpad instead
6. Make sure the keybinds set in `classesrace/setup.cfg` are not overwritten by any script that runs after it!

## Playing the game
1. Enter a party with at least one other player. You don't need to be connected to a Valve casual server to play the minigame, but you may need to have another player in the party for the `say_party` command to work.
2. Each round, when you kill a player of a certain class, hit the key corresponding to the class's number. NOTE: duplicate class kills are handled by the script, so you don't need to memorize which classes you've already killed.
   - Scout -> **F1**
   - Soldier -> **F2**
   - Pyro -> **F3**
   - Demoman -> **F4**
   - Heavy -> **F5**
   - Engineer -> **F6**
   - Medic -> **F7**
   - Sniper -> **F8**
   - Spy -> **F9**
3. Hit **F10** to check which classes you still need, they'll be displayed in the party chat if you've killed at least one class.
4. First player to 9 classes killed wins! The ninth class's message will be marked by `!![9/9]!!`. If nobody reached 9, the player who got the maximum score first wins, and if multiple people ended with the same score, scroll up in the party chat history to see who got there first.
5. When the round ends, each player hits **F11** to reset their counter. This will mark the chat history clearly with a message:  
   `[X/9] ---RESET---> [0/9]`
