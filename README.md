<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sudoku Solver</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        p, li {
            color: #555;
        }
        .code {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            padding: 10px;
            margin: 10px 0;
            display: block;
            white-space: pre-wrap;
        }
        a {
            color: #0366d6;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>Sudoku Solver</h1>
    <p>This project is a meticulously crafted Java application that solves Sudoku puzzles using the power of recursion. The graphical user interface (GUI) is seamlessly brought to life through the robust capabilities of Swing. Furthermore, the project strategically incorporates principles of Object-Oriented Programming (OOP), exemplifying a holistic approach to software development.</p>

  <h2>Features</h2>
    <ul>
        <li>Efficient Sudoku puzzle solver using recursive algorithms</li>
        <li>Intuitive and interactive GUI built with Swing</li>
        <li>Clear demonstration of Object-Oriented Programming principles</li>
    </ul>

  <h2>How It Works</h2>
  <ol>
        <li><strong>Input:</strong> The user inputs a Sudoku puzzle through the GUI.</li>
        <li><strong>Validation:</strong> The input puzzle is validated to ensure it meets the standard Sudoku rules.</li>
        <li><strong>Recursion:</strong> The core solving algorithm uses recursion to fill in the blanks. It attempts to place numbers 1-9 in empty cells while checking if the current state of the board is valid.</li>
        <li><strong>Backtracking:</strong> If the algorithm encounters a situation where no valid number can be placed, it backtracks to the previous step and tries a different number. This process repeats until the puzzle is solved.</li>
        <li><strong>Display Solution:</strong> Once the puzzle is solved, the solution is displayed on the GUI.</li>
    </ol>

  <h2>Usage</h2>
    <p>Once the application is running, you can interact with the Sudoku solver through the GUI. Input your Sudoku puzzle and click "Solve" to see the solution.</p>


</body>
</html>
