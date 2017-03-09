# Email-template

What is this template

The template is a framework for building hybvrid and responsive email newsletters. It consist of 3 files:

- HTML file containing the HTML markup and content
- framework.less containing all calculations for basic things like collumn widths etc
- styles.less contianing definitions for visual styling

It offers:
- A hybrid / responsive layout system
- Bootstrap like gridcollumn framework
- Easely adjustable dimensioning 
- Helper classes to adjust visual design and responsive behavior
- Works in all conventional emailclients 


How to use this template
1: Build HTML-file

Start building your own email template with the snippets provided in the 'Snippets' directory, or just choose an example email in the 'Examples' directory. Make sure that framework.css and styles.css are correctl;y linked.


2: Adjust main properties

All sizes of gridcollumns, gutters and paddings are calculated in this file based on some adjustable vairables. You can adjust those variables to your needs in the top of this document. Remember to parse this file to CSS each time!


3: Add styling

Finish the visual design by adding/adjusting further styling in styles.less (and parse this file to .CSS)


4: Inline styles

Send the email using Measuremail Spike of Measuremail M7 to have all CSS correctly inlined.
