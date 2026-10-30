# Harbor Registry — live demo mock-up

Sample records only. This is not a real nonprofit’s data, and it is not a finished registry.

Open `index.html` in a browser. Nothing to install.

Click a preset, or any row. Related rows stay highlighted in all four tables.

Presets:

1. One client, two programs — Amira Khan
2. Whole shelter — Harbor Light Shelter
3. Waitlist — Jonah Ellis
4. Completed — Samir Haddad
5. Show the model — the four tables and their keys

Keys:

- `people.organization_id` = `organizations.id`
- `programs.organization_id` = `organizations.id`
- `enrollments.person_id` = `people.id`
- `enrollments.program_id` = `programs.id`
