# Tickets

TICKET-1: Create `README.md` and `.gitignore` (ignore .DS_Store, node_modules/). Create the develop branch from main.

TICKET-2: Create index.html with an `<h1>` welcome heading and a navigation bar containing a Home link. Done when: the page opens and shows the heading and navigation.

TICKET-3: Create `css/style.css` with a base font and nav spacing, and link it in `index.html`. Needs TICKET-2 because it edits index.html.

TICKET-4: Create `contact.html` (heading, nav, contact email) that uses the shared stylesheet. Add a Contact link to the homepage navigation. Branch from develop after TICKET-3 is merged, so the stylesheet exists and the nav edits don't conflict. (release 1.0.0)

TICKET-5 – Wrong contact email (hotfix) Release 1.0.0 shows a wrong emailadress. Change it. Branch from main, fix it, merge into main (tag v1.0.1), then back into develop.
