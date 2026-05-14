# Invigilator — Help & FAQ

This page answers common questions about Invigilator. If your question
is not here, please contact us:

- **Email:** mridul.spm@gmail.com
- **Phone:** +91-8800777452

---

## What does Invigilator do?

Invigilator helps students preparing for competitive examinations stay
focused during their study sessions. You start a focus session of a
chosen duration (25, 45, 60, or 90 minutes, or open-ended). The app
quietly watches which apps you open on your phone during that session.

If you switch to a distracting app (like YouTube, Instagram, or other
social media), Invigilator first gives you a gentle voice reminder.
If you keep wandering, the reminders escalate, and eventually you get
a notification asking you to refocus or end the session.

Parents can link their account to their child's account and see
summaries of how many study sessions their child completed and how
many reminders were issued.

---

## Why does Invigilator need "Usage Access" permission? Is my data safe?

To detect when you switch to a distracting app, the app needs
permission to know which app is currently in the foreground. This
permission is called "Usage Access" in Android settings.

When you grant this permission, Android shows a generic warning
saying it "can put your personal info at risk." This warning is shown
for every app that requests this permission, not just Invigilator.

**What Invigilator actually does with this permission:**
- Looks at which app is in the foreground during your active study session
- Knows the name of the app (e.g., "com.google.android.youtube")
- That is all

**What Invigilator does NOT do:**
- Does not see your messages, emails, or chats
- Does not access your photos, videos, or files
- Does not see what you type or search
- Does not record audio, video, or screenshots
- Does not see your bank or payment info
- Does not access your contacts
- Does not track your location
- Does not collect anything outside of an active study session

You can revoke this permission anytime from Android Settings → Apps →
Invigilator → Permissions.

For full details, see our [Privacy Policy](https://mr-mishra21.github.io/invigilator-legal/).

---

## Why am I hearing voices when I open YouTube?

That's Invigilator's "nudge" — a voice reminder asking you to return
to your study. Invigilator speaks when you switch from a study-related
app (or no app) to a distracting app during an active focus session.

The voice reminders escalate over time:
1. First reminder after 60 seconds in a distracting app — gentle question
2. Second reminder at 2 minutes — firmer suggestion
3. Final reminder at 3 minutes — direct nag with a notification

If the voice is in the wrong language, change your app language in
**Settings → Language**.

If the voice sounds robotic or mispronounces words, that is a limitation
of your phone's Text-to-Speech engine, not Invigilator. You can install
better Indic language voice packs from Settings → Languages on your
phone.

---

## How can my parent see my focus sessions?

Your parent must create an Invigilator account and link your account
to theirs:

1. Your parent opens Invigilator and signs in
2. Your parent taps "Link a student" and gets a 6-character code
3. You open your Invigilator app and tap "Connect to parent"
4. You enter the 6-character code your parent shares with you
5. Your parent reviews the linking request and confirms

After this, your parent can see how many focus sessions you completed,
how many reminders you received, and other session summaries.

Your parent **cannot** see what apps you opened (beyond whether the
session had distractions), what you typed, or any content of your apps.
They see only summary information about your focus behavior.

---

## How do I link my child's account? (For parents)

1. Make sure your child has already created an Invigilator account on
   their own phone
2. Open Invigilator on your phone and sign in
3. From your home screen, tap "Link a student"
4. The app shows you a 6-character code
5. Share this code with your child (via WhatsApp, SMS, or in person)
6. Your child opens their app, taps "Connect to parent," and enters the code
7. You confirm the linking request

Once linked, you will see your child's session summaries on your home
screen.

If your child is under 18, you will be asked to formally consent to
data processing on their behalf, as required by the Digital Personal
Data Protection Act, 2023. This is a one-time step during linking.

---

## The app keeps asking for permission even after I granted it. What's wrong?

This issue affects some Samsung and Xiaomi phones, where the system
takes a few seconds to register that a permission has been granted.

If you see "Permission required" even after you turned on Usage Access
in Android settings:

1. Wait about 5-10 seconds — the app shows a "Verifying..." message
   while the system catches up
2. If it still says "permission required" after 10 seconds, press
   **Back** to return to the home screen, then re-open Invigilator
3. The permission should now be recognized

If the problem persists, contact us at mridul.spm@gmail.com.

---

## Will this drain my battery?

We tested Invigilator on real Indian budget phones during 90-minute
study sessions. Battery drain was between 6% and 9% over the full
session, which is normal for a foreground app that keeps your screen
on. When the app is idle (not in an active session), battery use is
about 1% per 30 minutes.

If you find your battery draining faster than expected:
1. Make sure no other apps are running in the background
2. Check your screen brightness — high brightness consumes much more
   battery than Invigilator
3. If you still see unusual drain, report it to us with your phone
   model and Android version

---

## How do I change the app language?

Open Invigilator → **Settings → Language**, and choose from:
- English
- Hindi (हिंदी)
- Assamese (অসমীয়া)
- Bengali (বাংলা)

The voice reminders during a focus session will also switch to your
chosen language.

---

## How do I delete my account?

To permanently delete your account and all your data:

1. Open Invigilator → **Settings → Account → Delete my account**
2. Confirm the warning dialog
3. Verify your identity by entering the OTP sent to your phone
4. Confirm a final time

Your account, all your session data, and your Firebase Auth record
will be permanently deleted within 7 days. This cannot be reversed.

If you are a parent, deleting your account will also delete the
accounts of any linked minor children, because parental consent is
the legal basis for their data processing.

---

## Who do I contact for help?

- **Email:** mridul.spm@gmail.com
- **Phone:** +91-8800777452

For privacy-specific questions, see our
[Privacy Policy](https://mr-mishra21.github.io/invigilator-legal/).

For general feedback or feature requests, use the **Send feedback**
link in app Settings.

---

## A note on this page

This FAQ will grow based on questions from real users during our pilot.
If your question is not answered here, please tell us — we'll add it.

*Last updated: 14/05/2026*
