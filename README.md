# Fyno - Fintech Bank Application

## 🤖 Introduction

**Fyno** is a full-stack banking app built with modern technologies. It connects multiple bank accounts via Plaid, tracks transactions in real-time, supports peer-to-peer transfers using Dwolla, and provides detailed financial insights – all in one unified dashboard.

## ⚙️ Tech Stack

- **Frontend**: Next.js, TypeScript, TailwindCSS, ShadCN
- **Backend**: Appwrite
- **Integrations**: Plaid, Dwolla
- **Form & Validation**: React Hook Form, Zod
- **Data Visualization**: Chart.js


## 🔋 Features

✅ **Authentication**: Secure server-side authentication with robust validation  
🏦 **Connect Banks**: Integrate and link multiple bank accounts via Plaid  
📊 **Dashboard Overview**: Real-time account balances, categorized expenses, and recent transactions  
🏦 **My Banks**: View all connected bank accounts and details  
📁 **Transaction History**: Paginated and filterable transaction list  
🔁 **Real-Time Updates**: Instant UI updates on changes  
💸 **Funds Transfer**: Send money to other users securely using Dwolla  
📱 **Fully Responsive**: Seamless experience across desktop, tablet, and mobile  

### 🛠️ Installation

Clone the repository:

```bash
git clone https://github.com/ranirp/fyno-fintech-bank-application.git
cd fyno-fintech-bank-application
```

Install dependencies:

```bash
npm install
```

### ⚙️ Environment Setup

Create a `.env` file in the root directory:

```env
# NEXT
NEXT_PUBLIC_SITE_URL=

# APPWRITE
NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
NEXT_PUBLIC_APPWRITE_PROJECT=
APPWRITE_DATABASE_ID=
APPWRITE_USER_COLLECTION_ID=
APPWRITE_BANK_COLLECTION_ID=
APPWRITE_TRANSACTION_COLLECTION_ID=
APPWRITE_SECRET=

# PLAID
PLAID_CLIENT_ID=
PLAID_SECRET=
PLAID_ENV=
PLAID_PRODUCTS=
PLAID_COUNTRY_CODES=

# DWOLLA
DWOLLA_KEY=
DWOLLA_SECRET=
DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
DWOLLA_ENV=sandbox
```

### 🚀 Run the App

```bash
npm run dev
```

Open `http://localhost:3000` in your browser.

## 📄 License

This project is licensed under the [MIT License](LICENSE).