# Delta-Y Resistor Configuration Converter

A set of HP Prime graphing calculator programs to convert between delta and y resistor configurations, and display the result graphically.

## Delta and Y Resistor Configurations?

From left to right, the following image depicts delta and y resistor configurations, respectively.

![alt text](https://github.com/Aswin-SaiSubramanian/Delta-Y-Resistor-Configuration-Converter/blob/main/images/delta_y.png "delta and y resitor networks")

## Usage

### Delta to Y

On CAS mode, type **DtoY(ra, rb, rc)**, where ra, rb and rc are resistor values starting on the top edge of the delta configuration and going
counter-clockwise. Press "Enter" to show graphical result. Then press "Esc" to resume CAS mode.

example: DtoY(1,2,3)
output:

![alt text](https://github.com/Aswin-SaiSubramanian/Delta-Y-Resistor-Configuration-Converter/blob/main/images/DtoY_Example.PNG "DtoY usage example")

### Y to Delta

On CAS mode, type **YtoD(ra, rb, rc)**, where ra, rb, and rc are resitor values starting on the left hand of the Y configuration and going counter-clockwise.
Press "Enter" to show graphical result. Then press "Esc" to resume CAS mode.

example: YtoD(0.333333,1,0.5)
output:

![alt text](https://github.com/Aswin-SaiSubramanian/Delta-Y-Resistor-Configuration-Converter/blob/main/images/YtoD_Example.PNG "YtoD usage example")

## Dependency Tree

DtoY and YtoD take care of computations for resistor configuration conversions in each direction, while DRAW_TRIANGLE_AND_Y takes care of graphical output.

![alt text](https://github.com/Aswin-SaiSubramanian/Delta-Y-Resistor-Configuration-Converter/blob/main/images/DeltaY_Converter_Dependancy_Tree.png "Project dependenct tree")



                   
