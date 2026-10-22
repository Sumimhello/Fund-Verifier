# Fund-Verifier

A lightweight, single-file interactive prototype for shared-fund withdrawal requests and dual co-owner approval.

## Run locally

Open `index.html` in a modern browser. No build tools or dependencies are required.

## Demo features

- Shared-account overview with clearly labelled fictional figures
- Withdrawal request form with amount validation
- Two independent demo approvals (Minh Le and Anh Pham)
- Request status, cancellation, and session-only activity log
- CSV export of the activity log
- Security notes outlining production requirements

## Important limitations

This is a frontend-only demonstration. It does **not** connect to a bank, transfer funds, access a camera, verify identity, perform biometric/liveness checks, or provide server-side authentication or authorization. All request and activity data exists only in the current page session. Do not use this prototype to make real financial or identity decisions.

Before production, implement authenticated accounts, server-side access controls, durable audit records, transaction-bound signed approvals, replay protection, and appropriately regulated payment-provider integration.
