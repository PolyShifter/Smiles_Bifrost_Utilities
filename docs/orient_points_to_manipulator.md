orient_points_to_manipulator

Orients the points to said manipulator's position using a float value.

- Use a _manipulator_field_ and _interpret_auto_port_as_scalar_ nodes to have a cleaner falloff.
- Using this in conjunction with _cull_points_ option, will drastically increase performance.
- Using the diagnostic toggle will generate cubes at the locations of your points, to show the orientation.

## Inputs

### points
> The points to orient to the manipulator.

### manipulator_position
> Position of your manipulator.

### fraction
> Weights from 0-1 for how much the points should enherit the new orientation.

### rotation_vector
> Direction in which you want your points to be oriented from the manipulators position.

### degrees
> Rotation amount in degrees.

### cull_points
> Will cull_points based on the strength of the _fraction_.

### cull_sharpness
> A multiplyer of the _fraction_ to allow for tighter boundaries of the cull.

## Display

### length, width, height
> The dimensions of the cube you wish to be generated for diagnostic display.
___

## Outputs

### out_points
> Points with new orientations.