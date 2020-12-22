# Delta-Y Resistor Configuration Converter

A set of HP Prime programs to convert between delta and y resistor configurations, and display the result graphically.

## Delta and Y Resistor Configurations?

From left to right, the following image depicts delta and y resistor configurations, respectively.

![alt text](https://github.com/Aswin-SaiSubramanian/Delta-Y-Resistor-Configuration-Converter/blob/main/delta_y.png "delta and y resitor networks")

## Usage

### Delta to Y

On CAS mode, type **DtoY(ra, rb, rc)**, where ra, rb and rc are resistor values starting on the top edge of the delta configuration and going
counter-clockwise. Press "Enter" to show graphical result. Then press "Esc" to resume CAS mode.

  example: 
    command: DtoY(1,2,3)

### Y to Delta

On CAS mode, type **YtoD(ra, rb, rc)**, where ra, rb, and rc are resitor values starting on the left hand of the Y configuration and going counter-clockwise.
Press "Enter" to show graphical result. Then press "Esc" to resume CAS mode.

  example:
    command: YtoD(0.333333,1,0.5)

## Dependency Tree
