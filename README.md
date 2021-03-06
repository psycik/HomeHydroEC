# HomeHydroEC
=============
An extension of Michael Ratcliffe's excellent EC project.   
<B>See the Project Wiki for a full description.  </B>  
https://github.com/ozarchie/HomeHydroEC/wiki  

## Extensions  
-------------
This project addresses the issue of polarization by implementing a square wave balanced resistor approach to measurement.  
An additional analog input channel is required.  
The 1k resistor is split in two as two 470R resistors and the probe inserted between the resistors.  
The voltage across the 470R sense resistor allows calculation of the sense current.  
The voltage across the prongs and the sense current allows determination of the electrical conductivity.  
An 18B20 sensor is connected to monitor the solution temperature.  

![Schematic](https://cloud.githubusercontent.com/assets/6479143/21031359/c254f52c-bdee-11e6-8f4b-8af198f6637a.png)

Testing and documentation is underway. Documentation is included in the code.  

The Kcell of the probe is calculated using standard formula and measurements of the AC probe. 
EC Measurements agree well with Chinese TDC&EC meters.  
See the Project Wiki for a full description.  

## Original Work  

Original ideas and program published by -:  

www.MichaelRatcliffe.com/projects  
https://www.element14.com/community/community/design-challenges/vertical-farming/blog/2015/09/13/automated-green-house-blogs-main-page  
 
  28/8/2015  Michael Ratcliffe  Mike@MichaelRatcliffe.com
 
 
   This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.
 
 
    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.
 
 
    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
