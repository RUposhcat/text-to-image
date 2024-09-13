There are two converters in the repository, one is for discord channels (creating an image out of the discord messages) and a plain .txt to image converter.

They do not make an image of the letters, but each letter in the text will be turned into a corrisponding colour and each letter will create a pixel, creating an abstract image.

**HOW TO USE**

To use image_creator_text.py, Firstly install the pillow module by running the command:
```pip install pillow```
You can then run it using an IDE like IDLE that comes preinstalled with python (or any prefered IDE), and pasting the path of the text file you want to convert into the prompt given (in the IDE's terminal)
The image will be created in the same folder as the python file with the name of the text file.

To use image_creator_dis.py, You need to first create a discord bot using the discord developer portal, after setting up the bot, you need to get the bot token from the discord developer portal (pictured below).
![image](https://github.com/user-attachments/assets/3d266139-3ca2-4439-885a-ac280c04dc5d)

You then need to open the image_creator_dis.py and replace the text 'add your bot token here' with the bot token.
![image](https://github.com/user-attachments/assets/1bb20f06-ee33-4b04-92b0-2f5d47deb195)

After Inviting the bot to the discord server in which the channel you want to convert lies, run the command
```?create_image (channel_id*)```

The channel_id argument is not required because if it is not provided, the bot will just take the messages from the channel the command was ran.

**Last important notice**
The discord bot needs admin as it needs access to the chat history.
