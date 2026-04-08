\# Business Rules

\#\# Party & Guests  
\- Guests belong to a Party  
\- A Party can contain multiple Guests  
\- Guests act independently but are grouped logically

\---

\#\# Invitations  
\- Invitations are created per Party  
\- Each Party accesses the system via event link \+ name lookup

\---

\#\# RSVP

\#\#\# Structure  
\- RSVP is submitted at Party level  
\- Stored per Guest per Event

\---

\#\#\# Rules  
\- Guests can RSVP only for events they are invited to  
\- Each Guest-Event pair has one status:  
  \- attending  
  \- declined

\---

\#\#\# Editing  
\- Guests can resubmit RSVP  
\- Latest submission overwrites previous

\---

\#\#\# Partial RSVP  
\- Some guests in a party can RSVP while others do not

\---

\#\# Plus-One  
\- Enabled per Party by host  
\- Must include name when added  
\- Becomes a Guest record

\---

\#\# Visibility  
\- Guests can view:  
  \- event details  
  \- their party members  
  \- other attending guests (first name only)

\---

\#\# Host Permissions  
\- Host can override RSVP responses  
