# Workforges Backend Roadmap

The backend will provide REST APIs for all ERP modules.

---

## Phase 0 — Foundation (Current)
- [ ] PostgreSQL connection (pg module)
- [ ] Database migration structure
- [ ] Basic `/api/health` route
- [ ] `.env.example` for configuration

---

## Phase 1 — Authentication & Users
- [ ] Users table (id, name, email, role)
- [ ] Companies table (multi-tenant)
- [ ] JWT authentication
- [ ] Role-based endpoints

---

## Phase 2 — CRM + Sales
- [ ] Leads table
- [ ] Lead status update endpoint
- [ ] Quotations table
- [ ] Sales orders table

---

## Phase 3 — Inventory + Accounting
- [ ] Products table
- [ ] Stock in/out endpoints
- [ ] Invoices table
- [ ] Payment tracking

---

## Phase 4 — HRM & Advanced
- [ ] Employees table
- [ ] Attendance
- [ ] Leave requests
- [ ] Payroll

---

If you are ready to contribute:
→ Check the **Issues** tab and request assignment.
