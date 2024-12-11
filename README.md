# :focus-visible Pseudo-class Issue

This repository demonstrates a problem with the CSS `:focus-visible` pseudo-class.  In certain scenarios, the expected visual styling changes upon focus are not applied.  This can lead to accessibility issues for users relying on keyboard navigation or assistive technologies.

The `bug.css` file contains the problematic CSS, and `bugSolution.css` offers a potential workaround or clarification.

## Steps to Reproduce

1. Open `bug.html` in a web browser.
2. Try to focus on the elements (buttons etc). Observe the lack of expected visual cues in some browsers/situations.

## Potential Solutions

See `bugSolution.css` for potential solutions, such as using JavaScript to detect focus and apply styles conditionally based on the focus-visible state or explore browser-specific workarounds.