# ALGORITHM-LAB-PROJECT-
Student Info:
Abdullah Mohammed
Id: 222-115-105


/**********************************************************************************************************************************************************************************/


### Project Description:
- **Game Type:** Console-based car racing game.
- **Programming Language:** C++.
- **Libraries Used:** `iostream`, `windows.h`, `time.h`, `conio.h`.
- **Game Features:** 
  - Player controls a car using 'A' and 'D' keys to avoid obstacles (enemies).
  - Score increases as the player avoids collisions.
  - Simple menu system to start the game, view instructions, or quit.

### Build and Run Instructions:

#### Dependencies:
- This project uses standard C++ libraries and Windows-specific headers (`windows.h`, `conio.h`), which are typically available in most C++ development environments for Windows.
- A C++ compiler compatible with these libraries (e.g., Visual Studio's C++ compiler, MinGW, etc.) is required.

#### Steps to Build and Run:
1. **Download the Source Code:**
   - Copy the provided C++ code into a file, naming it with a `.cpp` extension (e.g., `car_game.cpp`).

2. **Compile the Code:**
   - Open a C++ development environment or a terminal/command prompt with a C++ compiler installed.

   - Use the appropriate command to compile the code. For example, using MinGW on Windows:
     ```
     g++ car_game.cpp -o car_game
     ```

3. **Run the Game:**
   - After successful compilation, execute the compiled binary:
     ```
     car_game.exe
     ```

4. **Play the Game:**
   - Follow the instructions displayed in the console.
   - Use 'A' and 'D' keys to control the car and avoid collisions.
   - Press 'ESC' to quit the game.

### Additional Instructions:
- **Controls:** 
  - Use 'A' key to move the car left.
  - Use 'D' key to move the car right.
  - Press 'ESC' to exit the game at any time.

- **Menu Options:** 
  - Start Game: Begins the car racing game.
  - Instructions: Displays control instructions for the game.
  - Quit: Exits the program.

- **Compatibility:** 
  - This code is primarily designed for Windows environments due to its dependency on the `windows.h` header for console manipulation.

- **Note:** 
  - Ensure your development environment supports the necessary C++ libraries for console input/output and system calls (`getch()`, `SetConsoleCursorPosition()`, etc.).
  - Adjustments may be needed if compiling and running on non-Windows platforms or different development environments.

Follow these steps, and you should be able to compile, run, and enjoy the simple car racing game in the console!
