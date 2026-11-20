PAWCARE GUIDE — GITHUB PAGES SEO PACKAGE

ফাইলগুলো:
1) index.html — আপনার মূল ওয়েবসাইট। মূল ডিজাইন ও JavaScript ফিচার অপরিবর্তিত রাখা হয়েছে; SEO title, description, robots, social preview metadata এবং basic WebSite structured data যোগ করা হয়েছে।
2) robots.txt — crawler access নির্দেশনা।
3) sitemap.xml — এক-পৃষ্ঠার সাইটম্যাপ টেমপ্লেট।

প্রকাশের আগে অবশ্যই:
- GitHub username ও repository name বসিয়ে robots.txt এবং sitemap.xml-এর placeholder URL পরিবর্তন করুন।
- URL-এর শেষে / রাখুন। উদাহরণ: https://username.github.io/pawcare-guide/
- সব ফাইল repository-র root-এ আপলোড করুন।

GitHub Pages:
Repository > Settings > Pages > Deploy from a branch > main > /(root) > Save.

Google indexing:
1. সাইট প্রকাশ হওয়ার পর Google Search Console-এ Domain/URL-prefix property যোগ করে ownership verify করুন।
2. Sitemaps অংশে sitemap.xml submit করুন।
3. URL Inspection দিয়ে homepage পরীক্ষা করে Request indexing দিন।

গুরুত্বপূর্ণ:
- SEO সেটআপ Google-এ indexing বা ranking নিশ্চিত করে না।
- এই ওয়েবসাইটটি single-page static site; sitemap-এ আপাতত একটি URL আছে। নতুন আলাদা HTML page তৈরি করলে sitemap-এ সেগুলো যোগ করতে হবে।
- কনটেন্টকে veterinarian-এর পরামর্শের বিকল্প হিসেবে উপস্থাপন করবেন না। স্বাস্থ্য/জরুরি তথ্য প্রকাশের আগে নির্ভরযোগ্য veterinary source দিয়ে যাচাই করুন।
- GitHub Pages static hosting; login, database বা server-side processing এখানে চলবে না।
