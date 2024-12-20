# Uncommon HTML Bug: Contenteditable on Label Element

This repository demonstrates an uncommon HTML bug involving the use of the `contenteditable` attribute on a `<label>` element.  Using `contenteditable="true"` on a label can lead to unpredictable and often undesirable behavior, especially concerning interactions with associated form elements.

The `bug.html` file showcases the issue. The `solution.html` offers a corrected approach, adhering to best practices.

## Problem

The `contenteditable` attribute, while useful for making elements directly editable by the user, is generally not intended for use with form labels.  This is because labels are primarily designed to associate text with input elements, not for direct content editing that could potentially interfere with form submission and validation.