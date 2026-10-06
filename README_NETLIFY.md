# seasdsa - Netlify Production Deployment Package
**সংস্করণ (Version):** 1.0.2
**বিল্ড তৈরির সময়:** ৬/১০/২০২৬, ১১:১৮:১৫ AM (2026-10-06T05:18:15.308Z)
**প্রস্তুতকারী অ্যাডমিন:** তানভীর আহমেদ
**ইমেজ স্ট্যাটাস:** সকল গরুর ছবি (Images) সরাসরি 'images/' ফোল্ডারে অন্তর্ভুক্ত করা হয়েছে।

---

## 🚀 Netlify-তে কীভাবে এই বিল্ড ডিপ্লয় করবেন?

### পদ্ধতি ১: Netlify ড্র্যাগ অ্যান্ড ড্রপ (সবচেয়ে সহজ - ১ মিনিট)
১. [Netlify.com](https://app.netlify.com)-এ লগইন করুন।
২. আপনার "Sites" ড্যাশবোর্ডে যান।
৩. এই ডাউনলোডকৃত ZIP ফাইলটি আপনার কম্পিউটারে আনজিপ (Extract) করুন।
৪. আনজিপ করা ফোল্ডারটি (যার মধ্যে index.html ও images ফোল্ডার আছে) সরাসরি Netlify-এর **"Drag and drop your site output folder here"** বক্সে ড্র্যাগ করে ছেড়ে দিন।
৫. সাথে সাথে আপনার ওয়েবসাইট ও সকল গরুর ছবি সহ লাইভ হয়ে যাবে!

### পদ্ধতি ২: Netlify CLI দিয়ে
```bash
npm install -g netlify-cli
netlify deploy --prod --dir=.
```

---
© ২০২৬ seasdsa | সর্বস্বত্ব সংরক্ষিত।
