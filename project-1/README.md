# Midnight Echo Band Website

## Project overview

Midnight Echo is a fictional indie rock band based in London.  
This static front end website presents information for fans and event organisers.  
It helps users learn about the band, listen to music, view upcoming shows, and request bookings.  
The site supports the goals of the band by showcasing music, promoting upcoming shows, and making it easy to enquire about bookings.  

The project was created using custom HTML and CSS and follows the principles of user experience design, accessibility, and responsive layout.  

## Target audience and user stories

Primary audiences  

<ol>
  <li>Fans and potential fans who want to learn about the band, listen to music, and follow them on social platforms.</li>
  <li>Event organisers who want to assess whether Midnight Echo is suitable for their event and request a booking.</li>
</ol>

Key user stories  

<ol>
  <li>As a new visitor, I want to understand who the band is and what style of music they play so I can decide if I am interested.</li>
  <li>As a fan, I want to see photos, listen to sample tracks, and watch videos so I can enjoy their content.</li>
  <li>As an event organiser, I want to see availability, pricing guidance, and booking contact details so I can decide whether to hire them.</li>
  <li>As a social media user, I want links to their profiles so I can follow them and stay updated.</li>
</ol>

The site content and layout were designed to address these user stories directly.  

## Features

<ul>
  <li>Clear main navigation across all pages.</li>
  <li>Home page with hero section, audio samples, and a live performance video.</li>
  <li>About page with band history, member profiles, and testimonials.</li>
  <li>Shows and booking page with upcoming dates, ticket links, and booking information.</li>
  <li>Responsive layout that adapts to mobile, tablet, and desktop screen sizes.</li>
  <li>Accessible colour contrast, semantic HTML, and descriptive alternative text for images.</li>
  <li>External links that open in new tabs.</li>
  <li>Real content written for a real audience.</li>
</ul>

## Information architecture

Pages included in the project  

<ol>
  <li><code>index.html</code>  
    Overview of the band, key selling points, and featured media.</li>
  <li><code>about.html</code>  
    Band story, member profiles, and testimonials.</li>
  <li><code>shows.html</code>  
    Upcoming shows table and booking information for event organisers.</li>
</ol>

Navigation  

<ul>
  <li>A consistent header with logo and main navigation menu appears on every page.</li>
  <li>The footer includes contact details and social media links.</li>
</ul>

## UX and accessibility

The design follows user experience and accessibility principles.  

<ul>
  <li>Information hierarchy: headings structure each page, and content is grouped into clear sections.</li>
  <li>Priority of information: key actions such as booking and listening to music are highlighted with buttons and headings.</li>
  <li>User control: audio and video never autoplay, and users choose when to start media.</li>
  <li>Consistency: colours, typography, and component styles remain consistent across all pages.</li>
  <li>Accessibility: strong colour contrast, semantic HTML, descriptive link text, and alternative text for images.</li>
</ul>

Any deliberate deviations from common user experience patterns would be documented, but the current design follows accepted practice.  

## Distinction level UX justification

This project demonstrates the characteristics of craftsmanship expected at distinction level.  

### Information hierarchy

Content is structured with clear headings that guide the user through each page.  
Important information appears first, such as the introduction to the band and the booking call to action.  
Sections are grouped by purpose, which allows users to find information quickly and intuitively.  

### User control

All media requires user interaction to begin.  
There are no automatic pop ups or autoplaying elements.  
Navigation remains consistent across all pages and provides immediate feedback through active link styling.  

### Consistency

The colour palette, typography, spacing, and component styles remain consistent across the entire site.  
This creates a unified experience and supports the identity of the band.  

### Accessibility

The site uses semantic HTML, descriptive alternative text, and strong colour contrast.  
Interactive elements are reachable with keyboard navigation.  
Headings follow a logical order to support screen reader users.  

### Real world alignment

All content is written for real users rather than placeholder text.  
The site directly addresses the user stories defined at the start of the project.  
The Shows page supports event organisers, while the Home and About pages support fans and new visitors.  

## Technologies used

<ul>
  <li>HTML for semantic structure.</li>
  <li>CSS for layout, typography, and responsive design.</li>
  <li>Git and GitHub for version control and hosting.</li>
  <li>GitHub Pages for deployment.</li>
</ul>

All custom HTML and CSS were written by the developer.  
External resources are listed below.  

## External resources and attribution

<ul>
  <li>System fonts for typography.</li>
  <li>YouTube embed pattern for the live performance video.</li>
  <li>General layout inspiration from common band and event websites.</li>
  <li>Images used in this project were sourced from Pexels, which provides free to use photography suitable for fictional and creative projects.</li>
</ul>

Where specific code snippets were adapted from tutorials or documentation, a comment is placed directly above the relevant code in the source files, and the source is listed in this section.  

Example description  

Audio player markup was informed by guidance from MDN Web Docs.  

