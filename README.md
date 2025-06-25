## 💡 Project: **Coding Social**

### 🎯 Goal

Build a web app where users can submit their **name, email, GitHub, LeetCode, and Codeforces usernames** using a form. All entries will be stored in a database (using a Backend-as-a-Service like Firebase or Supabase). The homepage should display all submitted profiles and allow visiting their coding profiles directly.

---

## 🧩 Features Overview

### 1. **Form Page**

* A form with the following fields:

  * Name (text)
  * Email (email)
  * GitHub username
  * LeetCode username
  * Codeforces username
* On submission, the data should be stored in a cloud database.

### 2. **Home Page**

* Fetch and display all submitted users.
* Each user card should show:

  * Name
  * Email
  * Clickable links to:

    * `https://github.com/{username}`
    * `https://leetcode.com/u/{username}`
    * `https://codeforces.com/profile/{username}`

---

## 🔧 Tech Guidelines

* **Frontend**:

  * Use **React** (preferred) or another frontend library of your choice.
  * Use Tailwind CSS or ShadCN for styling (optional but suggested).
  * Make the design clean and responsive.

* **Backend / DB**:

  * No custom backend needed.
  * Use a **BaaS (Backend as a Service)**:

    * Recommended: **Supabase**, **Firebase**, or **Appwrite**
    * Must allow:

      * Storing user submissions
      * Fetching the list of users for the homepage

* **Git & GitHub**:

  * Use git for version control.
  * Push code regularly to GitHub.
  * Share your **GitHub repo link** and **deployed site**.

---

### Example UX Flow:

1. User opens the form page → submits their details.
2. Data gets saved in Supabase/Firebase.
3. On the homepage:

   * All users are listed with links like:

     * 🔗 github.com/username
     * 🔗 leetcode.com/u/username
     * 🔗 codeforces.com/profile/username

---

## ✅ Minimum Requirements

* [ ] Form page working
* [ ] Data saved to a real-time database
* [ ] Homepage shows cards of all users
* [ ] All profile links should open in a new tab
* [ ] Good use of Git and GitHub
* [ ] Deploy the app (e.g. Vercel/Netlify)

---

## 🌐 Bonus (Optional)

* Use icons like GitHub/LeetCode/Codeforces
* Add search or filter by name
* Use form validation
* Show a toast or success message after submitting

---

## 📤 What to Submit

* ✅ GitHub repository link
* ✅ Deployed live link (Netlify/Vercel/Firebase Hosting)
