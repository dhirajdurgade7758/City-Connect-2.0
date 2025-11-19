<!-- # 🌍 CityConnect – AI-Powered Civic Engagement & EcoCoin Rewards

### 🏆 MIT IEE 24-Hour National Level Hackathon Project

CityConnect is an **AI-powered civic-tech + gamification platform** that empowers citizens to **report civic issues, complete eco-friendly tasks, and earn rewards**. The system integrates **AI verification, live location tracking, EcoCoin gamification, and departmental admin panels** to create a **smart city management ecosystem**.

---

## 🎯 Problem Statement

Citizens often face difficulties in reporting civic issues, and governments struggle with verification, accountability, and public engagement. Additionally, there is a lack of motivation for citizens to actively participate in eco-friendly initiatives.

**CityConnect solves this by:**

* Using **AI to verify issues & eco tasks**.
* Providing **gamified incentives (EcoCoins, badges, leaderboard)**.
* Building a **transparent reward system** where users can redeem offers.
* Giving **departments real-time dashboards** to track and resolve issues.

---

## 🚀 Features

### 👤 User Features

* **Profile Dashboard**: Track reports, tasks, EcoCoins, badges, and redemptions.
* **Issue Reporting Feed**:

  * Submit issues with **image, description, live location**.
  * **AI verification** ensures authenticity.
  * Like ❤️, Comment 💬, Save 📌, Share 🔗.
* **Eco Tasks**:

  * Complete eco-friendly tasks (waste management, plantation, etc.).
  * **AI validates** task submissions.
  * EcoCoins awarded automatically.
* **Gamification**:

  * Earn **EcoCoins** via issues, tasks, likes, and comments.
  * Unlock **badges** for milestones (First Post, 100 EcoCoins, etc.).
  * Compete on the **Leaderboard**.
* **EcoCoin Store**:

  * 4 categories: 🛍 Shop Offers, 🎁 Donor Gifts, 🎟 Event Tickets, 🌱 Eco Rewards.
  * Redeem offers → Generate **voucher PDF** → Claim at physical location.
* **Saved Posts**: Save/unsave posts with HTMX-powered UI.

---

### 🏛 Department Admin Panels

Departments manage issues in their category:

* **Electricity Department**
* **Waste Management Department**
* **Water Supply Department**
* **Public Works Department**

Each panel allows:

* Viewing issues assigned to department.
* Seeing **live location maps**.
* Updating issue status (Pending → In Progress → Resolved).
* Monitoring issue resolution history.

---

### 🎮 Gamification System

* **EcoCoins**:

  * Earned via tasks, issue reporting, likes, comments.
  * Spent in the EcoCoin Store.
* **Badges**:

  * 🐣 First Post
  * 🌱 Green Starter (50 EcoCoins)
  * 🌿 Eco Warrior (100 EcoCoins)
  * 🌳 Eco Champion (200 EcoCoins)
  * 🪐 Planet Protector (500 EcoCoins)
* **Leaderboard**:

  * Shows top contributors by EcoCoins.

---

### 🎁 EcoCoin Store

* **Categories**:

  * 🛍 Shop Offers – Discounts from local businesses.
  * 🎁 Donor Gifts – Items donated by citizens.
  * 🎟 Event Tickets – Concerts, workshops, city events.
  * 🌱 Eco Rewards – Plants, bottles, eco-bags.
* **Redemption Flow**:

  1. User redeems an offer.
  2. Coins deducted & stock reduced.
  3. Unique **voucher code** generated.
  4. User downloads/prints PDF receipt.
  5. Claim at physical store/location.

---

## ⚙️ Tech Stack

### Backend

* **Django 5.x** (Python)
* **PostgreSQL / SQLite**
* **OpenAI API** – Image & text verification
* **HTMX** – Interactive frontend updates

### Frontend

* **Django Templates**
* **Bootstrap 5**
* **Bootstrap Icons / FontAwesome**
* **JS + AJAX + HTMX**

### Other Integrations

* PDF Voucher Generation
* Live Location Fetch
* AI-based Coin Allocation

---

## 📂 Project Structure

