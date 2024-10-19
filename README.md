# Indian Flag Using HTML & CSS

This project is an attempt to create the Indian national flag using only HTML and CSS. It includes the tricolor stripes (saffron, white, and green) and the Ashoka Chakra with its 24 spokes. The flag is designed to be as close to the real one as possible using basic web technologies.

## Preview

![Indian Flag Preview]('https://drive.google.com/file/d/1g0ADueMOU0mzSnXdZ_Z-Lt8Ix57Y3PSH/view?usp=drive_link') *(Add a screenshot of your flag here)*

## Features

- Responsive design that adapts to different screen sizes.
- Ashoka Chakra created using CSS transformations for accurate placement of the 24 spokes.
- Pure HTML and CSS solution without using any JavaScript or external libraries.

## Technology Stack

- **HTML**: Structure of the flag.
- **CSS**: Styling, including flexbox for layout and transforms for the Ashoka Chakra.

## How It Works

1. **Tricolor Sections**: 
   - The flag consists of three sections—saffron, white (with the Ashoka Chakra), and green. These are styled using simple `div` elements and background colors.

2. **Ashoka Chakra**:
   - The Ashoka Chakra is made up of 24 spokes. Each spoke is a thin line rotated in increments of 15 degrees from 0 to 360 degrees using the `transform` property in CSS.

## Getting Started

To run this project locally:

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/indian-flag-html-css.git
    ```

2. Navigate to the project directory:

    ```bash
    cd indian-flag-html-css
    ```

3. Open the `index.html` file in your browser to see the Indian flag.

## Code Explanation

### HTML

The basic structure includes a container for the flag (`.flag`) and nested elements for each section of the tricolor and the Ashoka Chakra:

```html
<div class="flag">
    <div class="stripe saffron"></div>
    <div class="stripe white">
        <div class="ashoka-chakra">
            <!-- Additional spokes here -->
        </div>
    </div>
    <div class="stripe green"></div>
</div>
