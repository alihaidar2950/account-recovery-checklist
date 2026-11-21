# Got hacked? The recovery checklist, step by step

**انهكر حسابك؟ شو لازم تعمل، خطوة بخطوة**

I put this together after my Instagram account was hijacked. If you're dealing with an account
takeover, start with the first six steps. Menu names can vary by app version.

جمّعت هالخطوات بعد ما انهكر حسابي عإنستغرام. إذا صار معك نفس الشي، بلّش بأوّل ست خطوات.

---

## The one thing to understand first / أول شي لازم تفهمو

After you sign in, the app keeps you logged in using a **session**. In a browser, this commonly
involves a cookie. Someone who gets a valid session cookie may be able to reuse it without entering
your password or two-factor code. **Change your password and revoke other sessions.**

بعد ما تعمل login، التطبيق بيخلّيك داخل بـsession، وغالباً بتكون محفوظة بـcookie عالـbrowser.
إذا حدا قدر يستعمل الـsession تبعك، ممكن يفوت بلا password أو كود two-factor.
**غيّر الـpassword واعمل log out من باقي الأجهزة.**

---

## Right now: stop it / هلّق فوراً: وقّف الهاكر

1. **Use a device you trust**, such as your phone if you suspect your computer was compromised.
   **استعمل جهاز بتوثق فيه.** إذا شاكك بالكمبيوتر، استعمل تلفونك.
2. **Change the password** of the hacked account to a new one you've never used anywhere.
   غيّر الـpassword لواحد جديد ما استعملتو بأي محل.
3. **Log out every other device.** Instagram and Facebook: Accounts Center → Password and security →
   **Where you're logged in** → select your account → log out other sessions. Then check the list again.
   اعمل log out من كل الأجهزة، وارجع اتأكّد بعد كم دقيقة.
4. **Secure your recovery email.** Change its password, sign out other sessions, and check the
   recovery phone and email. For Gmail, open [Google Account security](https://myaccount.google.com/security)
   and look for **Your devices**. Do this first if someone also has access to your email.
   غيّر password الإيميل كمان، لأنو يلّي معو إيميلك بيقدر يرجّع كل حساباتك.
5. **Turn on two-factor with an authenticator app**, not SMS (Google Authenticator, Microsoft
   Authenticator, or similar). Save the backup codes somewhere offline.
   شغّل الـtwo-factor بـapp، مش SMS، واحفظ الـbackup codes.
6. **Locked out completely?** Instagram's official recovery page: <https://www.instagram.com/hacked/>.
   Use only that link. Anyone who DMs you offering to "recover" your account is a second scam.
   إذا ما عاد فيك تفوت: استعمل الرابط الرسمي بس. أي حدا بيبعتلك إنو بيرجّعلك الحساب = نصّاب.

## Today: clean up / اليوم: نضّف

7. **Check connected apps** and remove any you don't recognise. Instagram: Settings → Website
   permissions → Apps and websites.
   شيل أي app موصول بحسابك وما بتعرفو.
8. **Check your email for traps:** forwarding rules, filters, and the recovery phone and email.
   Hackers add these so they can get back in later.
   شوف إذا في forwarding أو filter أو رقم recovery مش إلك.
9. **Warn your contacts.** Unsend scam messages where you can and post a short Story telling people
   which messages or links to ignore. If you're locked out, warn them through another channel.
   امسح الرسايل الـscam، ونزّل story إنك انهكرت. رفقاتك هنّي الضحية الجاية.
10. **Rotate passwords exposed on a compromised device.** Prioritize email, financial accounts,
    and any reused passwords. Change them from a trusted device.
    غيّر كل الـpasswords المحفوظة بالـbrowser، وابدا بالبنك.
11. **Developers:** replace every API key and token that was on that computer (`.env` files, cloud
    and GitHub tokens), and sign out other sessions on GitHub and your hosting.
    إذا انت مبرمج: بدّل كل الـAPI keys والـtokens.

## This week: fix the computer / هالجمعة: صلّح الكمبيوتر

12. **Remove browser extensions** you don't use or recognize. An extension with broad site access
    can read or change what appears on those sites.
    شيل كل extension مش ضروري.
13. **Run a full antivirus scan** (Windows Security → Virus & threat protection → Scan options →
    Full scan), and let it finish.
    اعمل full scan وخلّيه يخلص للآخر.
14. **If you suspect your computer is still compromised, consider reinstalling Windows.**
    Back up important files first and scan the backup before restoring anything. Microsoft's
    [Windows recovery guide](https://support.microsoft.com/en-us/windows/experience/backup-recovery/recovery-options-in-windows)
    explains the options and which ones erase your files.
    إذا بعدك شاكك إنو الكمبيوتر مخترق، فكّر ترجّع تنزّل Windows. أول شي اعمل backup لملفّاتك المهمّة.

## Never again / ما تعيدها

- **Never press Windows+R, then paste, then Enter because a website told you to.** A fake
  verification screen can use this trick, called ClickFix, to get you to run a malicious command.
  **أبداً ما تكبس Windows+R وبعدين paste وEnter لأنو موقع قلّك.** ما في CAPTCHA حقيقي بيطلب هيك.
- Don't install "cracked" software or random tools you found in a comment or DM.
- Use a password manager, so every account has its own password.
- If an account suddenly sends weird messages, act within minutes: every minute it keeps sending.

---

*I still don't know how the attacker obtained my session. These are the steps I'd use to recover.*

*لهلّق ما عرفت كيف وصل المهاجم للـsession تبعي. هيدي الخطوات يلّي بمشي فيها لرجّع أمّن الحساب.*

## Official help / المساعدة الرسمية

- Instagram [account recovery](https://www.instagram.com/hacked/) and [connected apps and websites](https://www.facebook.com/help/instagram/1144624522593085)
- Google [secure a compromised account](https://support.google.com/accounts/answer/6294825)
- Microsoft [Windows Security scan options](https://support.microsoft.com/en-us/windows/security/threat-malware-protection/virus-and-threat-protection-in-the-windows-security-app) and [how ClickFix works](https://www.microsoft.com/en-us/wdsi/threats/malware-encyclopedia-description?Name=Behavior%3AWin32%2FClickFix)

---

### What next? · شو بعد؟

- ⭐ Star this repo if it helped, so more people find it.
- Follow [@alihaidar.dev](https://www.instagram.com/alihaidar.dev/) on Instagram or [TikTok](https://www.tiktok.com/@alihaidar.dev) for the next free guide.
- All my free guides: [github.com/alihaidar2950](https://github.com/alihaidar2950?tab=repositories)

<div dir="rtl">

إذا فادك، حطّ ⭐ عالـrepo، وتابعني عَ [إنستغرام](https://www.instagram.com/alihaidar.dev/) أو [تيك توك](https://www.tiktok.com/@alihaidar.dev) لتوصلك الأداة الجاية ببلاش.

</div>
