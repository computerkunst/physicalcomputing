#Was braucht der Code? Librarys
import machine
import utime

#Welche Geräte (Sensoren, Aktoren) sind wo angeschlossen
led_onboard = machine.Pin(2, machine.Pin.OUT)

#Loop = Hauptprogramm immer und immer wieder
while True:
    led_onboard.value(1)
    utime.sleep(1)
    led_onboard.value(0)
    utime.sleep(1)

