লিমন রেফ্রিজারেটর — ফোন থেকে APK বানানোর নিয়ম

১) এই ZIP-এর সব ফাইল GitHub repository-তে upload করো।
২) GitHub-এর Actions ট্যাবে যাও।
৩) "Build Limon Refrigerator APK" workflow নির্বাচন করো।
৪) "Run workflow" চাপো।
৫) কাজ শেষ হলে নিচের workflow run-এ ঢুকে Artifacts থেকে "limon-refrigerator-apk" ZIP download করো।
৬) ZIP extract করলে app-debug.apk পাবে।
৭) APK ফোনে install করো।

নোট:
- এটি debug APK।
- অ্যাপটি offline-এ কাজ করবে এবং browser local storage ব্যবহার করবে।
- ফোন পরিবর্তন/অ্যাপের data মুছে গেলে data হারাতে পারে, তাই অ্যাপের Backup ব্যবহার করা ভালো।
