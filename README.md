[![DOI](https://zenodo.org/badge/95059554.svg)](https://zenodo.org/badge/latestdoi/95059554)

# High Rising City Artifact [![GitHub Logo](http://vissoft17.dcc.uchile.cl/img/artifact.png)](http://vissoft17.dcc.uchile.cl/)
This repository contains the VISSOFT 2017 artifact for the following paper:

>Katsuya Ogami, Raula Gaikovina Kula, Hideaki Hata, Takashi Ishio, and Kenichi Matsumoto, "Using High-Rising Cities to Visualize Performance in Real-Time,". In Proc. of 5th IEEE Working Conference on Software Visualization (VISSOFT 2017), pp. 34-42.

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

* When you place mouse cursor on 3D object (package, class or method), displays the a tooltip that describes the highlighted building.

## Sample Demonstrations:

* [Tetris game](https://github.com/exal99/Tetris)  
  The case study that was used for the VISSOFT paper.  
[![](http://img.youtube.com/vi/eleVo19Hp4k/0.jpg)](https://www.youtube.com/watch?v=eleVo19Hp4k)

* [MarioLike game](https://github.com/aidiary/javagame)  
(Not in the paper) The tool was able to detect a freezing bug. This bug is intermittent and not easily detectable.
[![](http://img.youtube.com/vi/_2GOglYqN8g/0.jpg)](https://www.youtube.com/watch?v=_2GOglYqN8g)

## Extras (Optional)

To profile your own java program, you can execute the command below (i.e., replacing the Tetris.jar with your own program at `Run/win/Tetris.bat` or `Run/linux_mac/Tetris.sh`):

`java -javaagent:"../HighRisingCityAgent/HighRisingCityAgent.jar" -jar Tetris.jar`

## License

MIT License

Copyright (c) sefield Team and Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

## ASM Library Usage License

Copyright (c) 2000-2011 INRIA, France Telecom
All rights reserved.

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions
are met:

1. Redistributions of source code must retain the above copyright
   notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright
   notice, this list of conditions and the following disclaimer in the
   documentation and/or other materials provided with the distribution.

3. Neither the name of the copyright holders nor the names of its
   contributors may be used to endorse or promote products derived from
   this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF
THE POSSIBILITY OF SUCH DAMAGE.
