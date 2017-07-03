# High Rising City Artifact
This repository contains the VISSOFT 2017 artifact for the following paper:

>Katsuya Ogami, Raula Gaikovina Kula, Hideaki Hata, Takashi Ishio, and Kenichi Matsumoto, ***"Using High-Rising Cities to Visualize Performance in Real-Time,"***. In Proc. of 5th IEEE Working Conference on Software Visualization (VISSOFT 2017), (to appear).

## Installation and Profiling a sample program:

1. Clone or download this repository.

`git clone https://github.com/sefield/high-rising-city-artifact`

2. Install and execute our high-rising-city Visualization. You may have to set execution permission of program file. (Note: installers are located in the HighRisingCityVisualizer folder)

  * ***Windows***  
    Double click `HighRisingCityVisualizer/HighRisingCityVisualizer_win_x86_64/HighRisingCityVisualizer_win_x86_64.exe`.

  * ***Mac***  
    Double click `HighRisingCityVisualizer/HighRisingCityVisualizer_mac.app`.

  * ***Linux***  
    Double click `HighRisingCityVisualizer/HighRisingCityVisualizer_linux/HighRisingCityVisualizer_linux.x86" (or .x86_64)`.

3. Run and profile a sample java program.(Note: sample programs are located in the Run folder)

  * ***Windows***   
    Double click `Run/win/MarioLike.bat` or `Run/win/Tetris.bat`.

  * ***Mac/Linux***   
    On terminal, execute a shell script. You need to set current directory `Run/linux_mac/`.
    ```
    cd Run/linux_mac/
    ./MarioLike.sh or ./Tetris.sh
    ```

## How to explore the City

* You can browse the city using the following mouse commands:
  * Rotate ... Right button drag
  * Zoom ... Wheel spin
  * Slide ... Wheel button drag

* When you place mouse cursor on 3D object (package, class or method), displays the tooltip which states the

## Sample Demonstrations:

* [Tetris game](https://github.com/exal99/Tetris)  
  The case study that was used for the VISSOFT paper.  
[![](http://img.youtube.com/vi/eleVo19Hp4k/0.jpg)](https://www.youtube.com/watch?v=eleVo19Hp4k)

* [MarioLike game](https://github.com/aidiary/javagame)  
(Not in the paper) The tool was able to detect a freezing bug. This bug is intermittent and not easily detectable.

[![](http://img.youtube.com/vi/_2GOglYqN8g/0.jpg)](https://www.youtube.com/watch?v=_2GOglYqN8g)

## Extras (Optional)

To profile your own java program, you can run the command:

`java -javaagent:"../HighRisingCityAgent/HighRisingCityAgent.jar" -jar Tetris.jar`
