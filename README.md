# Ironwood Community Workshop – Prototype

Functional prototype for the CNIT 280 term project (Group 1, Ironwood Community Workshop case).

**Open the prototype:** [`index.html`](index.html). With GitHub Pages turned on, it is served at https://evannechiang.github.io/ironwood-workshop/

The prototype runs entirely in the browser using sample data. Nothing is saved: refreshing the page resets it.

## Test accounts

| Role | Username | Password |
|---|---|---|
| Member | `robert.byrne` | `member123` |
| Member (under 18) | `avery.lin` | `youth555` |
| Staff Member | `alex.morgan` | `staff246` |
| Shop Manager | `marcus.ojeda` | `shop456` |
| Monitor | `kelsey.park` | `monitor789` |
| Class Coordinator | `priya.raghunathan` | `class321` |

## What each sprint covers

| Sprint | Requirement | Use case | Who uses it |
|---|---|---|---|
| 1 | Reserve a machine | UC 001 | Member |
| 1 | Manage machine certifications | UC 002 | Shop Manager (records), Monitor (views) |
| 2 | Register for class | UC 004 | Member |
| 2 | Create and manage classes | UC 005 | Class Coordinator |
| 3 | Complete a guest liability waiver | UC 007 | Guest (no login: "Complete Liability Waiver" on the sign-in page); Monitor checks "Waiver Status" |
| 3 | Record a guest or day-pass visit | UC 008 | Monitor ("Record Visit"); Monitor and Shop Manager view "Visit Records" |
| 4 | View overdue member accounts | UC 009 | Staff Member ("Member Accounts") |
| 4 | Record machine maintenance and repairs | UC 010 | Shop Manager ("Manage Maintenance") |
| 5 | Manage member records | UC 011 | Staff Member ("Manage Members" → "Register New Member"); Shop Manager and Monitor ("Member Lookup") |
| 5 | Validate machine certifications | UC 012 | Shop Manager ("Manage Certifications"); age and duplicate checks run when a machine is selected |

## Sample visitors (for UC 007 and UC 008)

| Visitor | Type | What it shows |
|---|---|---|
| Dana Kim | Day-Pass User | Everything complete, check-in works |
| Sam Patel | Guest | Valid waiver, check-in works |
| Jamie Fox | Guest | No waiver on file, check-in blocked |
| Chris Owens | Guest | Expired waiver, check-in blocked |
| Leo Martinez | Day-Pass User | Day-pass not paid, check-in blocked |
| Morgan Lee | Day-Pass User | Already checked in today, no duplicate |

## Sample members (for UC 011 and UC 012)

| Member | ID | Date of birth | Phone | Use it to show |
|---|---|---|---|---|
| Robert Byrne | M-1042 | 1988-03-14 | 317-555-0121 | Duplicate certification (already certified on CNC router, Laser 2, Table saw) |
| Jordan Fontaine | M-1107 | 1997-06-02 | 317-555-0134 | Duplicate member registration (same name and date of birth, or same phone) |
| Avery Lin | M-1188 | 2010-02-09 | 317-555-0156 | Under-18 metal-bay restriction (MIG welder, Metal lathe) |

## Sample member accounts (for UC 009)

| Member | Payment status |
|---|---|
| Robert Byrne, Avery Lin | Current |
| Jordan Fontaine, Tia Nwosu | Overdue |
| Miguel Reyes | Payment information incomplete |

The waiver, check-in, member accounts, maintenance, member registration and certification screens have "Prototype test only" checkboxes to simulate errors or empty results.

## Files

- `index.html`: current prototype (Sprints 1–5)
- `Ironwood Community Workshop – Sprint 1 Prototype.html`: Sprint 1 version, kept for reference
