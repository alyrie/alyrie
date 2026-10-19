# Field Sales Operations Platform

**Mobile-first CRM and field operations system for a regional service-business sales team**

I designed and built a custom field-sales application to replace a fragmented collection of manual processes with one practical system that reps can use from their phones throughout the day.

The application is intentionally workflow-first rather than CRM-first. Each major feature maps to a real task a field salesperson needs to complete quickly while moving between customers, agents, job sites, and the office.

## The problem

The existing workflow depended on separate tools and manual steps for customer records, contact lists, signed notices, document scans, job tracking, business cards, and follow-up. Important information lived in different places, and routine tasks required unnecessary handoffs.

The goal was to reduce that friction without creating a heavyweight system that reps would avoid using.

## What the system does

- **Digital business cards** — each rep has a public contact card and QR code that customers can scan and save.
- **Customer CRM** — track prospects, agencies, contact details, notes, and follow-up status.
- **Mobile document workflow** — complete a customer notice in the field, capture a finger signature and required photos, generate a combined PDF, and route it to the office in one action.
- **Shared contact directory** — keep frequently used insurance, trade, restoration, and office contacts in one common team list.
- **Sales and job tracking** — track assigned jobs, key dates, billed and collected amounts, compensation status, photos, and follow-up work.
- **Controlled access** — only approved users can create accounts, with role-aware separation of rep-specific information.

## My role

I handled the product definition, workflow architecture, mobile UX, data modeling, authentication approach, document-generation workflow, file handling, email routing, deployment, and ongoing iteration.

This is a working production system, not a design prototype.

## Technology

`Next.js` `TypeScript` `Supabase` `Vercel` `Resend` `PDF generation` `QR contact sharing` `Responsive web app`

## Product decisions

A few design choices were especially important:

- Keep the interface optimized for phone use and fast field actions.
- Organize the app around the work reps already do rather than forcing a generic CRM model.
- Separate shared team resources from rep-specific sales and customer data.
- Turn a multi-step document process into one guided flow.
- Keep future licensing in mind so additional users can be added as paid seats without redesigning the product.

## Outcome

The platform is currently being used in a limited real-world pilot with historical sales data already loaded into the system. It demonstrates how a narrow operational problem can be turned into a useful vertical software product by designing around the user's actual workday.

🔒 Production source code, customer data, private workflows, credentials, schemas, and infrastructure details are proprietary and are not publicly disclosed.
