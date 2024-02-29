# iPod 

## Overview

This project is an implementation of an iPod-inspired user interface, featuring a wheel-based navigation system. The project utilizes HTML, CSS for styling, and the ZingTouch library for capturing rotation events. It also includes functionality to handle menu selection, screen transitions, and a basic navigation flow.

## Features

1. **Wheel UI with CSS Positioning:**
   - The wheel UI is designed using HTML and styled with CSS.
   - `position: absolute` is employed to position various divs on top of the wheel div.

2. **Rotation Event Handling with ZingTouch:**
   - The [ZingTouch library](https://zingchart.github.io/zingtouch/) is used to capture rotate events.
   - Event listeners are added to log rotation events to the console when moving around the wheel.

3. **Side Menu and Active List Item:**
   - A separate screen component contains a side menu and display area.
   - One of the list items has an active class for a distinct background color.

4. **Changing Active Menu Item with Wheel Rotation:**
   - The rotate event from ZingTouch is utilized to change the active menu item based on the angle.
   - The distanceFromLast property helps in determining whether the angle change is significant (e.g., >15 degrees).

5. **Handling Click on Menu Item:**
   - Clicking on a menu item hides the menu and displays another component based on the selected option.

6. **Menu Button Navigation:**
   - The MENU button has an onClick event listener that allows users to navigate back to the previous page.
   - For instance, if the user is on /songs, clicking MENU should navigate back to the home page.

7. **Improved UI:**
   - Additional focus has been given to CSS styling to enhance the overall UI.
   - Different screens and routes are accommodated for a more comprehensive user experience.


## How to Run

1. Clone the repository:

   ```bash
   git clone <https://github.com/Ananthuak16/IPod.git>
   ```

2. Open the `index.html` file in a web browser.

3. Explore the iPod-inspired UI and test the various functionalities.

## Credits

- [ZingTouch library](https://zingchart.github.io/zingtouch/)

## Improvements

Feel free to contribute and make improvements to the project. You can enhance UI, add additional features, or optimize the code.

## License



Happy navigating! 🎧📱