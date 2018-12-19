# Title
## Basic Lists
- DESC
    - Unordered list by `-` or `*`
    - Ordered list by number and `.`
- Text
    ```
    - George Washington
    - John Adams
    - Thomas Jefferson
    1. James Madison
    2. James Monroe
    3. John Quincy Adams
    ```
- Go
    > - George Washington
    > - John Adams
    > - Thomas Jefferson
    > 1. James Madison
    > 2. James Monroe
    > 3. John Quincy Adams
## Nested Lists
- DESC
    - Create a nested list by indenting one or more list items below another item
    - `-` or `*` should lie directly below the first character of the text in the item above it
- Text
    ```
    1. First list item
       - First nested list item
         - Second nested list item
    ```
- Go
    > 1. First list item
    >    - First nested list item
    >      - Second nested list item
## Task lists
- DESC
    - To mark a task as complete, use `[x]` (_~~only rendered in Github~~_)
- Text
    ```
    - [x] Finish my changes
    - [ ] Push my commits to GitHub
    - [ ] Open a pull request
    ```
- Go
    > - [x] Finish my changes
    > - [ ] Push my commits to GitHub
    > - [ ] Open a pull request
    