# Notification
import time
from plyer import notification

while True:
    notification.notify(

        title = "**Drink Water**",
        message  = "It’s commonly recommended that you drink eight 8-ounce (237-mL) glasses of water per day (the 8×8 rule).",
        # app_icon = "C:\Users\ArtiGulia\Downloads\water.ico",
        timeout = 2
    )
    # To pop up the notification in every 1 hour
    time.sleep(60*60)
