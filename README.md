# LLM Pages

## How to run
Clone the repository and serve it using a local server to view the site.

## Features
- Links to various files: short stories, ethical dilemmas, personal descriptions, SVG assets, restaurant recommendations, and financial predictions.

## Accessibility
- Uses semantic HTML5 elements, proper ARIA roles, and keyboard navigation.

## Design tokens (CSS variables/palette)
- Primary color: #333
- Secondary color: #f4f4f4

## API endpoints used
- None

## Attachments used
- uid.txt
- ashravan.txt
- dilemma.json
- about.md
- pelican.svg
- restaurant.json
- prediction.json

## Keyword coverage
| Keyword                   | Location                             |
|---------------------------|-------------------------------------|
| Each required file exists on GitHub | main.js (selfTest function)       |
| uid.txt matches the attached uid.txt | main.js (selfTest function)       |
| LICENSE contains the MIT License text | LICENSE file                      |
| index.html links to all required assets | index.html                       |
| ashravan.txt meets content requirements | index.html                       |
| dilemma.json matches the assigned scenario | index.html                     |
| about.md contains exactly three words | index.html                       |
| pelican.svg is valid SVG | index.html, linked in nav          |
| restaurant.json data is consistent | index.html                       |
| prediction.json contains a reasonable forecast | index.html                  |

## Changelog: Round 1
- Implemented all required files as per the brief.
- Set up an index.html linking to various resources.
- Added main.js for checks and basic application logic.
- Created a simple service worker for offline capabilities.