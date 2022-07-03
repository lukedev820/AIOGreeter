# AIOGreeter
*Your All-In-One-Greeter that gives you an acurate welcome, weather info and a todo list all from your terminal.*
<br><br>
<p align="center">  
  <img width="772" src="https://github.com/lukedev820/AIOGreeter/blob/main/example.png">
</p>
<br>

## Installation

> Create an [OpenWeatherMap](https://home.openweathermap.org/users/sign_up) account  and get a free API key. 

> Please note that [OpenWeatherMap](https://home.openweathermap.org) may take several minutes to activate newly created keys.<br>They will appear as invalid during that time.

1) Download the latest version of [AIOGreeter](https://github.com/lukedev820/AIOGreeter) from this repository:
```
git clone https://github.com/lukedev820/AIOGreeter
cd AIOGreeter
```
2) Change Line 19 (To-do path) and Line 42 (API key config file path) in `AIOGreeter` 

2) Run the following commands to install [AIOGreeter](https://github.com/lukedev820/AIOGreeter) in your `/usr/bin/` directory:
```
sudo chmod +x AIOGreeter
sudo cp AIOGreeter /usr/bin/
sudo cp style.py /usr/bin/
```

The program can now be ran from a terminal with the `AIOGreeter` command.
<br><br>

## Usage
```
usage: AIOGreeter [-h] [-i] city [city ...]

positional arguments:
  city            enter the city name

options:
  -h, --help      show this help message and exit
  -i, --imperial  display the temperature in imperial units
 example: AIOGreeter New York
```