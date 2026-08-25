══════════════════════════════════════════════
 Exodus Note — GitHub ပေါ်မှာ Android APK အစစ် ထုတ်နည်း
══════════════════════════════════════════════

ဒီ zip ထဲက file အားလုံးကို ရှိပြီးသား ExodusNote repo ထဲကို
(folder တည်ဆောက်ပုံ မပျက်စေဘဲ) တင်ပေးရပါမယ်။

ပါဝင်တဲ့ file တွေ —
 • index.html (အသစ် — ရှိပြီးသားအောက်ကို overwrite လုပ်ပါ)
 • settings.gradle, build.gradle, gradle.properties, .gitignore
 • app/ folder (Android app source code)
 • .github/workflows/build-apk.yml (APK အလိုအလျောက် build ပေးမယ့် script)

─────────────────────────────────────────────
အဆင့် ၁ — File တွေ Upload လုပ်ပါ
─────────────────────────────────────────────
ကွန်ပျူတာရှိရင် (အလွယ်ဆုံး) —
 1. Zip ကို extract လုပ်ပါ
 2. github.com/(username)/ExodusNote မှာ "Add file → Upload files"
 3. Extract လုပ်ထားတဲ့ file/folder အားလုံးကို drag & drop → Commit
    (ဖုန်း browser တွေမှာ folder drag & drop အဆင်မပြေရင်
    "Create new file" နဲ့ file name မှာ path အပြည့်ရိုက်ပြီး
    ဥပမာ app/src/main/AndroidManifest.xml ဆိုပြီး content ကူးထည့်လို့ရပါတယ်)

⚠️ သတိပြုရန် — .github/workflows/build-apk.yml က အစကနေ ဒီအတိုင်း
   path မှန်မှ အလုပ်လုပ်ပါမယ်။

─────────────────────────────────────────────
အဆင့် ၂ — APK ကို စောင့်ယူပါ
─────────────────────────────────────────────
 1. Upload ပြီးတာနဲ့ repo ရဲ့ "Actions" tab ကို သွားပါ
 2. "Build Android APK" ဆိုတဲ့ workflow အလုပ်လုပ်နေတာ တွေ့ရပါမယ်
    (ပထမဆုံးအကြိမ် စမှတ်ပါ — Actions tab မှာ "enable" ခိုင်းရင် နှိပ်ပေးပါ)
 3. ၅–၁၀ မိနစ်အတွင်း အစိမ်းရောင် ✓ ဖြစ်သွားပါမယ်
 4. အဲ့ run ကိုနှိပ်ပြီး အောက်ဆုံးက "Artifacts" အပိုင်းမှာ
    "ExodusNote-APK" ကို download လုပ်ပါ (zip ဖိုင်ရပါမယ်)
 5. Zip ထဲက app-debug.apk ကို ဖုန်းထဲ ကူးပြီး install လုပ်ပါ
    ("Install unknown apps" ခွင့်တောင်ရင် ခွင့်ပြုပေးပါ)

─────────────────────────────────────────────
ရလာမယ့် App အကြောင်း
─────────────────────────────────────────────
 • တကယ့် Android app အစစ် — code အားလုံး APK ထဲမှာ ထည့်မြှုပ်ထားလို့
   Internet လုံးဝမလိုပါ (Internet permission တောင် မပါဝင်ပါ)
 • Note တွေက app ရဲ့ ကိုယ်ပိုင် storage ထဲမှာ သိမ်းတယ် — privacy အပြည့်
 • Backup / Export တွေက ဖုန်းရဲ့