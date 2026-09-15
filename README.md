import math


def main():
    """Calculate and display the distance between two points."""

    print("=== Distance Calculator ===")

    # Get the coordinates of the first point from the user.
    
  x1 = float(input("Enter x1: "))
  y1 = float(input("Enter y1: "))

    # Get the coordinates of the second point from the user.
    
x2 = float(input("Enter x2: "))
y2 = float(input("Enter y2: "))

    # Calculate the horizontal and vertical differences.
    
horizontal_difference = x2 - x1
vertical_difference = y2 - y1

    # Use the distance formula:
    # distance = sqrt((x2 - x1)^2 + (y2 - y1)^2)
    
 distance = math.sqrt(
    horizontal_difference ** 2
    + vertical_difference ** 2
    )

    # Display the calculated distance.
  print(f"\nThe distance between the two points is: {distance}")


if __name__ == "__main__":
    main()
