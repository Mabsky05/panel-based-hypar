# Panel-Based Hypar

![main image](/References/image_main.png)

## Summary
Hyperbolic paraboloid (diamond saddle roof) structure composed of square panels.
Optional: Skylights with adjustable size based on remote point. 
Adjustable parameters include: 

The location of four points of the hypar on the ground, defining its overall shape.
Size of the panels.
Circular skylights on the panels (size and location)


## Usage
Open .ghx file in Rhino 8, via Grasshopper in command line
View >> remote control panel to view inputs. 

## Description of Procedure
1) Draw a line connecting two points on the XY axis.  
![image 1](/References/1.png)

2) From each of the initial two points, extend two lines along the YZ axis (with differing Y-values), and subdivide each into an equal number of points. 
![image 2](/References/2.png)


3) Draw a line from each point that has an equal height to the another. Loft the drawn lines to create a surface.  
![image 3](/References/3.png)
![image 4](/References/4.png)


5) Subdivide the surface into square panels. Separate these panels into two groups.  Group 1 consists of two panels at the bottom of the surface. Group 2 consists of the rest of the panels. Draw optional centred circles on the group 2 panels. 
![image 5](/References/5.png)
![image 6](/References/6.png)

6) Extrude all panels outward from the normal of their planes. Create an additional extrusion for each Group 1 panel. These Group 1 extrusions are to be downward and flat to create a pedestal on the XY plane. 
![image 7](/References/7.png)
![image 8](/References/8.png)

7) Scale each Group 2 extrusion to their centre to a factor of about 0.9. 
![image 9](/References/9.png)
![image 11](/References/11.png)

(to be continued)

## Log

### 20/09/2024
First upload.

