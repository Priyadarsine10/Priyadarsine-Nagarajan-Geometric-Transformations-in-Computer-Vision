
Geometric Transformations in Computer Vision

🔹 Transformations Covered

1. Euclidean Transformations

Operations: Rotation + Translation

Properties: Preserves both shape and size (rigid body motion).

Mathematical Form: Combination of a rotation matrix and a translation vector.

Use Case: Useful when the object is only moving/rotating without scaling.

Demo: A square rotated by 45° and shifted to a new position.



---

2. Similarity Transformations

Operations: Rotation + Translation + Uniform Scaling

Properties: Preserves shape but not size.

Mathematical Form: Special case of affine transformation with scaling factor k.

Use Case: Common in resizing images while keeping aspect ratio.

Demo: A square rotated, shifted, and scaled up by a factor of 2.



---

3. Affine Transformations

Operations: Rotation, Translation, Scaling (uniform or non-uniform), Shearing

Properties: Preserves parallelism of lines but not necessarily angles or distances.

Mathematical Form: Represented by a 2×3 affine matrix.

Use Case: Applied in skew corrections, image registration, and augmented reality.

Demo: A square distorted into a parallelogram or rectangle.



---

4. Projective Transformations (Homography)

Operations: Translation, Rotation, Scaling, Shearing, Perspective Warping

Properties: Preserves straight lines, but parallel lines may intersect (vanishing point).

Mathematical Form: Represented by a 3×3 homography matrix in homogeneous coordinates.

Use Case: Essential for perspective correction (e.g., document scanning, 3D view simulation).

Demo: A square warped into a trapezoid to simulate 3D depth.
