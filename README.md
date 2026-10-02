# PD Warriors Philippines — Get Together 2027 Fundraising E-Raffle

A forkable fundraising e-raffle website for Parkinson's Disease Warriors Philippines.

## Fundraising flow
- Open to supporters, friends, family, sponsors, and attendees
- Multiple tickets per buyer
- Unique ticket number for every raffle entry
- QR verification link per ticket
- Pending / Paid / Cancelled payment status
- Eligible / Winner / Not Selected draw status
- Admin ticket search and payment verification
- Paid + Eligible winner pool only
- CSV export and audit history

## Separate attendee raffle
The original attendee/check-in raffle was preserved as `event-raffle.html`.

## Important deployment note
The current GitHub Pages version is browser-local for testing and committee setup. Data is stored in localStorage on the device that created it. For real public sales across different phones/devices, connect the frontend to a shared database/backend such as Supabase or Firebase before accepting live purchases.

## Demo admin
PIN: `2027`

Before running a paid fundraising raffle, confirm the applicable Philippine permit, fundraising, tax, privacy, and raffle requirements for your organization.
