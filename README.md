# Ironwood Community Workshop – Prototype

Functional prototype for the CNIT 280 term project (Group 1, Ironwood Community Workshop case).

**Open the prototype:** [`index.html`](index.html). With GitHub Pages turned on, it is served at https://evannechiang.github.io/ironwood-workshop/

The prototype runs entirely in the browser using sample data. Nothing is saved: refreshing the page resets it.

## Test accounts

| Role | Username | Password |
|---|---|---|
| Member | `robert.byrne` | `member123` |
| Member (under 18) | `avery.lin` | `youth555` |
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
| 2 | Complete a guest liability waiver | UC 007 | Guest (no login: "Complete Liability Waiver" on the sign-in page); Monitor checks "Waiver Status" |
| 2 | Record a guest or day-pass visit | UC 008 | Monitor ("Record Visit"); Monitor and Shop Manager view "Visit Records" |

## Sample visitors (for UC 007 and UC 008)

| Visitor | Type | What it shows |
|---|---|---|
| Dana Kim | Day-Pass User | Everything complete, check-in works |
| Sam Patel | Guest | Valid waiver, check-in works |
| Jamie Fox | Guest | No waiver on file, check-in blocked |
| Chris Owens | Guest | Expired waiver, check-in blocked |
| Leo Martinez | Day-Pass User | Day-pass not paid, check-in blocked |
| Morgan Lee | Day-Pass User | Already checked in today, no duplicate |

The waiver and check-in screens have a "Prototype test only" checkbox to simulate a save error.

## Files

- `index.html`: current prototype (Sprint 1 + Sprint 2)
- `Ironwood Community Workshop – Sprint 1 Prototype.html`: Sprint 1 version, kept for reference
