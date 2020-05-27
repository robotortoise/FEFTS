# FEFTS
Fire Emblem Fates Text Simulator

ATTENTION: THIS PROJECT IS OUT OF DATE. PLEASE READ THE END OF THIS DOCUMENT FOR MORE DETAILS.


Forked from https://github.com/SciresM/FEITS .
Credit to SciresM for the original program. I only localized the names and fixed a few things.
Special thanks to deventio7 for creating the script that renames Fates portraits properly!


![FEFTS](/FEFTS/Resources/img/example_conversation_preview.png)

Simulates Fire Emblem Fates conversations, allows for the generation of portraits with specific hair colors, and is generally neat.



== Things that still need to be done, in order of importance and ease to implement ==

1. Implement DLC portraits. Portraits, along with the FaceData.bin files, are located in FEFTS\Resources\img\Not_Yet_Used\Fates.

2. Localize the expression names in portrait generator.

3. Automatically give each of the children their default hair color when they're used until specified otherwise. If possible, use the Heirs of Fate portrait instead of the in-game ones, as the HoF ones have minor fixes.

4. Figure out why the program sometimes crashes when making a support with the wrong syntax, and have it instead display an error message.

5. See if the font can be used for the generated text instead of the PNG, for higher-resolution images.

6. Allow the easy creation of supports, using drop-downs for each character expression, portrait, etc.

7. Restructure the code to load the portraits and assets on-the-fly like the games do instead of loading everything into RAM at once.

8. Implement the Awakening portraits (located in FEFTS\Resources\img\Not_Yet_Used\Awakening), dialogue box, and background.

9. If possible, animate the text to resemble the in-game text.

10.  Add music and voice support so this program can be used to render supports, rendering a 3DS capture card unnecessary to make videos of realistic custom supports.


DEPRECATION as of 5/27/2020:

This project has not been and will not be updated further. For a more comprehensive, easier to use solution, please use this tool: https://gitlab.com/secretivecactus/fe-conversation-editor

-Jordan
