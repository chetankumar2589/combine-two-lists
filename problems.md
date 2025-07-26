Problem: Combining two lists
Consider a list of elements within a line having position and values in the following format:

[
    {
        "positions": [left_position, right_position],
        "values": [value1, value2, ...]
    },
    ...
]


The left_position and right_position represents the position of the element in the line. 
Write code to combine two lists of the above format sorted by the left position. 
Values of the elements are to be combined if more than half of an element is contained within the other and positions of the element that appears first can be considered.
