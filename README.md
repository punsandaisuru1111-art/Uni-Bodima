# 🏡 SLIIT Stay — Student & Lecturer Boarding Platform near SLIIT Malabe

> **"Find Your Place. Feel at Home."**  
> *Peer-verified boarding discovery, key money escrow trust, and occupant verification for SLIIT Malabe Campus.*

---

## 🎯 1. Overview & Platform Purpose

**SLIIT Stay** is a peer-powered accommodation platform built specifically for the **SLIIT Malabe Campus** community (New Kandy Road, Malabe, Sri Lanka).

It solves the major pain points faced by SLIIT undergraduates and academic staff:
1. **Unverified & Misleading Listings**: Over-promising boarding places that lack proper study environments or safe surroundings.
2. **Key Money Risk & Broker Exploitation**: Landlords and middlemen demanding large cash advances without transparent guarantees.
3. **Privacy-Safe Peer Verification**: Needing to verify boarding conditions with actual current residents without compromising their personal contact information.

---

## 👥 2. User Roles & Dedicated Workflows

| User Role | Demo Persona | Credentials / Access | Key Capabilities |
| :--- | :--- | :--- | :--- |
| **🎓 SLIIT Student** | *Kasun Perera* | `kasun.p@my.sliit.lk` (`IT21048820`) | Search boardings, filter by walking distance to SLIIT, verify with 2 current residents via WhatsApp/Call, reserve & submit key money slips, leave 4-category verified reviews after completed stays. |
| **👨‍🏫 SLIIT Lecturer / Staff** | *Dr. Samantha Silva* | `samantha.s@sliit.lk` (`LEC-COMP-042`) | Dedicated "Lecturers Only" & quiet annex filter, study/work amenities verification, official staff email verification badge. |
| **🔍 SLIIT Scout / Listing Creator** | *Dinuka Jayasinghe* | `dinuka.j@my.sliit.lk` (`IT2022CS1042`) | Create listings with full 8-step wizard (rules, facilities, 2 occupant references, secure private creator bank details), track 10% key money commissions, manage scout wallet. |
| **🏡 Boarding Owner** | *Mrs. P. Bandara* | Trusted Landlord (Malabe) | Manage vacancies, view confirmed reservations, track 90% key money owner payouts directly to their bank account. |
| **🛡️ Platform Operations / Admin** | *SLIIT Stay Ops* | Platform Administrator | Verify key money deposit slips, inspect confidential creator & owner bank details, approve/reject payments with audit notes, release payouts. |

---

## 🚀 3. Upgraded Features Implemented

### 1. 🎓 University Email & Role Verification
- **Dual Email Enforcement**:
  - `@my.sliit.lk` for SLIIT Students.
  - `@sliit.lk` for SLIIT Lecturers and Academic Staff.
- Verified SLIIT badges displayed across user cards, reviews, and occupant contacts.
- Only verified SLIIT users can view occupant contact details, reserve rooms, submit key money slips, or post reviews.

### 2. 📝 Upgraded Boarding Listing Creation Wizard
- **Basic Information**: Title, Accommodation Type (*Single Room, Shared Room, Annex, Hostel*), Gender Preference (*Boys, Girls, Lecturers Only, Mixed*), Monthly Rent (LKR), Key Money Amount (LKR), Available Vacancies, Distance from SLIIT Malabe (meters / km / walking minutes).
- **Facilities Checklist**: Attached Bathroom, Wi-Fi, Air Conditioning, Cooking Allowed, Parking, Study Table, Washing Machine, Water Included, Electricity Included, Furnished, Kitchen.
- **Rules & Regulations**: Curfew time, visitor policy, cooking guidelines, utility bill splitting notes.
- **Photo Gallery**: Cover photo selector and gallery management.

### 3. 👥 Two Current Occupant Contacts & Privacy Protection
- Every listing captures two currently residing SLIIT students/occupants:
  - Full Name, SLIIT Student ID, Faculty/Department, Academic Batch, Phone Number.
  - Mandatory consent confirmation checkbox.
- **Strict Privacy Masking**:
  - Unverified or unauthenticated users see phone numbers masked (`077 ••• ••••`) with a locked badge.
  - Verified SLIIT students and lecturers see unmasked phone numbers with direct **WhatsApp Chat** and **Telephone Call** action buttons.

