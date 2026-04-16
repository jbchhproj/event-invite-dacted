# Domain Model

## Core Entities

### Event

- Represents a single scheduled event
- Example: Ceremony, Reception

---

### Party

- Group of guests invited together
- Primary unit of invitation

---

### Guest

- Individual person within a party

---

### Invitation

- Connects a party to events
- Entry point for guest access

---

### RSVP

- Represents responses for a party
- Contains guest-level responses

---

## Relationships

- Party -> has many Guests
- Party -> invited to many Events
- Invitation -> belongs to Party
- RSVP -> belongs to Party
- RSVP -> contains Guest responses per Event
