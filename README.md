
import os
from time import sleep


a ='\033[92m'
b ='\033[91m'
c ='\033[0m'
os.system('clear')
print(a+'\t  Shorcut for help you')
print(b+'\t    @ahsan')
print('wattsap 081244365434')
print(a+'+'*40)
print('\nProses..')
sleep(1)
print(b+'\n[!] making termux properties directory..')
sleep(1)
try:
      os.mkdir('/data/data/com.termux/files/home/.termux')
except:
      pass
print(a+'[!]Success !')
sleep(1)
print(b+'\n[!] Making setup file..')
sleep(1)

key = "extra-keys = [['ESC','/','-','HOME','UP','END','PGUP'],['TAB','CTRL','ALT','LEFT','DOWN','RIGHT','PGDN']]"
islam = open('/data/data/com.termux/files/home/.termux/termux.properties','w')
islam.write(key)
islam.close()
sleep(1)
print(a+'[!] Success !')
sleep(1)
print(b+'\n[!] Setting up..')
sleep(2)
os.system('termux-reload-settings')
print(a+'[!] Successfully !! ^^'+c+'\n\nhubungi @ahsan untuk requests\natau pertanyaan, atau hubungi 081244365434\nThanks :*\n\n')


# ini cuma shortcut buat bantu para newbie 
# Salam NKRI Merdeka