## Validation

### HTML validation

<ul>
  <li>All pages were tested using the official W3C validator.</li>
  <li>No errors remain in the final version.</li>
</ul>

### CSS validation

<ul>
  <li>All custom CSS was tested using the official Jigsaw validator.</li>
  <li>No errors remain in the final version.</li>
</ul>

### Accessibility checks

<ul>
  <li>All images include descriptive alternative text.</li>
  <li>Colour contrast meets accessibility guidelines.</li>
  <li>Headings follow a logical order.</li>
  <li>All interactive elements are reachable with keyboard navigation.</li>
  <li>No media plays automatically.</li>
</ul>

### Responsiveness checks

<ul>
  <li>Layout was tested on mobile, tablet, laptop, and desktop.</li>
  <li>Navigation remains clear at all screen sizes.</li>
  <li>Grid sections adjust correctly.</li>
  <li>No horizontal scrolling occurs except where acceptable for tables.</li>
</ul>

### Content checks

<ul>
  <li>No placeholder text remains.</li>
  <li>All external links open in new tabs.</li>
  <li>All internal links work correctly.</li>
  <li>No broken links remain in the final deployed version.</li>
</ul>

### Code quality checks

<ul>
  <li>Semantic HTML is used throughout.</li>
  <li>CSS is organised into clear sections with comments.</li>
  <li>File names use lower case with no spaces.</li>
  <li>No more than two consecutive blank lines appear in the code.</li>
  <li>All external code is clearly attributed.</li>
</ul>

## Screenshot mapping table

<table>
  <thead>
    <tr>
      <th>Screenshot</th>
      <th>Description</th>
      <th>User story supported</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Home page hero section</td>
      <td>Shows the band introduction and booking call to action.</td>
      <td>User stories 1 and 3.</td>
    </tr>
    <tr>
      <td>Home page media section</td>
      <td>Shows audio samples and video content.</td>
      <td>User story 2.</td>
    </tr>
    <tr>
      <td>About page band members section</td>
      <td>Shows profiles of each band member.</td>
      <td>User story 1.</td>
    </tr>
    <tr>
      <td>About page testimonials section</td>
      <td>Shows social proof for event organisers.</td>
      <td>User story 3.</td>
    </tr>
    <tr>
      <td>Shows page table</td>
      <td>Shows upcoming dates and ticket links.</td>
      <td>User story 3.</td>
    </tr>
    <tr>
      <td>Shows page booking section</td>
      <td>Shows pricing guidance and booking instructions.</td>
      <td>User story 3.</td>
    </tr>
    <tr>
      <td>Footer with social links</td>
      <td>Shows links to social platforms.</td>
      <td>User story 4.</td>
    </tr>
  </tbody>
</table>

Screenshots are stored in the assets folder of the project.  

## Testing summary

Testing covered functionality, usability, responsiveness, and accessibility.  
All essential features passed testing.  
Any issues found were corrected, and remaining minor issues are documented in the testing file named <code>testing.md</code>.  

## Version control

Version control was used throughout the project.  
Each feature was committed separately with descriptive messages that document the development process.  

Past tense commit messages used in the project included the following examples.  

<pre>
Created the initial project structure with folders for pages and assets
Added the base HTML layout for all pages with semantic structure
Added the global navigation and footer across all pages
Created the hero section and introduction content for the Home page
Added audio samples and the video embed to the Home page
Added the band story and member profiles to the About page
Added the testimonials section to the About page
Created the shows table and booking information on the Shows page
Added responsive grid layouts for media, members, and booking sections
Added full site styling including colours, typography, and spacing
Added responsive design rules with media queries
Added accessibility improvements including alternative text and descriptive link text
Added external link behaviour so all external links open in new tabs
Replaced all placeholder text with real content
Added comments to separate custom code from external references
Added the README with project overview and user stories
Added screenshots and mapped them to user stories
Added the testing document with full test coverage
Validated HTML and CSS and fixed all issues
Removed unused code and commented code before deployment
Deployed the final version to GitHub Pages
Completed the final review and confirmed that the deployed version matches the development version
</pre>

This commit history demonstrates a clear and transparent development life cycle.  

## Deployment

The final version of the site was deployed using GitHub Pages.  

Deployment steps  

<ol>
  <li>Pushed the main branch to GitHub.</li>
  <li>Enabled GitHub Pages in the repository settings.</li>
  <li>Selected the main branch as the source for GitHub Pages.</li>
  <li>Confirmed that the deployed version matched the development version.</li>
</ol>

## Future improvements

Possible future enhancements include the following ideas.  

<ul>
  <li>A dedicated gallery page with more photos and video content.</li>
  <li>A real mailing list service for the newsletter form.</li>
  <li>A contact form with client side validation.</li>
  <li>A theme toggle for user preference.</li>
</ul>

These improvements are outside the current project scope but would add further value in future iterations.  

