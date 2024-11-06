# GazeBubble_Dataset
This is the data set to analysis the participants eye-in-head angle. 
We collected data over the entire process, amounting to 3,366,925 frames and lasting approximately 12 hours in total. 
Our analysis focused solely when participants successfully completed a 2-second sustained gaze on the target, total 1,295,037 frames. 
Contributing to a better understanding of participants’ target acquisition behavior and aiding in the design and evaluation of future gaze-based interaction techniques.

## Dataset Name
There are 15 folders, each folder includes the same folder and name, we name each folder GazeData_Dis_X_Den_XXX_Angle_X, the 'X' is the parameter to make the parameter of the experiment.
| GazeData_    | Dis_X               | Den_XXX                        | Angle_X            |
|--------------|---------------------|--------------------------------|--------------------|
| Dataset name | X = 1, 3, 10 and 30 | XXX = Spread, Normal and Dense | X = 1, 3, 5 and 10 |

## Dataset Parameter
The data includes participants’ eye positions and direction vectors, head positions and direction vectors, the name of the triggered target (or ’None’ if no target was triggered), task target name and position, and experimental parameters such as density, target depth, and target size.
There is an example of our dataset parameter.

| Trigger_Name           | Head_Position        | Head_Direction       | Eye_Position         | Eye_Direction        | Target_Name            | Target_Distance | Target_Position     | Target_Size |  
|------------------------|----------------------|----------------------|----------------------|----------------------|------------------------|-----------------|---------------------|-------------|
| Far_Peripheral1314_#36 | (-0.04, 7.58, -0.21) | (-0.65, -0.69, 0.42) | (-0.04, 7.58, -0.21) | (-0.49, -0.59, 0.64) | Far_Peripheral1415_#57 | 1               | (-0.70, 8.35, 0.09) | 1           |


