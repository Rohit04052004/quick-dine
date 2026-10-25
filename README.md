# QuickDine

A modern restaurant table booking and reservation platform. Built by **Rohit Chigatapu**.

**Live demo:** https://quick-dine-eta-nine.vercel.app

> Note: this repo is the frontend only. Booking, auth, and admin/owner flows call a separate backend API (via `VITE_API_URL`) that isn't included here, so those flows won't work against the live demo until a backend is deployed and wired up.

## ✨ Features

- **Discerning Curation**: Clean, premium, and responsive search & filter options to browse dining venues by location, cuisine, price range, and rating.
- **Seat Availability System**: Live check of table slots and seat capacity for a chosen reservation date.
- **Seamless Booking Flow**: Reservation request with occasion selection and special dining requests.
- **Role-Based Portals**:
  - **Diners**: Book tables, track active reservations, and cancel requests.
  - **Restaurant Owners**: Register a venue, manage profile information, and confirm/cancel incoming reservations.
  - **Administrators**: Approve new restaurant registrations and monitor system-wide metrics.

## 🛠️ Tech Stack

- **Framework**: React 19 (Vite)
- **Language**: TypeScript
- **Styling**: Tailwind CSS v4
- **Routing**: React Router v7
- **Icons**: Lucide React
- **Notifications**: React Hot Toast
- **Deployment**: Vercel

## 🚀 Getting Started

### Prerequisites

Ensure you have **Node.js** (v18 or higher) and **npm** installed.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Rohit04052004/quick-dine.git
   cd quick-dine
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory:
   ```env
   VITE_API_URL=http://localhost:5000/api
   ```

### Development Server

Run the development server locally:
```bash
npm run dev
```
Open `http://localhost:5173` in your browser.

### Building for Production

Compile typescript and build the production bundle:
```bash
npm run build
```

Preview the production build locally:
```bash
npm run preview
```

## 📄 License

Distributed under the MIT License. See [LICENSE.md](./LICENSE.md) for more details.

## Credits

Adapted from an open-source table booking tutorial project, maintained and extended here by Rohit Chigatapu.
