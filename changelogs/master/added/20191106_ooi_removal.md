# Removal of Coordinate-Based Augmentables Outside of the Image Plane

* Added `BoundingBox.compute_area_out_of_image()`.
* Added `BoundingBox.compute_out_of_image_factor()`.
* Added `Polygon.compute_area_out_of_image()`.
* Added `Polygon.compute_out_of_image_factor()`.
* Added `LineString.compute_out_of_image_factor()`.
* Changed `Polygon.area` to return `0.0` if the polygon contains less than
  three points (previously: exception).