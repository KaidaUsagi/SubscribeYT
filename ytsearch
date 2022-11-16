import pyautogui
import time
import keyboard


def cautare_google():
    time.sleep(5)
    if pyautogui.locateOnScreen(r'D:\Proiecte\Python_Projects\Capture_URL_final.png', confidence=0.7) != None:
        camp_google = pyautogui.locateOnScreen(r'C:\Users\Kaida\Projects\Python\SubscribeYoutube\CautareGoogle.png', confidence=0.7)
        pyautogui.click(camp_google)
        time.sleep(1)
        pyautogui.write('https://www.youtube.com')
        pyautogui.press('enter')
    else:
        print("Imaginea nu este pe ecran")

def cautare_search():
    time.sleep(5)
    if pyautogui.locateOnScreen(r'C:\Users\Kaida\Projects\Python\SubscribeYoutube\YoutubeSearch.png', confidence=0.7) != None:
        camp_google = pyautogui.locateOnScreen(r'C:\Users\Kaida\Projects\Python\SubscribeYoutube\YoutubeSearch.png', confidence=0.7)
        pyautogui.click(camp_google)
        pyautogui.write('loltyler1')
        pyautogui.press('enter')
        time.sleep(3)
        camp_google = pyautogui.locateOnScreen(r'C:\Users\Kaida\Projects\Python\SubscribeYoutube\YoutubeChannel.png', confidence=0.7)
        pyautogui.click(camp_google)
    else:
        print("Imaginea nu este pe ecran")

def cautare_subscribe():
    time.sleep(5)
    if pyautogui.locateOnScreen(r'C:\Users\Kaida\Projects\Python\SubscribeYoutube\YoutubeSubscribe.png', confidence=0.7) != None:
        camp_google = pyautogui.locateOnScreen(r'C:\Users\Kaida\Projects\Python\SubscribeYoutube\YoutubeSubscribe', confidence=0.7)
        pyautogui.click(camp_google)
        time.sleep(1)
    else:
        print("Imaginea nu este pe ecran")

cautare_google()
cautare_search()
cautare_subscribe()
