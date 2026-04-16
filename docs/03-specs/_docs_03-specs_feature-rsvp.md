# Feature: RSVP & Guest Access

## Summary

Guests access an event via a shared event link, locate their party via name lookup, and submit RSVP responses for themselves and their group.

---

## Flow

1. Guest opens event link
2. Guest enters name
3. System returns matching party
4. Guest selects their party
5. Session is tied to that party
6. Guest views event details
7. Guest submits RSVP
8. System saves responses

---

## Acceptance Criteria

- Guest can access event without account
- Guest can find party via name search
- Guest can view event details before RSVP
- Guest can RSVP per guest per event
- Guest can edit RSVP
- Host can see updated RSVP data

---

## Edge Cases

- Wrong party selected -> user can go back
- Duplicate names -> multiple options shown
- Invalid name -> no results
- Partial RSVP allowed
- Multiple users accessing same party simultaneously

---

## RSVP Rules

- Party-level submission
- Guest-level tracking
- Latest submission wins

---

## Plus-One

- Only if enabled
- Must include name
- Does not block other RSVPs

---

## Access Model

- Event-level link (shared)
- Name-based lookup
- Session created after party selection

---

## Security (MVP)

- No authentication required
- Rate limit search attempts
- Minimal guest data exposure

---

## Future Enhancements

- Token-based invite links
- RSVP deadlines
- Guest authentication
