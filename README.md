# User tag exercise: lab page

Single-page lab site for the RUM user identifier exercise.

1. Open the page and enter your name, then select **Set name**.
2. The page writes the name into `<span id="lab-username" data-user="<name>">`.
3. Click a few buttons to generate events. A captured property with the CSS selector `#lab-username` picks up the name.

The Dynatrace RUM JavaScript tag is loaded in the page's `<head>`.
