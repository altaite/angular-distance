# Definition of angular distance
Measures similarity between two pairs of objects using their orientation toward each other.

Let A, B, C, D be identical rigid bodies in any orientation, and |AB| = |CD| = d (distance between centers of object A and B is equal to that of C and D). Then I define the angular distance between pairs AB and BD as  follows:
1. Move AB so that centers of A and B have coordinates (-d/2, 0, 0) and (d, 0, 0) respectivelly.
2. Move CD so that centers of C and D have coordinates (-d/2, 0, 0) and (d, 0, 0) respectivelly.
3. Let r be a rotation around axis X and ac, bd any rotations such that: C = ac(r(A)) and D = bd(r(B)). Let s be the sum of angles of rotations ac and bd. The minimum s is the angular distance.

This can be computed numerically by finding r minimizing s. This library computes s analytically.
