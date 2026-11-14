# WCC PC Inspector

Free Windows tool from **Win Computer Center** (Yangon) for checking second-hand PCs and laptops before you buy or sell them. It runs on Windows 10 and 11 (64-bit).

It shows the CPU, RAM, GPU, disks (SSD/HDD health, temperature, hours), battery wear, Device Manager problems, Wi-Fi, Bluetooth, camera, and the Windows and Office licence. It includes screen, keyboard, touchpad, speaker, microphone, camera and USB tests, and saves a PDF report in English or Myanmar.

## Download

Download WCC PC Inspector **only from this page**. A copy from Facebook, Telegram or someone else's USB stick may have been changed. Always check it against `SHA256SUMS.txt` (see below).

Go to [Releases](../../releases/latest) and download one of these:

- `WCC_PC_Inspector_vX.Y.Z_Setup.exe` installs the app. From 3.1.0, Setup asks how to install:
  - **Install for all users (recommended)** puts it in `C:\Program Files\WCC PC Inspector`. It needs an administrator password once. Normal programs cannot change files there, so **Run as administrator** stays safe.
  - **Install for me only** needs no administrator password and puts it in your own AppData folder.
  - An upgrade keeps the choice you made before. Uninstall also removes the app's settings and logs.
- `WCC_PC_Inspector_vX.Y.Z_portable.zip` needs no install. Unzip it and run `WCC_PC_Inspector.exe`. It works from a USB stick. Only use **Run as administrator** from a USB stick that is yours, because anyone who can write to the stick can change the files.

For full disk health (SMART, temperature, hours), right-click the app and choose **Run as administrator**.

## "Windows protected your PC" message

The app is free and not code-signed, so Windows SmartScreen may warn you. Click **More info**, then **Run anyway**.

## Check that your download is genuine (SHA256)

Each release includes `SHA256SUMS.txt`, which lists a fingerprint (SHA256 hash) for every file. If a file was damaged during download, or someone changed it (for example, added a virus) before sharing it with you, its fingerprint will be different. This matters most when you got the file from a friend, a USB stick, or a chat group rather than from this page.

1. Open the folder where the downloaded file is, type `cmd` in the address bar, and press Enter.
2. Run this command, using your file's name:

   ```
   certutil -hashfile WCC_PC_Inspector_vX.Y.Z_Setup.exe SHA256
   ```

3. Compare the long code it prints with the line for the same file in `SHA256SUMS.txt` on the [Releases](../../releases/latest) page.

If they match, the file is exactly the one we published. If they don't match, delete it and download it again from this page only.

## Updates

The app checks this page when it opens and tells you when a newer version is out. Nothing else is sent, and no personal data is collected.

## Licence

Freeware. It is free to use and share unchanged, but it may not be sold. There is no warranty, and reports are a shop inspection aid only. See `LICENSE.txt`.

---

## မြန်မာလို

**Win Computer Center** က အခမဲ့ ထုတ်ပေးထားတဲ့ Windows program ပါ။ Second-hand ကွန်ပျူတာနဲ့ laptop တွေကို မဝယ်ခင်၊ မရောင်းခင် စစ်ဆေးဖို့ သုံးပါတယ်။ Windows 10 နဲ့ 11 (64-bit) မှာ သုံးလို့ရပါတယ်။

- **ဒေါင်းလုဒ်** — ဒီ [Releases](../../releases/latest) စာမျက်နှာကနေပဲ ယူပါ။ Facebook၊ Telegram ဒါမှမဟုတ် တခြားသူ USB ကနေ ရတဲ့ဖိုင်ကို SHA256 မစစ်ဘဲ မသုံးပါနဲ့။ `Setup.exe` က install လုပ်ရတဲ့ ဖိုင်ပါ။ `portable.zip` ကတော့ install မလုပ်ဘဲ USB stick ကနေ တန်း run လို့ရပါတယ်။
- **Install ရွေးချယ်မှု (3.1.0 ကစ)** — **All users (recommended)** ကိုရွေးရင် `C:\Program Files` ထဲ ထည့်ပါတယ်။ Admin password တစ်ခါ လိုပေမယ့် ပိုလုံခြုံပါတယ်။ **Only for me** ကတော့ admin password မလိုပါဘူး။ Upgrade လုပ်ရင် အရင်ရွေးထားတဲ့အတိုင်း ထားပါတယ်။ Uninstall လုပ်ရင် settings နဲ့ log တွေပါ ဖျက်ပေးပါတယ်။
- **Portable ကို USB ကနေ သုံးရင်** — ကိုယ်ပိုင် USB ကနေပဲ **Run as administrator** နဲ့ ဖွင့်ပါ။ တခြားသူ ရေးလို့ရတဲ့ USB ထဲက ဖိုင်တွေကို ပြင်ထားနိုင်လို့ပါ။
- **Disk အသေးစိတ်ကြည့်ချင်ရင်** — app ကို right-click နှိပ်ပြီး **Run as administrator** နဲ့ ဖွင့်ပါ။
- **"Windows protected your PC" ပေါ်ရင်** — **More info** ကို နှိပ်ပြီး **Run anyway** ကို နှိပ်ပါ။ Code signing မလုပ်ထားတဲ့ အခမဲ့ program မို့ ဒီလိုပေါ်တာပါ။
- **ဒေါင်းထားတဲ့ဖိုင် စစ်မစစ် စစ်နည်း (SHA256)** — ဖိုင်တစ်ခုချင်းစီမှာ လက်ဗွေ (hash) ကုဒ် ရှိပါတယ်။ ဖိုင်ပျက်သွားရင် (သို့) တစ်ယောက်ယောက်က ပြင်ထားရင် (virus ထည့်တာ စသည်) ဒီကုဒ် ပြောင်းသွားပါတယ်။ သူငယ်ချင်း၊ USB stick သို့မဟုတ် Telegram ကနေ ရတဲ့ဖိုင်ဆိုရင် စစ်ကြည့်ဖို့ အကြံပြုပါတယ်။
  1. ဖိုင်ရှိတဲ့ folder ကိုဖွင့်၊ address bar မှာ `cmd` ရိုက်ပြီး Enter နှိပ်ပါ။
  2. `certutil -hashfile WCC_PC_Inspector_vX.Y.Z_Setup.exe SHA256` ကို run ပါ (ဖိုင်နာမည်ကို ကိုယ့်ဖိုင်နာမည်အတိုင်း ပြောင်းရိုက်ပါ)။
  3. ထွက်လာတဲ့ ကုဒ်ရှည်ကို [Releases](../../releases/latest) ထဲက `SHA256SUMS.txt` နဲ့ ယှဉ်ကြည့်ပါ။ တူရင် စိတ်ချရပါတယ်။ မတူရင် ဖိုင်ကိုဖျက်ပြီး ဒီစာမျက်နှာကနေပဲ ပြန်ဒေါင်းပါ။
- **Update** — ဗားရှင်းအသစ် ထွက်ရင် app ဖွင့်တဲ့အချိန်မှာ အလိုလို ပြောပြပါလိမ့်မယ်။
- **စည်းကမ်း** — အခမဲ့ သုံးနိုင်၊ မျှဝေနိုင်ပါတယ်။ ရောင်းချခွင့် မရှိပါ။ Report က ဆိုင်စစ်ဆေးမှုအတွက်သာ ဖြစ်ပြီး အာမခံ မဟုတ်ပါ။

Win Computer Center · 09 40100 7474 / 09 95353 4242
