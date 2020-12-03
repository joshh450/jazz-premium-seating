### Utah Jazz Premium Seating Pages

This project was built as part of the interview process with the Utah Jazz. The designs for the project can be found at the following link: https://xd.adobe.com/view/34c0425d-bfd2-49a8-a78b-30edd136cee8-6193/

## Run the Site

In order to run the site, simply open the index.html file in your browser of choice.

## Technical Details

The index.html uses the React and Babel CDN's to compile React into JavaScript. Because the CDN's are built for very basic usage, they did not play well with separating the scripts into their own files. This caused some re-usability issues with the content generated, so the code itself is pretty static despite being a SPA and using React State to render the content on the screen. I chose to focus my efforts on the design and User Interface of the project as opposed to the method of rendering.

## Design Specifications

The project was built most optimally (pixel-perfect) for the most common screen size: 1366x768. However, it is equipped to handle all of the most common desktop screen sizes: 1920x1080 | 1366x768 | 1280x1024 | 1280x800 | 1024x768

## CSS Structure

The HTML for the project was built semantically. Each section has a class assigned, and each child of the section is selected semantically after selecting the section class (i.e .page-section article{}), with a few exceptions.

The CSS itself is laid out using the "Outside In Method." This method orders the css as follows:

- Layout Properties (position, float, clear, display)
- Box Model Properties (width, height, margin, padding)
- Visual Properties (color, background, border, box-shadow)
- Typography Properties (font-size, font-family, text-align, text-transform)
- Misc Properties (cursor, overflow, z-index)