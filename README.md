# Session Insight static site

This folder is a static browser-delivered copy of the published Replit app.
It removes the Replit badge script and uses relative asset paths so it can be hosted from GitHub Pages.

Data is stored locally in each user's browser with localStorage keys such as `tutor_sessions`,
`tutor_active_session`, `tutor_scheduled_meetings`, and `session-lens-theme`.
There is no backend included.

For GitHub Pages, upload these files to a repository and enable Pages from the branch/folder that contains `index.html`.