### 4. 🔒 Confidential Private Bank Details Management
- During listing creation, two distinct bank accounts are securely collected:
  - **Listing Creator Bank Details**: Bank Name, Branch, Account Holder Name, Account Number.
  - **Boarding Owner Bank Details**: Bank Name, Branch, Account Holder Name, Account Number.
- **Security Guarantee**:
  - Excluded from public listing view objects.
  - Accessible strictly to Platform Administrators inside the payment inspection modal.
  - Account numbers are masked by default (`•••• •••• •••• 4421`) with an admin toggle to reveal for payment processing.

### 5. 💳 Key Money Escrow & Payment Submission System
- **Checkout Modal**:
  - Displays official platform escrow bank account (Bank of Ceylon, SLIIT Malabe Campus Branch, A/C #0084 2010 9942).
  - Clear 10% Commission / 90% Owner split breakdown.
  - Drag-and-drop or file upload for deposit slip / online transfer screenshot.
  - Instant payment tracking (`pending_verification` ➔ `approved` ➔ `paid_out`).

### 6. 🛡️ Admin Key Money Verification & Payout Dashboard
- **Key Money Payments Verification Table**: Filter by Pending, Approved, Rejected.
- **Payment Inspection Modal**:
  - Zoomable deposit slip preview.
  - Boarding & payer verification summary.
  - Securely decrypted Private Bank Details (Creator & Owner accounts).
  - Approve or Reject with mandatory audit reason.
  - Payout processing triggers.

### 7. 💰 Automatic Commission Calculation & Payouts
- Default **10% Commission** calculated automatically:
  - **100% of the commission** is credited to the verified Listing Creator / Scout.
  - **90% of the key money** is scheduled for payout to the Boarding Owner.
- Payout records generated for both creator and owner with transaction receipts.

### 8. 💼 Scout Wallet Upgrade
- Real-time earnings breakdown:
  - Key Money Commission Earned.
  - Pending Verification Commission.
  - Paid-Out Commission.
  - Total Lifetime Earnings.
- Detailed Key Money Commission Ledger table with payment reference IDs and timestamps.

### 9. ⭐ Verified Past Resident Reviews (4 Multi-Category Ratings)
- Reviews can only be submitted by students who have a verified completed stay record.
- Rated across 4 distinct categories:
  1. **Cleanliness** (1 - 5 stars)
  2. **Landlord Behaviour** (1 - 5 stars)
  3. **Safety & Security** (1 - 5 stars)
  4. **Value for Money** (1 - 5 stars)
- Features the **Verified Past Resident** green trust badge.

### 10. 🗺️ Interactive SLIIT Malabe Campus Map
- Centered on SLIIT Malabe Campus (`6.9147° N, 79.9733° E`).
- Color-coded pins for room availability (Green = Available, Red = Full, Amber = Few Left).
- Walking distance, meters from campus, and key money badges.

### 11. 🏡 Boarding Owner Dashboard
- "Key Money & Payouts" tracking section.
- Real-time vacancy management (1-click increment/decrement).
- Confirmed reservation list.

### 12. ⚡ 1-Click Interactive Demo Workflow
- Bottom quick-switcher bar allows testing all roles without re-logging in.
- **"⚡ Key Money Demo"** button triggers an end-to-end checkout demo with 1 click.

---

## 🏃 4. How to Run

### Method 1: One-Click Launch (Recommended)
Double-click `start-app.bat` in the project root folder:
```cmd
start-app.bat
```
This opens `index.html` directly in your default browser.

### Method 2: Zero-Dependency Local HTTP Server
If you prefer running over `http://localhost:3000`:
1. Right-click `server.ps1` and choose **Run with PowerShell**, or in terminal:
```powershell
powershell -ExecutionPolicy Bypass -File .\server.ps1
```
2. Navigate to: `http://localhost:3000`

---

## 🛠️ 5. Technology Stack & Architecture

- **Engine**: Zero-dependency, offline-ready React 18 compatible Virtual DOM engine (`js/react-lite.js`).
- **Styles**: Custom responsive CSS utility layer (`css/custom.css`) + progressive Tailwind CSS enhancement.
- **Icons**: Handcrafted lightweight SVG vectors (`js/icons.js`).
- **Database & State**: Observable reactive state engine with persistent `localStorage` synchronization (`js/store.js`).
- **Zero External Dependencies**: Operates 100% offline without requiring Node.js, npm, or Python.
