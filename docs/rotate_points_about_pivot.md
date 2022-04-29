# `rotate_points_about_pivot`
Rotates all given points about another location in world space. Will update `point_orientation` and `point_position` on given points. (Works with mesh or points)

## Inputs

### `points`
The geometries with points to be rotated.

### `pivot_position`
Location in world space to rotate the points about.

### `degrees`
The angle at which to rotate.

## Display

### `shape`
Shape of point to represent pivot location.

### `default_size`
Scale of point to represent pivot location.

### `color`
Color of point to represent pivot location.

## Output

### `out_geometry`
The geometry/points after rotation.