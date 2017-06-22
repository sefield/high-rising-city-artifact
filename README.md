# High Rising City Artifact
VISSOFT 2017 artifact for the following paper:

Katsuya Ogami, Raula Gaikovina Kula, Hideaki Hata, Takashi Ishio, and Kenichi Matsumoto, "Using High-Rising Cities to Visualize Performance in Real-Time," In Proc. of 5th IEEE Working Conference on Software Visualization (VISSOFT 2017), (accepted, to appear).

## How to run

1. Clone or download this repository.

2. Execute a visualizer program. You may have to set execution permission of program file.

  * Windows  
    Double click `HighRisingCityVisualizer/HighRisingCityVisualizer_win_x86_64/HighRisingCityVisualizer_win_x86_64.exe`.

  * Mac  
    Double click `HighRisingCityVisualizer/HighRisingCityVisualizer_mac.app`.

  * Linux  
    Double click `HighRisingCityVisualizer/HighRisingCityVisualizer_linux/HighRisingCityVisualizer_linux.x86" (or .x86_64)`.

3. Run one of sample java programs.

  * Windows  
    Double click `Run/win/MarioLike.bat` or `Run/win/Tetris.bat`.

  * Mac or Linux  
    On terminal, execute a shell script. You need to set current directory `Run/linux_mac/`.
    ```
    cd Run/linux_mac/
    ./MarioLike.sh or ./Tetris.sh
    ```

## How to explore city

* You can controll camera with mouse.
  * Rotate ... Right button drag
  * Zoom ... Wheel spin
  * Slide ... Wheel button drag

* When you place mouse cursor on 3D object (package, class or method), you can see description about it.

## Movie

* Tetris game, which is discussed in the paper.  
[![](http://img.youtube.com/vi/eleVo19Hp4k/0.jpg)](https://www.youtube.com/watch?v=eleVo19Hp4k)
* MarioLike game  
We found a short freeze bug in this game on Windows. When some sound effects run, the game sometimes freezes.  
[![](http://img.youtube.com/vi/_2GOglYqN8g/0.jpg)](https://www.youtube.com/watch?v=_2GOglYqN8g)
