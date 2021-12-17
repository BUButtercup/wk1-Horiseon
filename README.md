# wk1-Horiseon
Improving accessibility, increasing code efficiency.

The goal of this project was to improve accessibility of th assigned Horiseon marketing webpage for users that employ assistive devices, as well as streamlining existing code. I will be following the mock-up and acceptance criteria proposed.

This project really helped me realize the power of a sleek and well-laid-out code file. It's much easier to see what is where, and what is affecting what aspect of the published page when things are commented, tagged semantically, grouped well, and the selectors are standardized. I know I still have a ton to learn, but I feel like this increased my understanding and my ability to scan and evaluate code.

a link to the published project: https://bubuttercup.github.io/wk1-Horiseon/

The changes I made to the code are summarized as follows:

- Changed <title> to Horiseon Solutions

In HTML file:
- Converted div tags to semantic equivalents on lines.
- Added comments to identify the different sections of the page in the code
- Eliminated the ul and li in the header nav bar >> it was an unnecessary designation.
- Added title attribute to background image div. Also changed class to “background-image” to make more descriptive.
- Standardized class of the sections within the main content: they all required the same styling (also true of the img and h2 in those sections), so giving them the same class allowed condensation of CSS rules
- added unique ids to these sections for nav links
- Added alt tags to images in main sections
- Repeated class standardization for sidebar for same reason.
- Did not add alt images to the sidebar: these illustrations are purely decorative, they do not add to understanding of the text.

In CSS file:
- Ordered CSS by specificity, and tried to match to HTML structure for ease of locating pertinent code
- Added pertinent comments to match up sections with HTML and section on page
- Converted selectors made obsolete by the conversion of HTML tags to semantic equivalents
- Merged rule for .header div ul li into anchor rule set
- Eliminated .header div ul, as it was redundant (the a tags do the same thing)
- Took out p tag rule: 16px is the auto size
- Merged the rules for the three sections in <main> using a standardized class selector
- Did same for three sections in the <aside>

I would really appreciate any suggestions of improvements to my process or results that I could make to become a stronger developer.




