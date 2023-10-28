# 2D-Array
A 2D array in C++ is a data structure that allows you to store elements in a grid-like format with rows and columns. It is an array of arrays, where each element is identified by two indices: one for the row and one for the column. This structure is suitable for representing tabular data, matrices, and grids in applications. 2D arrays are declared using the syntax `datatype arrayName[rowSize][colSize]`, specifying the data type, array name, and the number of rows and columns. They provide a versatile tool for handling structured data in a program.
## Initializing a 2D array in C++: </br>
int main() {</br>
    // Initialize a 2D array with 3 rows and 4 columns</br>
    int myArray[3][4] = {</br>
        {1, 2, 3, 4},   // First row</br>
        {5, 6, 7, 8},   // Second row</br>
        {9, 10, 11, 12} // Third row</br>
    };</br>

    // Accessing elements of the 2D array</br>
    cout << "Element at row 2, column 3: " << myArray[1][2] << endl; // Outputs: 7</br>

    return 0;</br>
}
