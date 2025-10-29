# 🧩 Google Tag Manager (GTM) Recipes Library

Welcome to the **GTM Recipes Library** — a curated collection of reusable GTM container snippets and templates designed to help you track events, conversions, and interactions efficiently across different platforms.

Each recipe is meant to serve as a **starting point** — something you can import, customize, and adapt to your specific setup.

---

## 🚀 Getting Started

### 1. Importing a Recipe

If you're new to GTM, follow these steps to import any `.json` recipe:

1. **Download the Recipe File**
   - Find the recipe you need (e.g., `add_to_cart.json`) and download it to your computer.

2. **Open Google Tag Manager**
   - Go to [https://tagmanager.google.com](https://tagmanager.google.com)

3. **Import the Recipe**
   - Navigate to **Admin → Import Container**
   - Click **Choose Container File** and upload the `.json` file you downloaded
   - Choose your **workspace** (use a *test workspace* if available)
   - Select **Merge** (not overwrite)  
     > 🟡 This ensures you keep your existing tags while adding new ones.

4. **Review & Save**
   - GTM will show you a list of tags, triggers, and variables that will be added.
   - Double-check before confirming.

---

### 2. Exporting Your Own Recipes

If you want to contribute a recipe:

1. Go to **Admin → Export Container**  
2. Choose the workspace containing the tags you want to share  
3. Click **Download** to save the `.json` file  
4. Name it descriptively (e.g., `scroll_depth_tracking.json`)  
5. Add it under the correct category folder in this repo  
6. Include a short `README.md` describing what it does, required variables, and any setup notes  

---

## 🧠 Before You Publish or Use

Please **test everything in Preview Mode** before publishing to production.  
- Verify that tags fire correctly.  
- Confirm events appear properly in GA4, Ads, or your analytics tool.  
- Ensure triggers and variables are set up as expected.  

> ⚠️ **Note:** GTM and analytics platforms evolve quickly. A recipe that worked six months ago may need adjustments today.

---

## 💡 Contributing & Improving Recipes

This repository is a **living resource**. If you notice:
- A recipe that no longer works as intended  
- A more efficient or privacy-friendly way to track something  
- A missing setup step or dependency  

Please **open an Issue** or **submit a Pull Request** with your suggestions.  
We welcome improvements and updated approaches — the goal is to help everyone stay current as tracking standards evolve.

---

## 🧰 Categories (Examples)

| Category | Description |
|-----------|--------------|
| **Ecommerce** | Add-to-Cart, Purchase, and Enhanced Ecommerce tracking |
| **Form Tracking** | HubSpot, Contact Forms, and Lead submissions |
| **Engagement** | Scroll depth, video interactions, and link clicks |
| **Utilities** | Debugging tags, consent setup, and data layer helpers |

---

## ⚙️ Best Practices

- Always import into a **sandbox** or **test workspace** first  
- Follow consistent naming conventions for tags and triggers  
- Keep documentation with each recipe for clarity  
- Test across browsers and devices when applicable  
- Regularly review your recipes as platforms (like GA4 or Consent Mode) update  

---

## 🪄 Disclaimer

These GTM recipes are provided **as-is** and intended for educational and reference purposes.  
Always validate configurations against your business and data policies before use.

---

### 💬 Feedback & Collaboration

If you have questions, find something outdated, or want to suggest a new tracking method — please start a discussion or create a pull request.  
We’re stronger when we share what works.

---

**Created and maintained by the WebOps & Marketing Technology community**  
📍 *Last updated:* _October 2025_

---
