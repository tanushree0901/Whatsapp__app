# Whatsapp__app
# Now you can annoy yours friends by just clicking enter.
import random
import pyautogui as pg
import time

animal=('Monkey','Donkey','Dog')
time.sleep(8)
for i in range(10):
    a=random.choice(animal)
    pg.write("You are a " +a)
    pg.press("enter")
