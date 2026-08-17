# 🎓 INKPUNK × Maheshwari Public School — Teacher's Day Tribute

An immersive, brutalist inkpunk microsite crafted for **Maheshwari Public School** to celebrate Teacher's Day.

---

## 🚀 How to Deploy on Vercel

### Option 1: Via Vercel CLI (Fastest)
1. Install Vercel CLI if you haven't already:
   ```bash
   npm i -g vercel
   ```
2. Open terminal inside this folder and run:
   ```bash
   vercel
   ```
3. Follow the prompts — your site will be live instantly!

---

### Option 2: Via GitHub + Vercel Dashboard
1. Push this directory to your GitHub repository.
2. Go to [Vercel Dashboard](https://vercel.com/new).
3. Import your GitHub repository.
4. Click **Deploy** (no build command needed — zero configuration required!).

---

## 📂 Project Structure

```
teachers-day/
├── index.html            # Page 1: Hero & Tribute
├── page2.html            # Page 2: Teacher Name Search Form
├── card.html             # Page 3: Official Digital Card Showcase
├── teachers-db.js        # Centralized Teacher Database
├── vercel.json           # Vercel deployment configuration
├── package.json          # Project metadata
└── cards/                # Teacher Digital Card PNG/JPG Images
    └── shweta_maam.jpg   # Card for Shweta Ma'am (English)
```

---

## ➕ How to Add New Teachers to the Database

Open `teachers-db.js` and add a new entry to the `TEACHERS_DATABASE` array:

```javascript
{
  id: "teacher_name",
  name: "Teacher Name",
  aliases: ["name", "alias1", "alias2"],
  subject: "Subject Name",
  role: "Role / Tagline",
  cardImg: "cards/your_image.png",
  quote: "Personalized tribute quote..."
}
```
Place their digital card image inside the `cards/` directory!
