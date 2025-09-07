# ocr-privacy

Docs & pages for **For OCR Model** — a research-only project for OCR on the **Shan** language.  
เอกสารและหน้าเว็บสำหรับโครงการวิจัย **OCR ภาษาไทยใหญ่ (Shan)**

---

## 🔎 What’s in this repo?
This repo hosts public policy pages required for Meta App Review and general transparency.

- `privacy.html` – Privacy Policy (EN + TH)
- `terms.html` – Terms of Service (EN + TH)
- `delete.html` – Data Deletion instructions (EN + TH)
- (Optional) `assets/` – icons, screenshots, screencast links

> All pages are bilingual (English first, Thai below) per reviewer friendliness.

---

## 🔗 Live Pages (GitHub Pages)

Replace `<Tai1360>` with your GitHub username (or your custom domain).

- Privacy Policy: `https://<Tai1360>.github.io/ocr-privacy/privacy.html`
- Terms of Service: `https://<Tai1360>.github.io/ocr-privacy/terms.html`
- Data Deletion: `https://<Tai1360>.github.io/ocr-privacy/delete.html`

### Deploy steps (GitHub Pages)
1. Settings → **Pages** → Source: `Deploy from branch`
2. Branch: `main` → Folder: `/ (root)` → **Save**
3. Wait for Pages to build (~1–2 min).  
4. Add your site’s domain (e.g., `username.github.io`) to **App Domains** in Meta App Settings.

---

## 🧩 How these pages support Meta App Review

- **App Settings › Basic**
  - **Privacy Policy URL** → link to `privacy.html`
  - **Terms of Service URL** → link to `terms.html`
  - **Data Deletion Instructions URL** → link to `delete.html`
  - **App Domains** → add the domain used above (e.g., `username.github.io`)
- These pages explicitly state:
  - Research-only intent for **Shan OCR**
  - Public Page content only (no personal user data)
  - Clear deletion workflow and contact email

---

## 🧪 Local preview

Use any static server, e.g. Python:

```bash
python3 -m http.server 8080
# open http://localhost:8080/privacy.html
