# NextTopper — প্রথম কার্যকর সংস্করণ

## এতে কী আছে?
- Biology, Chemistry, Physics, English ও General Knowledge-এর নমুনা MCQ
- উত্তর যাচাই ও বাংলা ব্যাখ্যা
- বিষয়ভিত্তিক অনুশীলন ও ৫ মিনিটের টাইমড কুইজ
- স্কোর, সঠিক উত্তরের হার ও ভুলের খাতা (এই ডিভাইসে সংরক্ষিত)
- মোবাইল/ডেস্কটপ রেসপনসিভ ডিজাইন
- HTTPS হোস্টিংয়ে PWA ইনস্টলেশন ও বেসিক অফলাইন ক্যাশ

## ফোনে দ্রুত পরীক্ষা
1. ZIP ফাইলটি Extract করো।
2. `index.html` ফাইলটি ব্রাউজারে খোলার চেষ্টা করো। কিছু ব্রাউজারে ফাইল সরাসরি খোলা গেলেও PWA install/offline-এর জন্য HTTPS hosting দরকার।
3. অনলাইনে প্রকাশ করতে চাইলে পুরো ফোল্ডারটি GitHub repository-তে আপলোড করে GitHub Pages চালু করো।

## GitHub Pages-এ প্রকাশের সংক্ষিপ্ত ধাপ
1. github.com-এ অ্যাকাউন্ট তৈরি/সাইন ইন।
2. নতুন repository তৈরি করো, যেমন `nexttopper`.
3. `index.html`, `manifest.json`, `sw.js` আপলোড করো।
4. Repository Settings → Pages → Deploy from a branch → `main` এবং `/ (root)` বেছে Save করো।
5. প্রকাশিত HTTPS URL মোবাইলে খোলো; ব্রাউজারের menu থেকে Add to Home screen/Install app বেছে নাও।

## গুরুত্বপূর্ণ
- এটি একটি starter demo, পূর্ণাঙ্গ বা অফিসিয়াল প্রশ্নব্যাংক নয়।
- নমুনা প্রশ্নগুলো শিক্ষামূলক উদাহরণ; বিষয়-শিক্ষকের মাধ্যমে উত্তর ও ব্যাখ্যা যাচাই করে বড় প্রশ্নব্যাংক তৈরি করা উচিত।
- Progress Local Storage-এ থাকে, তাই একই ডিভাইস/ব্রাউজারের মধ্যে সীমাবদ্ধ; অন্য ডিভাইসে সিঙ্ক হয় না।
- এই সংস্করণে login, cloud database, admin panel, notification বা Play Store package নেই।
- Play Store-এ প্রকাশের জন্য পরবর্তী পর্যায়ে Android packaging, policy review, testing ও developer account লাগবে।

## পরবর্তী উন্নয়নের প্রস্তাবিত ক্রম
1. প্রশ্নগুলো আলাদা JSON ফাইলে স্থানান্তর ও বিষয়/অধ্যায় অনুযায়ী সাজানো
2. সম্পূর্ণ সিলেবাস অনুযায়ী যাচাইকৃত প্রশ্ন ও ব্যাখ্যা
3. ভুল প্রশ্নের পুনরাবৃত্তি, bookmark ও দৈনিক লক্ষ্য
4. Admin panel / cloud database (প্রয়োজন হলে)
5. Capacitor দিয়ে Android package তৈরি ও পরীক্ষণ
