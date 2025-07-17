# 🛣️ SoloLedger Project Roadmap

**SoloLedger** is an open-source iOS app designed to help sole traders — especially fitness instructors and service professionals — track income, expenses, receipts, and payment status in a clean, cloud-native mobile interface.

The project is built using SwiftUI and Firebase and is inspired by real-world needs, starting with a fitness instructor's experience managing her sole trader business.

---

#### MVP Scope (v0.1.0)

The goal of the MVP is to deliver a functional, intuitive app that supports:

### Income Management
- [ ] Add income entry with:
  - Source (Company or Individual)
  - Amount, date, notes
- [ ] Manage income sources
  - Tag as Company or Individual
  - Store contact info and payment preference
- [ ] Mark income as paid/unpaid

### Expense Tracking
- [ ] Add expense entry with:
  - Category (fuel, equipment, etc.)
  - Optional: km travelled (for fuel tax)
  - Receipt photo upload
- [ ] Manage expense categories

### Invoicing & Payment Reminders
- [ ] For Companies: generate and send PDF invoices via email/text
- [ ] For Individuals: send payment reminders via email/text

### Reporting
- [ ] View dashboard with income/expenses/balance summary
- [ ] Export monthly PDF or CSV report

### Authentication & Cloud Sync
- [ ] Sign in with Apple or Email
- [ ] Securely store data with Firebase Auth + Firestore

### Payment Reconciliation (Basic)
- [ ] Upload or fetch bank transaction data
- [ ] Match deposits to income entries (manual with smart suggestions)

---

#### Near-Term Enhancements (v0.2.x)

- [ ] Offline-first support with sync
- [ ] Recurring income/expense entries
- [ ] Auto-categorize frequent entries
- [ ] Multi-currency support
- [ ] Invoice status tracking

---

##### Stretch Goals (v1.0 and Beyond)

- [ ] Tax summary and quarterly estimate report
- [ ] AI-based receipt parsing
- [ ] GPS-based km tracking for travel expenses
- [ ] Real-time Open Banking integration (Basiq or Plaid)
- [ ] Invite accountant or assistant for read-only access
- [ ] Push notifications (e.g., unpaid invoice reminders)

---

## Contribution Ideas

If you're a developer, designer, or user who wants to help:

- Review [issues labeled `help wanted`](https://github.com/vivek-OZ/sololedger/issues)
- Submit UI/UX suggestions
- Write test cases or improve Firebase rules
- Help build invoicing logic or dashboard visualizations

---

## Timeline

| Milestone | Target |
|-----------|--------|
| MVP Functional Prototype | August 2025 |
| First Public TestFlight | September 2025 |
| Community Feedback Phase | Q4 2025 |
| v1.0 Launch | Early 2026 |

---

_Last updated: July 2025_

