# AirwaveConnect

![Markdown](https://img.shields.io/badge/Format-Markdown-blueviolet)
![Format](https://img.shields.io/badge/Format-HTML-blue.svg)
![Templates](https://img.shields.io/badge/Templates-Available-brightgreen)
![Status](https://img.shields.io/badge/Status-Active%20Development-blue)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Maintained](https://img.shields.io/badge/Maintained-Yes-success)
![License](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey)
![Use](https://img.shields.io/badge/Use-Non--Commercial%20Only-critical)

Personal portfolio landing page for [airwaveconnect.com](https://airwaveconnect.com).

## Hosting on GitHub Pages

1. Create a new GitHub repository (e.g. `airwaveconnect`).
2. Upload `index.html` (and this README) to the repo's `main` branch.
3. Go to **Settings → Pages**.
4. Under **Source**, choose `Deploy from a branch` → branch `main` → folder `/ (root)`.
5. Save. Your site will be live at `https://<username>.github.io/airwaveconnect/`.

## Connecting your custom domain

1. In **Settings → Pages → Custom domain**, enter `airwaveconnect.com` and save.
   This creates a `CNAME` file in the repo automatically.
2. At your domain registrar's DNS panel, add these records:

   | Type  | Name | Value                  |
   |-------|------|------------------------|
   | A     | @    | 185.199.108.153        |
   | A     | @    | 185.199.109.153        |
   | A     | @    | 185.199.110.153        |
   | A     | @    | 185.199.111.153        |
   | CNAME | www  | `<username>.github.io.` |

3. Wait a few minutes for DNS to propagate, then enable **Enforce HTTPS** in GitHub Pages settings.

## Editing

The whole site is a single `index.html` with inline CSS — open it in any editor and change the headline, tagline, email, or links as you like.
