# Omrushikesh Raiwade

**Student developer from Udgir, Maharashtra — I build software my college actually runs on.**

A blood-donor network on the Play Store, a public newspaper archive, and a learning platform. All three are live, and real people use them.

I work mostly in React Native, Next.js and Firebase. The problems I enjoy are the ones where being wrong has a cost — matching a blood request to donors who can genuinely give, or making sure an emergency alert actually arrives on someone's phone.

---

## Projects

### 🩸 RaktSetu — blood donor network
**Android · Google Play** · [Code](https://github.com/Raiwadeom/raktsetu)

Connects people who urgently need blood with nearby verified volunteer donors.

Matching runs on real **red-cell compatibility**, not exact blood-group equality — so a request for A+ also reaches O−, O+ and A− donors. Matching on equality alone would have silently excluded most of the people who could actually help. Donor profiles are ID-verified by an admin before anyone can post or answer a request, and every request is tracked through to closure.

Built without a paid backend: donor matching, notification fan-out and push delivery all run client-side against Firestore security rules, with no Cloud Functions.

`React Native` · `Expo` · `TypeScript` · `Firebase` · `Firestore Rules` · `FCM` · `EAS Build`

### 📰 CSM News Desk — press-cutting archive
**Live:** [csm-news-desk.vercel.app](https://csm-news-desk.vercel.app) · [Code](https://github.com/Raiwadeom/csm-news-desk)

A Pinterest-style public archive of the college's newspaper cuttings. Anyone can browse, open a cutting full-screen and download it — no sign-in. Administrators sign in separately to upload, sort into collections and set publication dates.

Scans upload **browser-to-Cloudinary through signed requests**, so large images never pass through a serverless function. One set of components serves both the public and admin views via a `readOnly` prop, rather than duplicating the UI.

`Next.js` · `Firebase Auth` · `Firestore` · `Cloudinary` · `Vercel`

### 📚 DyanSetu — learning platform
**Live:** [dyansetu.vercel.app](https://dyansetu.vercel.app) · [Code](https://github.com/Raiwadeom/dyansetu)

A quiz-based learning app, deployed on Vercel with serverless API routes and Firebase behind it.

`Vite` · `JavaScript` · `Firebase` · `Vercel Serverless`

---

## Tools I work with

**Languages** — TypeScript · JavaScript · Python · Dart · SQL

**Mobile** — React Native · Expo · EAS Build & Submit · Flutter

**Web** — Next.js · React · Node.js · Vite · HTML · CSS

**Backend & data** — Firebase (Firestore, Auth, Cloud Messaging, Security Rules) · MongoDB · REST APIs · Cloudinary

**Shipping** — Git · Vercel · Google Play Console

---

## Reach me

[![Email](https://img.shields.io/badge/Email-Raiwadeomrushikesh%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:Raiwadeomrushikesh@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-om--raiwade-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/om-raiwade)

Open to internships and collaboration — especially anything where the software has to work when it matters.
