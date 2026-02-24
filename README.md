<!--Answer 1:  -->

Answer 1: What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
getElementById দিয়ে একটি নির্দিষ্ট HTML id-কে ধরা যায়।
getElementsByClassName দিয়ে একাধিক HTML class-এর element ধরা যায়।
querySelector দিয়ে HTML-এর id, class এবং tag ধরা যায়। কিন্তু querySelector ব্যবহার করলে শুধুমাত্র প্রথম মিল পাওয়া id, class বা tag-টিই কাজ করে, বাকিগুলো কাজ করে না।
querySelectorAll ব্যবহার করলে querySelector-এর যে সীমাবদ্ধতা আছে, তা দূর করা যায়। কারণ এটি মিল পাওয়া সবগুলো element একসাথে ধরে।

<!-- Answer 2: -->

Answer 2: DOM ব্যবহার করে HTML-এর সব ধরনের কাজ করা যায়। DOM-এর মাধ্যমে document.createElement() ব্যবহার করে HTML-এর মধ্যে যেকোনো section, div বা অন্য HTML tag তৈরি করা যায় এবং appendChild()-এর মাধ্যমে সেটিকে DOM-এ যোগ করা হয়।
এছাড়াও, DOM ব্যবহার করে innerText দিয়ে লেখা দেখা যায় এবং innerHTML দিয়ে নতুন content সেট করা যায়।

<!-- Answer 3: -->

Answer 3: Event Bubbling হলো একটি উল্টো গাছের মতো, যেখানে পাতার থেকে ছোট ডাল, তারপর বড় ডাল, এবং শেষ পর্যন্ত গাছের গোঁড়ায় পর্যন্ত ইভেন্ট চলে যায়।
সহজভাবে বলতে গেলে, ইভেন্ট প্রথম child element-এ ঘটে এবং ধীরে ধীরে তার parent-এর দিকে ছড়িয়ে যায়।

<!--Answer 4:  -->

Answer 4: Event Delegation হলো এমন একটি পদ্ধতি যেখানে আমরা parent element-এ event listener বসাই, এবং parent-এর child element-এ কোনো event ঘটলেও parent listener সেটিকে handle করে।

<!-- Answer 5: -->

Answer 5: preventDefault() হলো একটি method যা event-এর স্বাভাবিক কাজ বন্ধ করে দেয়।
stopPropagation() হলো একটি method যা নির্দিষ্ট স্থানে কাজ করে event-এর ছড়ানো বন্ধ করে দেয়, অর্থাৎ event উপরের element-এ পৌঁছাবে না।
