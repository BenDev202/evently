# evently
# 🎟️ EventHub — Event Registration and Digital Ticketing Platform

A secure, responsive web app where organizers publish events, attendees register and get QR-code digital tickets, and authorized staff verify tickets and check attendees in.

**Intango TSS · DSE — Digital Skills for Employability**
**Group 5 (Team Echo)** · team project

---

## Problem

Managing events with paper forms, spreadsheets, and chat apps leads to duplicate registrations, lost tickets, inaccurate attendance records, and slow check-in. EventHub centralizes registration, ticket generation, secure verification, and attendance reporting.

> MVP scope: free events only. No payment processing.

## User Roles

| Role | What they do |
|------|--------------|
| **Attendee** | Browse events, register, view/download tickets |
| **Organizer** | Create and publish events, view registrations, assign staff, export reports |
| **Check-In Staff** | Verify tickets and check in attendees for assigned events |
| **Admin** | Approve organizers, manage users and categories, review audit logs |

## Key Features

- Authentication with role-based access control
- Event creation, publishing, search and filtering
- Registration with server-enforced capacity and duplicate prevention
- Unique digital tickets with QR codes and PDF download
- QR scan or manual reference check-in (no double check-in)
- Role dashboards and attendance reports (CSV export)
- Audit logs for important admin actions

## Tech Stack

React · TypeScript · Tailwind CSS · Node.js · Express · MySQL · Prisma · Vitest/Supertest · GitHub Actions · Figma

## Repository Structure

```
eventhub/
├── frontend/   → React app (see frontend/README.md)
├── backend/    → Express API (see backend/README.md)
├── docs/       → SRS, ERD, API docs, test reports, designs
└── README.md
```

## Quick Start

```bash
git clone https://github.com/<org-or-username>/eventhub.git
cd eventhub
```

Then follow the setup guides:
1. [Backend setup](backend/README.md)
2. [Frontend setup](frontend/README.md)

## Documentation

- [SRS](docs/SRS.pdf)
- [ERD](docs/ERD.png)
- [API documentation](docs/API.md)
- [Test report](docs/TEST_REPORT.md)


## Links

- 🌐 Live app: `https://...`
- ⚙️ API: `https://...`
- 🎨 Figma: `https://www.figma.com/design/XrNw9EhvEFTfvStBbkQsiw/EventHub1?node-id=0-1&t=I7m7Mkgtioo8yHo9-1`

---
