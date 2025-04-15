# QA Test App

This is a mock feedback form used for senior QA interviews. It includes intentional bugs to assess a candidate’s exploratory testing, bug reporting, accessibility knowledge, and communication.

## Features

- Manual form submission
- CSV upload for bulk feedback
- CSV export of feedback entries

## Known Intentional Bugs

- Form accepts invalid email
- No required field validation
- No success message appears
- Title and heading have typos
- Inputs lack associated `<label for>` attributes
- Image lacks `alt` text
- Form data is not persisted
- Mobile layout breaks
- Focus outlines are removed
- Skip link is present but visually hidden improperly
- CSV import accepts malformed lines without UI feedback

## Deployment

Host with GitHub Pages or drag-and-drop to Netlify.
