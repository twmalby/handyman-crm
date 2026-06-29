How it works:
This is a single HTML file that runs entirely in your browser — no server, no internet required.
Storage — two layers:

Browser memory (localStorage): every time you add or edit a contact, 
it's automatically saved inside the browser itself. This means 
if you close and reopen the file in the same browser, your data is still there without doing anything.
The .txt file (your real database): the JSON data lives in a plain text file on your computer. 
You control when to read/write it using two buttons — Load .txt (reads the file into the app) and Save .txt 
(writes the current contacts back to the file).

Typical workflow:

Open handyman-crm.html in Chrome/Edge
Click Load .txt → pick your crm_contacts.txt → contacts appear
Add/edit contacts as needed
Click Save .txt → overwrites the file with the latest data
Close browser — done

Sharing / multi-device:

Put crm_contacts.txt in a shared Dropbox folder. Anyone who has the HTML file 
and access to that Dropbox folder can load and save the same data. 
Just make sure two people aren't editing at the same time — there's no conflict resolution, last save wins.
⚠️ Important: the .txt file is the only thing that matters long-term. 
The browser cache can be cleared at any time and you'd lose unsaved changes. 
Make regular copies of crm_contacts.txt (weekly, or before any big editing session) 
— rename them with the date: crm_contacts_2026-06-29.txt.
