# Tables
## Create a table
- DESC
    - You can create tables with pipes `|` and hyphens `-`
    - `-` are used to create each column's header,while `|` separate each column
    - You must include a blank line before your table in order for it to correctly render.
- Text
    ```
    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |
    ```
- Go

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |
- Text not aligned with colums
    ```
    | Command | Description |
    | --- | --- |
    | git status | List all new or modified files |
    | git diff | Show file differences that haven't been staged |
    ```
- Go

    | Command | Description |
    | --- | --- |
    | git status | List all new or modified files |
    | git diff | Show file differences that haven't been staged |
## Formatting content within tables
- DESC
  - Align text to the left, right, or center of a column by including colons : to the left, right, or on both sides of the hyphens within the header row
- Text
    ```
    | Left-aligned | Center-aligned | Right-aligned |
    | :---         |     :---:      |          ---: |
    | git status   | git status     | git status    |
    | git diff     | git diff       | git diff      |
    ```
- Go

    | Left-aligned | Center-aligned | Right-aligned |
    | :---         |     :---:      |          ---: |
    | git status   | git status     | git status    |
    | git diff     | git diff       | git diff      |