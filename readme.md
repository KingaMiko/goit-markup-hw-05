Create a repository goit-markup-hw-05.</br>
Clone the created repository and copy the previous work files into it.</br>
Add animated decorative effects to layout pages of homework #5.</br>
Set up GitHub Pages and add a link to the live page in the header of the GitHub repository.</br>

Criteria for work acceptance by the tutor

Project

«A1» All styles are contained in one styles.css file in the css folder.</br>
«A2» Source code is formatted with Prettier.</br>
«A3» All images and text content are taken from the layout.</br>
«A4» All HTML pages have a style normalizer modern-normalize.</br>
«A5» The code is in line with the guide.</br>
«A6» The modal window script is linked in HTML as a separate file, modal.js.</br>

Markup

«B1» HTML-markup is done for all layout elements.</br>
«B2» Tags are used according to their semantics.</br>

Styling

«C1» For all hover and focus effects (color, background, shadow), transitions are made. Time is set to 250ms, and the timing function is cubic-bezier(0.4, 0, 0.2, 1).</br>
«C2» Transitions and animations explicitly specify the properties to be animated. There is no all value anywhere.</br>
«C3» In the What We Do section, text with background is positioned over the image.</br>
«C4» In the main navigation, the current page's link (which the user is currently viewing) is underlined using the ::after pseudo-element.</br>
«C5» Blue overlay with text appears on the cards of the Portfolio page when hovering over any part of the card.</br>
«C6» Blue overlay slides out from the bottom of the cards on the Portfolio page, as shown in the video.</br>
«C7» Pseudo-elements have no text content in the content property. They are used exclusively for decorative purposes.</br>

Modal window

«D1» The markup and styling of the modal "backdrop" (dark semi-transparent background) are done.</br>
«D2» "Backdrop" fills 100% of the height and width of the browser viewport and stays fixed in it.</br>
«D3» The markup and styling of the modal window are done.</br>
«D4» The modal window is vertically and horizontally positioned in the middle of the backdrop.</br>
«D5» The markup and styling of the button for closing the modal window in the upper right corner are done.</br>
«D6» By default, the modal and backdrop are hidden using the is-hidden class in the backdrop, whose selector uses the visibility, opacity and pointer-events properties.</br>
«D7» If you remove the is-hidden class from the backdrop, the backdrop and modal window will appear.</br>
«D8» The modal window opening/closing is animated using a transition with an arbitrary effect such as scale or translate, and opacity.</br>

Modal window opening/closing

A modal window with the order form opens by clicking on the "Order a service" button. In order for the script to work, you need to add special attributes to the markup, used by the script to search for elements:

data-modal-open to the button for modal window opening;
data-modal-close to the button for modal window closing;
data-modal to the modal window's backdrop.
Then, before the closing body tag, add the script tag with a link to the script file for the modal window.

The script to be copied and pasted into the modal.js file.