```
cityconnect/
│── cityconnect/         # Main project settings
│── core/                # User profiles, dashboard, feed, auth
│── issues/              # Issue reporting & AI verification & Civic task submission 
│── store/               # EcoCoin store, redemptions
│── admin_panel/         # Department dashboards
│── templates/           # HTML templates
│── static/              # CSS, JS, assets
```

---

## 📊 System Workflow

1. **User Action** → Reports issue / Completes task.
2. **AI Verification** → Matches image + description + department.
3. **EcoCoins Awarded** → Based on authenticity & engagement.
4. **Department Panel** → Sees issue, updates status.
5. **Store Redemption** → User redeems offer, receives voucher.
6. **Physical Claim** → User shows voucher at store to get reward.

---

## 🎉 Impact

* ✅ Citizens empowered to report and act.
* ✅ AI ensures fairness & reduces fake reports.
* ✅ Gamification motivates civic participation.
* ✅ Departments get real-time actionable insights.
* ✅ Local businesses & donors engage with community.

---

## 🔮 Future Enhancements

* Mobile App (Flutter/React Native)
* Push Notifications (task verified, badge unlocked)
* AI Fake Report Detection (more advanced)
* Shopkeeper/Donor Self-Service Panel
* City Analytics Dashboard

---

## 👨‍💻 Team & Credits

Developed as part of **MIT IEE 24-Hour National Level Hackathon**.

**Team Goal**: To create a **Smart City + AI-powered Gamification Platform** that makes civic engagement **transparent, rewarding, and impactful**.

---

## 🏆 Conclusion

CityConnect is more than just a hackathon project – it’s a **scalable smart city solution** that bridges the gap between **citizens, government, and local businesses**, using the power of **AI + gamification** to make cities cleaner, greener, and more efficient. -->



# 🌍 CityConnect – AI + Blockchain Powered Civic Engagement & Reward Ecosystem

### 🏆 MIT IEE 24-Hour National Level Hackathon Project

A **smart-city civic engagement platform** that combines **AI verification**, **gamification**, and **blockchain-based reward management** to empower citizens, improve civic issue resolution, and create a transparent reward system for eco-friendly participation.

---

# 🎯 Problem Statement

Citizens struggle with:

* Reporting civic issues effectively
* Lack of transparency in issue resolution
* Poor motivation for eco-friendly tasks
* No clear accountability between departments and citizen reports

Governments struggle with:

* Authentication of issues
* Inter-department coordination
* Engagement & reward tracking
* Scalable, tamper-proof, auditable reward distribution

---

# 💡 CityConnect – The Solution

CityConnect provides:

* **AI-powered civic issue verification**
* **Real-time department dashboards**
* **Gamified EcoCoin reward system**
* **Blockchain-based reward & store item management**
* **Map dashboards with live issue markers**
* **Eco-friendly task validation**
* **Voucher-based EcoCoin store**

---

# 🚀 Features

## 👤 User Features

### 📌 Issue Reporting Feed

* Upload image, description, and **auto-fetched live location**
* AI checks **authenticity**, **department mapping**, and **duplicate issues**
* Feed Page with (Like ❤️, Comment 💬, Save 📌, Share 🔗) features
* Earn **EcoCoins** for valid contributions

### 🌱 Eco-Friendly Tasks

* Complete validated eco activities (planting, waste management, etc.)
* OpenAI verifies image + description
* Auto-awarded coins upon approval

### 🏆 Gamification System

* EcoCoins from reports, tasks, likes, comments
* Badges:

  * 🐣 First Post
  * 🌱 Green Starter (50 coins)
  * 🌿 Eco Warrior (100 coins)
  * 🌳 Eco Champion (200 coins)
  * 🪐 Planet Protector (500 coins)
* Global leaderboard 🔥

### 🎁 EcoCoin Store

* Categories:

  * 🛍 Shop Offers
  * 🎁 Donor Gifts
  * 🎟 Event Tickets
  * 🌱 Eco Rewards
* Redemption Flow:

  1. User redeems offer
  2. Coins deducted
  3. Blockchain updates balance
  4. Voucher PDF generated
  5. Claim at physical location

