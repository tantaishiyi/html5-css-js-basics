# CSS Basic Syntax

## CSS ID and Class

### ID
The ID selector specifies a style for HTML elements with a specific ID. It is defined in CSS with `#`.

### Class
The class selector styles a group of elements. Classes can be used on multiple elements and are represented with a dot (`.`) in CSS.

## Creating CSS
There are three methods to insert a stylesheet:

### External Style Sheet
- Ideal for multiple pages.
- Changes site appearance by modifying one file.
- Use the `<link>` tag in the document's `<head>`:
  ```html
  <link rel="stylesheet" type="text/css" href="mystyle.css">
  ```
- Save the file with a `.css` extension.

### Internal Style Sheet
- Use the `<style>` tag within the `<head>` of a single document.

### Inline Styles
- Use the `style` attribute directly in an HTML tag.
- Best for styles applied to an element only once.

## Multiple Style Priority
The priority of styles is:
1. Inline style
2. Internal style sheet
3. External style sheet
4. Browser default style

## CSS Background
- **Shorthand properties**:
  - `background-attachment`
  - `background-color`
  - `background-image`
  - `background-position`
  - `background-repeat`

## CSS Text Properties
| Property           | Description                                        |
|--------------------|----------------------------------------------------|
| `color`            | Sets the color of text                             |
| `direction`        | Sets the text direction                            |
| `letter-spacing`   | Sets the space between characters in text          |
| `line-height`      | Sets the line height                               |
| `text-align`       | Aligns the text in an element                      |
| `text-decoration`  | Adds decoration to text                            |
| `text-indent`      | Indents the first line of text in an element      |
| `text-shadow`      | Sets the shadow effect for text                    |
| `text-transform`   | Controls text capitalization                       |
| `vertical-align`   | Sets vertical alignment of an element              |
| `white-space`      | Handles white space inside an element              |
| `word-spacing`     | Sets spacing between words                         |

## CSS Fonts
| Property           | Description                                        |
|--------------------|----------------------------------------------------|
| `font`             | Sets all font properties in one declaration        |
| `font-family`      | Specifies the font family for text                 |
| `font-size`        | Specifies the font size of text                     |
| `font-style`       | Specifies the font style for text                   |
| `font-weight`      | Specifies the weight of a font                      |

## CSS Links
### Link Styles
- Style links using any CSS properties.
- Four link states:
  - `a:link` - unvisited link
  - `a:visited` - visited link
  - `a:hover` - mouse over link
  - `a:active` - link when clicked

### Order Rules
- `a:hover` must come after `a:link` and `a:visited`
- `a:active` must come after `a:hover`

## CSS Tables
| Property               | Description                                       |
|------------------------|---------------------------------------------------|
| `list-style`           | Sets all properties for a list in one declaration  |
| `list-style-image`     | Specifies an image as the list-item marker       |
| `list-style-position`  | Specifies the position of the list-item markers   |
| `list-style-type`      | Specifies the type of list-item marker            |

## CSS Box Model
All HTML elements are considered boxes. The box model includes:
- **Margin**: Clears an area outside the border (transparent).
- **Border**: A border around padding and content.
- **Padding**: Clears an area around content (transparent).
- **Content**: Where text and images appear.

## CSS Dimensions
| Property               | Description                                       |
|------------------------|---------------------------------------------------|
| `height`               | Sets the height of an element                     |
| `line-height`          | Sets the line height                               |
| `max-height`           | Sets the maximum height of an element             |
| `max-width`            | Sets the maximum width of an element              |
| `min-height`           | Sets the minimum height of an element             |
| `min-width`            | Sets the minimum width of an element              |
| `width`                | Sets the width of an element                       |

## CSS Overflow
The `overflow` property controls content fitting:
- **visible**: Default; content is not clipped.
- **hidden**: Content is clipped and invisible.
- **scroll**: Content is clipped, but scrollbar is added.
- **auto**: Scrollbar added if content is clipped.
- **inherit**: Inherits value from the parent element.

## CSS Float
- Elements float horizontally.
- Floated elements move left or right until they touch the container or another floated element.

## CSS Layout Horizontal Alignment
### Center Align Elements
- Use `margin: auto;` with a specified width.

### Center Align Text
- Use `text-align: center;`.

### Center an Image
- Use `margin: auto;` and set the image to a block element.

### Left and Right Align - Using Position
- Use `position: absolute;` for alignment.

### Left and Right Align - Using Float
- Use `float` to position elements.

## CSS Combinators
Four types of combinators:
- **Descendant selector** (space)
- **Child selector** (>)
- **Adjacent sibling selector** (+)
- **General sibling selector** (~)

## CSS Pseudo-classes
### Examples
- `:checked` - Selects checked `<input>` elements.
- `:disabled` - Selects disabled `<input>` elements.
- `:first-of-type` - Selects the first `<p>` element of its parent.
- `:hover` - Selects links on mouse over.

## CSS Pseudo-elements
### Examples
- `::before` - Inserts content before an element.
- `::after` - Inserts content after an element.

## CSS Navigation Bar
### CSS Dropdown
- Use a container (`<div>`) for dropdown content.
- Style with `.dropdown` and `.dropdown-content` classes.

## CSS Media Types
### @media Rule
Allows different styles for different media:
- `all`, `screen`, `print`, etc.

## CSS Attribute Selectors
Style HTML elements with specific attributes.

## CSS Forms
### Input Field Styles
Customize padding, borders, colors, focus styles, and more.

## CSS Counters
| Property               | Description                                       |
|------------------------|---------------------------------------------------|
| `content`              | Used with `::before` and `::after` to insert content |
| `counter-increment`    | Increments counter values                          |
| `counter-reset`        | Creates or resets counter values                   |

## CSS Website Layout
Common layout parts include header, navigation, content, and footer.

## CSS !important
The `!important` rule adds more importance to a property/value, overriding other declarations regardless of specificity.