# Todo_Python_tele_bot

## A ToDo Telegram bot
- Install the required packages as follows,
  - ```pip install -r requirements.txt```
  
- This repo contains following files,
  - An entry point file __bot.py__
    - __Commands___ that it'll handle are as follows:
      - ```/start``` : To add new ToDo items
      - ```/show``` : To display ToDo items
      - ```/done``` : To remove ToDo items after they are completed
    - Here, It'll display the ToDo items in a In-line Keyboard fashion, In which we select a particular button it'll remove that ToDo item from the list)
    
  - A model file __dbhelper.py__  to interact with __DB__
    - This file consists a __DBHelper__ Class
    - By using __SQLite DB__ storing respective users ```ToDo```
    - All operations like CRUD performed by accessing __DBHelper__ Class instance.
    
  - A __runtime.txt__ file
    - Basically needed for deployment on Heroku.
  
  - A major file __Procefile__
    - Which acts as a protocol/entry point for Heroku, To run the bot after successful deploy on Heroku.
    
## ```Note:```
- This repo was created in interest of learning the concepts.
- If anybody finds helpful, Kindly provide a ```Star``` or
```fork``` for adding new feature or ```ANY Issues``` with this repo, feel free to connect with me.)
