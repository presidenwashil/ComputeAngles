# Compute Angles

## Description

The `ComputeAngles` Java project calculates the three angles of a triangle based on three points entered by the user. The program prompts the user to input the coordinates (x, y) of three points, which represent the vertices of a triangle. It then computes the lengths of the sides and the angles using trigonometric functions and displays the results.

## Usage

1. **Compile the Program**: Compile the `ComputeAngles.java` file using your Java compiler:
    ```
    javac ComputeAngles.java
    ```

2. **Run the Program**: Execute the program from the command line:
    ```
    java ComputeAngles
    ```

3. **Input**: Enter three points as coordinates (x, y) when prompted. The format is as follows:
    ```
    Enter three points: x1 y1 x2 y2 x3 y3
    ```

4. **Output**: The program will display the three angles of the triangle in degrees, rounded to two decimal places.

## Example

After running the program, you may see output similar to the following example:

Enter three points: 0 0 1 1 0 1
The three angles are 45.0 45.0 90.0


## Notes

- The program uses trigonometric functions such as `Math.sqrt` and `Math.acos` to calculate the lengths of the sides and angles of the triangle.
- The angles are rounded to two decimal places for better readability.
- Ensure that the input points form a valid triangle; otherwise, the program may produce inaccurate results.
