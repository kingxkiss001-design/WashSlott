# WashSlot — low-fidelity wireframe

```text
┌──────────────────────────────────────────────────────────────────────────────┐
│ [W] WashSlot                         Shared laundry, made simpler.  Student │
│                                                                      Housing │
├──────────────────────────────────────────────────────────────────────────────┤
│ LAUNDRY ROOM · DEMO SCHEDULE                             [Monday, date]      │
│ Get laundry done. Skip the guesswork.                                       │
│ Check sample availability before heading downstairs.                       │
│                                                                              │
│ ┌───────────────────────────────────────────────┐ ┌───────────────────────┐ │
│ │ Choose a machine                              │ │ Booking details       │ │
│ │ (●) Washer 1       ( ) Washer 2    ( ) Dryer 1│ │ Your selection stays  │ │
│ │                                               │ │ visible while filling│ │
│ │ Upcoming availability            Date [date] │ │ [DEMO ONLY notice]    │ │
│ │ [Available] [Booked] [Next available]        │ │ Machine  Washer 1     │ │
│ │                                               │ │ Date     selected day│ │
│ │ [14:00–15:00]             [Next available]    │ │ Time     selected slot│ │
│ │ [15:00–16:00]             [Booked]            │ │                       │ │
│ │ [16:00–17:00]             [Available]         │ │ Your name             │ │
│ │ [18:00–19:00]             [Available]         │ │ [___________________]│ │
│ │                                               │ │ Room / apartment no.  │ │
│ │ > Show earlier slots (n)                      │ │ [___________________]│ │
│ │                                               │ │ [Confirm booking]    │ │
│ └───────────────────────────────────────────────┘ └───────────────────────┘ │
│                                                                              │
│ Mobile flow: header → welcome/date → machine cards → schedule → booking form│
│                                                                              │
│ Submit flow: required-field checks → processing feedback → demo confirmation│
│              (no shared reservation or saved booking)                       │
└──────────────────────────────────────────────────────────────────────────────┘
```

## Main user flow

1. Check the current date and select a machine.
2. Review that machine's upcoming sample slots; past slots are hidden in a collapsed section.
3. Select an available slot. Booked slots cannot be selected.
4. Confirm the machine, date, and time in the booking summary.
5. Enter a name and room number, then submit to see processing and demonstration-only confirmation feedback.
