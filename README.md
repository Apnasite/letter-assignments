# 📄 HTML & CSS Letter Design Assignment

## 🧭 Goal

Design a **visually appealing and professional letter template** using **HTML & CSS**.
You'll work on a **predefined HTML structure**, applying CSS creatively to style headers, content, and footers.

🔗 **Live Deployment Format:**
`https://services.apnasite.in/letter-assignments/[YourName_AssignmentNumber]/preview.html`

🔗 **GitHub Repository:**
👉 [https://github.com/Apnasite/letter-assignments](https://github.com/Apnasite/letter-assignments)

---

## 📁 Folder Structure

```
letter-assignments/
 ┣ 📂 designs/
 ┃ ┗ 📂 sample-code/
 ┃   ┣ 📂 css/
 ┃   ┃ ┗ style.css
 ┃   ┣ 📂 img/
 ┃   ┃ ┣ letter-logo.png
 ┃   ┃ ┗ org-logo.png
 ┃   ┣ 📂 fonts/
 ┃   ┣ 📜 index.html
 ┃   ┗ 📜 preview.html
 ┣ 📂 SubmittedAssignments/
 ┃ ┗ 📂 [YourName_AssignmentNumber]/
 ┣ 📜 Letter Assignment.docx
 ┗ 📜 User Assignment Mapping.xlsx
```

---

## 🧱 HTML Structure Guidelines

### ✅ You Can Modify: `preview.html`

```html
<div class="letter-background">
  <!-- ✅ Add or edit content/styling elements here -->
</div>
```

### ❌ Do NOT Modify:

```html
<div class="letter-content">
  <!-- ❌ Keep everything inside this div unchanged -->
</div>
```

### Add/Copy new background html block `index.html`:

```html
<div class="letter-background">
  <!-- ✅ Add or edit content/styling elements here -->
</div>
```

---

## 🎨 CSS Styling Guidelines

Use **advanced and creative CSS** properties to achieve a clean, professional letter format.

### 🎯 Goals per Section:

#### ✅ 1. Background Styling

* Use `background-color`, `linear-gradient`, or `image backgrounds` in `.letter-background`.

#### ✅ 2. Fonts

* Use **custom web fonts** (Google Fonts or fonts folder).
* Use properties like `font-family`, `font-size`, `font-weight`, `letter-spacing`, `line-height`, `text-align`.

#### ✅ 3. Layout & Dimensions

* Use **mm** for layout (widths, margins, paddings).
* Use **pt** for font size and borders.
* ❌ Do **not** use px, %, em, or rem.

#### ✅ 4. Header Styling

* Style the logo, organization name, letter reference, and date.
* Use `display`, `position`, `margin`, `padding`, `flex`, `text-transform`, `text-shadow`.

#### ✅ 5. Body Styling

* Structure: sender details, subject, salutation, message body, and signature.
* Maintain clear visual hierarchy using font weights and spacing.
* Use `border`, `box-shadow`, `border-radius`, `line-height`.

#### ✅ 6. Footer Styling

* Style contact details (phone, email, website, address).
* Use subtle variations in font size, color, or layout for emphasis.

---

## 🧪 CSS Property Checklist

Use as many of these properties as possible:

* **Typography:**
  `font-family`, `font-size`, `font-style`, `text-align`, `letter-spacing`, `word-spacing`, `line-height`

* **Color & Decoration:**
  `color`, `background-color`, `background-image`, `gradient`, `opacity`, `text-shadow`

* **Spacing & Sizing:**
  `margin`, `padding`, `width`, `height`, `border`, `border-radius`, `box-shadow`

* **Layout:**
  `display`, `flex`, `grid`, `position`, `float`, `z-index`, `gap`

* **Transformations:**
  `transform`, `rotate`, `scale`, `translate`, `transition`, `animation`

* **Print Optimization:**
  Use `@media print` and standard **A4 size** layout (297mm width)

---

## 🚀 Assignment Submission Process (with Git Commands)

### 🔁 1. **Fork the Repository**

Go to:
👉 [https://github.com/Apnasite/letter-assignments](https://github.com/Apnasite/letter-assignments)
Click the **Fork** button.

---

### 💻 2. **Clone Your Forked Repo**

```bash
git clone https://github.com/YOUR_USERNAME/letter-assignments.git
cd letter-assignments
```

---

### 📁 3. **Create Your Assignment Folder**

```bash
mkdir SubmittedAssignments/YourName_Assignment01
cp -r designs/sample-code/* SubmittedAssignments/YourName_Assignment01/
```

---

### 🛠️ 4. **Work on Your Design**

* Edit only `preview.html` and `css/style.css` inside your folder.
* Add new images, fonts if needed, in `img/` and `fonts/`.

---

### ✅ 5. **Commit Your Work**

```bash
git add .
git commit -m "Added Letter Design Assignment - YourName_Assignment01"
```

---

### ⬆️ 6. **Push to Your GitHub Repo**

```bash
git push origin main
```

---

### 🔃 7. **Raise a Pull Request**

* Go to your GitHub fork
* Click “Compare & Pull Request”
* Set base repo to `Apnasite/letter-assignments`
* Set head repo to `YourUsername/letter-assignments`
* Title: `"Submitting Letter Assignment - YourName_Assignment01"`
* Click **Create Pull Request**

---

## 🧾 Evaluation Criteria

| Evaluation Area                      | Weightage |
| ------------------------------------ | --------- |
| HTML Structure Adherence             | ✅         |
| Creative Use of CSS Properties       | ✅✅✅       |
| Professional Layout & Typography     | ✅✅        |
| Visual Hierarchy & Readability       | ✅✅        |
| Usage of mm and pt units             | ✅         |
| Logo/Image Placement                 | ✅         |
| Proper Folder & File Naming          | ✅         |
| Git Workflow (Commit, PR)            | ✅✅        |
| Bonus: Use of Transitions/Animations | ⭐ Bonus   |

---

## 🧠 Reminder

Your work reflects your skill and eye for detail.
Design something that feels **official, clean, and modern**—just like a letter from a reputed organization.

> ✍️ **Example Submission:**
> `https://services.apnasite.in/letter-assignments/Akshay_Kamble_01/preview.html`
