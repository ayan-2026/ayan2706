AYAN TRAVELLING AND CSC CENTRE — Android App Project

এই ZIP-এর মধ্যে আপনার Ayan_Travelling_Final.html ফাইলটি Android WebView অ্যাপের ভিতরে রাখা হয়েছে।

APK বানানোর নিয়ম:
1. কম্পিউটারে Android Studio ইনস্টল করুন।
2. ZIP ফাইলটি Extract করুন।
3. Android Studio > Open > extracted AyanTravellingAndroid ফোল্ডার খুলুন।
4. Gradle sync শেষ হওয়া পর্যন্ত অপেক্ষা করুন (ইন্টারনেট লাগবে)।
5. Build > Build Bundle(s) / APK(s) > Build APK(s) চাপুন।
6. APK সাধারণত app/build/outputs/apk/debug/app-debug.apk-এ তৈরি হবে।
7. APK মোবাইলে পাঠিয়ে ইনস্টল করুন। প্রয়োজনে Android Settings থেকে এই উৎসের app install অনুমতি দিন।

গুরুত্বপূর্ণ:
- এই পরিবেশে Android SDK/Gradle build tool নেই, তাই এখানে সরাসরি installable APK compile করা যায়নি; এটি Android Studio-তে build করার project।
- অ্যাপ চালাতে ইন্টারনেট প্রয়োজন, কারণ HTML-এ Firebase এবং অনলাইন service link আছে।
- Firebase Authentication / Google sign-in-এর মতো WebView-নির্ভর কিছু প্রবাহ Android-এ আলাদা করে পরীক্ষা করতে হবে।
- ক্লাউড ডেটা ঠিকভাবে সিঙ্ক হচ্ছে কি না, এই project তৈরি করলেই তা নিশ্চিত হয় না; Firebase rules/configuration এবং বাস্তব মোবাইলে পরীক্ষা প্রয়োজন।

GitHub দিয়ে APK বানানোর সহজ পদ্ধতি:
1. GitHub.com-এ sign in করে New repository তৈরি করুন (Public বা Private)।
2. এই ZIP extract করে ভেতরের সব ফাইল ও .github ফোল্ডার repository-তে upload করুন। শুধু ZIP ফাইলটি repository-তে upload করবেন না।
3. Commit changes করুন। Actions tab-এ “Build Android APK” workflow চলবে।
4. কাজ শেষ হলে Actions > সফল workflow run > Artifacts থেকে “AyanTravelling-debug-apk” ডাউনলোড করুন। ZIP extract করলে app-debug.apk পাবেন।
5. APK মোবাইলে পাঠিয়ে install করুন। Android চাইলে browser/file manager-এর জন্য “Install unknown apps” অনুমতি দিতে হবে।

নোট: এটি debug APK। Firebase login, cloud sync, file upload এবং external links বাস্তব Android ফোনে পরীক্ষা করতে হবে।
