# Boardify Whiteboard

A simple whiteboard, built with [paper.js](https://github.com/paperjs/paper.js), [jquery](https://github.com/jquery/jquery) and [bootstrap](https://github.com/twbs/bootstrap).

# How To Run?

## Python (using `http.server` module)\*

if you have python installed

1. Open a terminal or command prompt and navigate to the directory where your `index.html` file is located.
2. Run the following command to start the server: `python -m http.server` (or `python3 -m http.server` if you have both Python 2 and 3 installed).

This will start a simple HTTP server that serves files from the current directory. You can then access your `index.html` file by navigating to `http://localhost:8000` in your web browser.

## Node.js (using `http-server` package)\*

if you have node.js

1. Open a terminal or command prompt and navigate to the directory where your `index.html` file is located.
2. Run the following command to install the `http-server` package: `npm install http-server` (or `yarn add http-server` if you use Yarn).
3. Run the following command to start the server: `http-server` (or `npx http-server` if you don't want to install it globally).

This will start a simple HTTP server that serves files from the current directory. You can then access your `index.html` file by navigating to `http://localhost:8080` in your web browser.

## Note:

You can also use other packages like `express` or `serve` to start a server in Node.js, but `http-server` is a simple and easy-to-use option for this purpose.

# Shortcuts

| Result                                                   | Shortcut            | Mode |
| -------------------------------------------------------- | ------------------- | ---- |
| Select area                                              | Shift               | Any  |
| Move                                                     | Mouse 3             | Any  |
| Delete                                                   | Mouse 2             | Any  |
| Delete selected items                                    | Del, Backspace      | Any  |
| Zoom                                                     | Mouse wheel         | Any  |
| Change stroke width                                      | Space + Mouse wheel | Any  |
| Clear whiteboard                                         | Space + Del         | Any  |
| Reset whiteboard (clear the whiteboard and reset values) | Space + Backspace   | Any  |
| Change mode to Move                                      | Space + 1           | Any  |
| Change mode to Draw                                      | Space + 2           | Any  |
| Change mode to Delete                                    | Space + 3           | Any  |
| Change mode to Text                                      | Space + 4           | Any  |
| Select single item                                       | S                   | Move |
| Horizontal move                                          | Q                   | Move |
| Vertical move                                            | W                   | Move |
| Rotate selected items                                    | R                   | Move |
| Draw rectangle                                           | Q                   | Draw |
| Draw circle (1:1)                                        | W                   | Draw |
| Draw circle                                              | W + E               | Draw |
| Draw straight line                                       | A                   | Draw |
| Draw horizontal line                                     | A + S               | Draw |
| Draw vertical line                                       | A + D               | Draw |
