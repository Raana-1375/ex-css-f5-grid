# Front-end Grid Practice: Color Grid Layout

This project is a front-end development practice focused on mastering **CSS Grid** and responsive layout design (Mobile-First / Multi-device), developed within the Factoría F5 training program.

# Project Objective

The main objective of this project is to accurately reproduce a specific grid layout of color blocks, ensuring seamless adaptability across three distinct viewing environments: **Desktop, Tablet, and Phone**.

---

## Fulfilled Technical Requirements

* **Grid Layout:** Built with a modular structure using native CSS Grid properties.
* **Fully Responsive:** Implemented strategic breakpoints to guarantee visual fluidity on Phone, Tablet, and Desktop screens.
* **Google Fonts Integration:** Integrated external typography (`Bitcount Single`) using Google Fonts.
* **Live Breakpoint Control:** Included independent visual indicators (`screen-label`) that actively display which screen size is currently rendering during the testing phase.

---

##  Responsive Behavior (Layout Breakpoints)

The grid structure automatically reorganizes itself as follows to optimize the visual space on different devices:

### 🖥️ 1. Desktop View (≥ 900px)
* **Grid Template:** `repeat(6, 1fr)` (A base structure of 6 dynamic columns).
* The main `Colors` header element spans across the entire top width (`span 6`).
* The `green` block expands to take up a double-column width in its row (`span 3`).
* The active top indicator shows: **Desktop**.

### 📐 2. Tablet View (600px - 899px)
* **Grid Template:** `repeat(4, 1fr)` (Reduced to 4 dynamic columns).
* The `Colors` header element automatically scales down to fit the new layout width (`span 4`).
* The active top indicator shows: **Tablet**.

### 📱 3. Phone View (< 600px)
* **Grid Template:** `repeat(3, 1fr)` (A compact 3-column layout tailored for mobile devices).
* Elements are rearranged into more vertical, thumb-friendly blocks to enhance readability.
* The active top indicator shows: **Phone**.

---

## 🛠️ Tech Stack
* **Languages & Layout:** HTML5, Advanced CSS3 (CSS Grid & Flexbox)
* **Version Control:** Git & GitHub (Atomic Commits Workflow)