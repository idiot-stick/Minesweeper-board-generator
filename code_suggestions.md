### 1. improve the int-to-char routine
### 2. look at multi-dimensional array, or use a single dimensional array for the grid

`std::vector<std::vector<char>>` => `std::array<char>`

instead of writing `grid[x][y]` => `grid[x*grid_size + y]`
