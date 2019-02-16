Simple Python server that shows Taskwarrior tasks using javascript [fullcalendar](http://fullcalendar.io/) library.

## Instalation on WSL Ubuntu 16.04:
0. Open WSL Ubuntu 16.04

1. Go to your home directory, and open your username directory (Optional):
```
cd ~
```
2. Create a new folder named `calendar` and open it (Optional):
```
mkdir calendar
cd calendar
```
3. Git clone this repository (assuming you already have git installed):
```
git clone <Put the link you see at the green git clone button here"
```
4. Install python minimal:
```
apt install python-minimal
```

## Usage:
5. Open the (downloaded) taskwarrior-fullcalendar folder and start up the event calendar
```
cd taskwarrior-fullcalendar
python server.py
```
6. Now in your Windows 10 open a browser and goto:
```
http://127.0.0.1:9001/
```

7. TODO: determine why tasks are not displayed in Windows 10.