---

# 🏛 Department Admin Panels (Role-Based Access)

Every admin is assigned a **department**, and can only view/manage issues belonging to it.

### 🔐 Admin Login

* Admin login restricted to users with:

  * `role = admin`
  * `department` assigned
* Non-admin users blocked automatically

### 📊 Department Dashboard

Each department receives:

* **Status KPIs**

  * Pending
  * In Progress
  * Resolved
  * Total

* **Monthly Analytics Chart (6-month time series)**

  * Powered by `TruncMonth()`
  * Visualized via Chart.js

* **Issue Table**

  * Filters
  * Sorting
  * Quick actions

* **Department-specific access protection**

  * Admin of Water Department cannot view Electricity Department issues

### 🗺 Interactive Map Dashboard

Admins get a map of all issues with:

* Google Maps markers
* Image preview
* Location name
* Status
* View issue button
* Resolve issue link
* Department-wise color-coded markers

---

# ⚙️ Admin Functionalities (Newly Added)

## ✔️ 1. Issue Resolution Panel

Admins can:

* Open issue
* Mark In Progress / Resolved
* Upload resolution proof
* Save resolution date & resolver

### 🪙 Blockchain-Integrated EcoCoin Rewarding

When admin resolves an issue:

1. Reward payload sent to Node server:

   ```json
   {
     "userId": "<username>",
     "amount": 50,
     "reason": "For reporting and resolving issue ID: <id>"
   }
   ```
2. Blockchain updates coin balance
3. Django syncs the updated balance from blockchain
4. Success or failure messages shown

⚠️ Network or blockchain failure shows a **warning** but still saves admin updates.

---

## ✔️ 2. Store Offer Management (Blockchain Synced)

### ➕ Create Store Offer

Admins can add:

* Offer Name
* Category
* Coins Required
* Stock
* Image

After saving:

* Offer is **synced with blockchain**
* Blockchain item `id` is saved inside Django model
* If blockchain sync fails, admin is notified

### 📄 Offer List Page

Admins can view all created offers.

---

## ✔️ 3. Global Issue List (Super Admin)

Super admins (`is_staff`/`is_superuser`) get:

* Global issue list
* Filter by: Pending / In Progress / Resolved

---

# 🔗 Blockchain Integration (Node.js Backend)

Used for:

* EcoCoin awarding
* Store item management

Integration includes:

* Error handling
* Logging
* Balance synchronization
* Unique item ID storage

---

# 📂 Project Structure

```
cityconnect/
│── cityconnect/              # Project config
│── core/                     # User profiles, auth, dashboard
│── issues/                   # Issue reporting, AI verification
│── store/                    # EcoCoin store & vouchers
│── admin_panel/              # Department admin dashboards
│── templates/                # HTML templates
│── static/                   # CSS, JS, Images
```

---

# 🧠 Tech Stack

### Backend:

* Django 5.x
* PostgreSQL / SQLite
* OpenAI API (AI validation)
* Node.js Blockchain service
* Google Maps Platform

### Frontend:

* Django Templates
* Bootstrap 5
* HTMX
* JS + AJAX

---

# 📊 System Workflow

1. User reports issue
2. AI verifies
3. Department dashboard receives issue
4. Admin resolves it
5. Blockchain rewards user with EcoCoins
6. User redeems store item
7. Voucher PDF generated
8. Physical store claim

---

# 🎯 Impact

* Reduces fake reports using AI
* Transparent governance using blockchain
* Gamifies civic participation
* Boosts local business engagement
* Department efficiency improved

---

# 🔮 Future Enhancements

* Flutter / React Native mobile app
* Shopkeeper self-service panel
* Advanced AI duplicate detection
* Notification system
* City insights analytics dashboard

---

# 🏆 Conclusion

CityConnect showcases how **AI + Blockchain + Gamification** can create a **smart city ecosystem** where:

* Citizens feel empowered
* Departments work efficiently
* Rewards remain transparent
* Eco-friendly participation grows

**A complete, scalable, production-ready civic engagement platform born from a 24-hour hackathon.**
