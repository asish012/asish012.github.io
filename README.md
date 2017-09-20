## Headers
  ```
  We can use one hash '#' all the way up to six hashes '######' for different heading sizes.
  # This is an <h1> tag
  ## This is an <h2> tag
  ###### This is an <h6> tag
  ```

## Emphasis
- Italic:
  ```  
  *This text will be italic*
  _This will also be italic_
  ```
- Bold:
  ```
  **This text will be bold**
  __This will also be bold__    
  ```
- Combined:
  ```
  _We **can** combine them as well_
  ```

- Lists
  - Unordered:
    ```
    * Item 1
    * Item 2
      * Item 2.1
      * Item 2.2
    ```
  - Ordered:
    ```
    1. Item 1
    2. Item 2
      1. Item 2.1
      2. Item 2.2
    ```
  - Symbolic order:
    ```
    - Item 1
    - Item 2
      - Item 2.1
      - Item 2.2
    ```

## Images
  ```
  Format:  ![Alt Text](url)
  Example: ![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
  ```
    
## Links
  ```
  Format 1: Direct link
  Example:  http://github.com
  Format 2: [Link Name](http://actual.link)
  Example:  [GitHub](http://github.com)
  ```

## BlockQuotes
  ```
  > We Become the Story We Tell Ourselves - Borendro Kobi
  ```

## Inline code
  ```
  I think you should use an `unsigned int` instead `signed int`
  ```

## Code block
- With indent:
  ```
  Simply indent your code block with four spaces.
      if (something == true) {
        do something
      }
  ```
- Fencing (without indent):
  ```
  Fench all your code with two lines of three consequitive backticks (```), 
  and you don't need to indent anymore.
  ```
  
- Syntax highlighting
  ```
  In order to enable syntax highlighting add the language name with the opening line of backticks
  ```javascript
  ```
