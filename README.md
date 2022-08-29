# Auricle-Google-Sheets-Automization
Whenever a writer finds a DOI for a new medical article to write about they put it in the google sheet. This was inefficient because they would have to communicate with their editor manually that they added a DOI. If they forgot to, it would take many days for the editor to realize there was a new DOI. So, this program using Google App Scripts, senses when there has been an edit to a DOI and sends an email to the assigned editor. It also checks the database of already done DOI to make sure it hasn't been done already and if it has been done, the editor is notified it is a repeat.
