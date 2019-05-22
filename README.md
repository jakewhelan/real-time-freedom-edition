# Real Time - FREEDOM EDITION!

A mod for the Cities: Skylines game, now with less social justice!

Adjusts the time flow in the game to make it more real. **Real Time** makes the game way more real and more challenging!

## Installation
1. Download the latest mod binaries from the Github [releases](https://github.com/jakewhelan/real-time-freedom-edition/releases) section
2. Extract everything into a folder named `real-time-nosteam` in your Cities: Skylines mod folder at `%localappdata%\Colossal Order\Cities_Skylines\Addons\Mods`
3. The full path should look like `%localappdata%\Colossal Order\Cities_Skylines\Addons\Mods\real-time-nosteam\RealTimeNoSteam.dll` (plus the other files in the .zip)
4. Run the game
5. Enjoy having the freedom to buy the game anywhere you like

## Key Features
### Time flow

- The game time flows slowly. The time speed can be configured for the daytime and for the night time separately.
- The sunrise and the sunset times depend on the map location and on the day of year.

### Work...

- The adult citizens go to work in the morning. The children go to school.
- There are weekends. No school, no usual work on weekends!
- The adults may also work second shift, night shift, and some of them work on weekends!
- A lot of traffic, especially at rush hour times.
- Citizens can go out for lunch, if there are some commercial buildings near the citizens' workplaces.
- Citizen can go on vacation for some days. Families prefer to go on vacation all together (parents and children).

### ...and relax

- The school ends earlier, so the children can have spare time.
- After work or school, the citizens go shopping or relaxing.
- Children stay at home in the late evening.
- Citizens can attend events like football matches. In addition to the game events, there are some other events for various unique buildings in the city.
- Tourists can stay in the city for longer, if there are some hotels.
- In the night time, no one will visit parks; a single exception: the 'Night tours' policy is activate in a park.
- Only few citizens will go out and party at night (in leisure buildings, if there are any). 
- Some adult citizens will take night shopping tours.

### More real

- Citizens might go shopping even when they don't need any goods - just for fun.
- Tourists also prefer to sleep at night.
- The buildings will be constructed slowly.
- There are restrictions how many construction sites are allowed at the same time in the city.
- The building construction sites pause at night.
- Citizens switch the lights off when they are going to sleep, as well as many other parks and buildings.
- When the weather becomes bad, citizens try to shelter from the weather in the buildings.
- Citizens remember how long they need to get to work and use this in their schedules, trying to be on-time.
- When waiting for public transport for too long or stuck in a traffic jam, citizens get angry and cancel their journeys.

# Contributing
If you have some time and would like to help build Real Time - FREEDOM EDITION! I'd love to have your assistance.

## Environment
You will need:
- Visual Studio
- C# SDK
- Cities: Skylines + DLC (this mod references binaries from the game)
- SkyTools (https://github.com/jakewhelan/sky-tools-freedom-edition)

## Compiling
1. Clone repo `git clone git@github.com:jakewhelan/real-time-freedom-edition.git`
2. Copy the SkyTools project into `real-time-freedom-edition/src/SkyTools`
3. Open `real-time-freedom-edition/src/SkyTools/src/SkyTools/SkyTools.csproj` in Visual Studio
4. In Solution Explorer, right click `references` --> Add References -> Browse
5. Find the missing binaries in your Cities: Skylines game folder and add them to project
6. CTRL + B to build
7. Now open `real-time-freedom-edition/src/RealTime/RealTime.csproj`
8. In Solution Explorer, right click `references` --> Add References -> Browse
9. Find the missing binaries in your Cities: Skylines game folder and add them to project
10. You're golden, CTRL + B to build
11. Find the RealTimeNoSteam.dll and other compiled binaries in `real-time-freedom-edition/src/bin/**/*`

## Debugging and development help
Honestly I'm not that committed to modding Cities: Skylines and resources for how to do so aren't very good, if you aren't an experienced developer you may have difficulty contributing to this project.

Google will have to do.

# Special Thanks
Huge thanks to dymanoid for being such a snob about Steam Workshop and inconveniencing me enough that I was motivated to make this project.

![image](https://i.gyazo.com/8dbdd0bd33260ff03b738e844dbd399f.png)

https://www.reddit.com/r/CitiesSkylines/comments/9b7g6m/new_real_time_mod_makes_the_game_life_like/e53afo2/

🖕