- One file per note.
- File names are IDs + due date (if set).
- Folders for categories.
- Subfolder for done notes in each category.
- Subfolder for snoozed notes in each category.
- Always-on server should check each day for due dates and send mails.
- Searching:
  - `$ git log --all --name-only --pretty=format: | sort -u | grep <pattern>`
  - `$ git grep <pattern>`
- Now we only need a simple frontend:
  - Text field / add button
  - List of notes
  - Web and mobile native
