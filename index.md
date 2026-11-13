# NutriPal Demo Privacy Policy

*Effective November 12, 2026*

NutriPal Demo is a private test version of a nutrition-tracking app. It is available only to a small number of people I invite through Apple's TestFlight. It is run by an independent developer, publishing as NutriPal Demo ("I", "me"). This policy explains what the app collects, why, where it is kept, and how to have it deleted.

## What the app collects

**Your access code.** You sign in with a personal access code that I give you. The app keeps it in your iPhone's Keychain, tied to that device: it is not synced through iCloud Keychain and can't be restored onto a different device. The server never stores the code itself, only a one-way fingerprint of it, with a short label I chose (such as "friend-iphone") and when it was issued or revoked.

**Your profile.** When you set up the app, you enter your age, sex, height, weight, activity level and goal (lose, maintain or gain weight). They are used to calculate your daily calorie goal. Your calorie goals, calculated or chosen by you, are stored with the dates they apply from.

**Your meals.** For each meal you log, the server stores the description you typed (if any); the estimated meal name, calories, protein, carbohydrates and fat; the estimate's range, confidence and stated assumptions; which AI service produced it; whether you used text or a photo; when you logged it; the calendar day it belongs to; and when you last edited it.

**Your time zone.** The app sends your iPhone's time-zone name (for example, America/New_York) with each request, so that "today" means your day.

**Meal photos.** If you take or choose a photo, the app first makes it smaller and re-saves it **without the original photo's information, so no location is sent**. The photo goes to the server only to estimate that meal. **The server does not save your photo.** It passes the photo to OpenAI for the estimate and keeps only the result.

**Settings on your iPhone.** Your choice of units (lb or kg, ft or cm) and appearance (light or dark) are stored only on your iPhone.

## How meals are estimated

To estimate a meal, the server sends your meal description and, if you added one, your photo to OpenAI's API. Your access code and profile are not sent. OpenAI processes this data under its own API data policies. As of November 12, 2026, OpenAI says that:
- data sent to its API is not used to train its models unless the customer opts in;
- abuse-monitoring logs are kept for up to 30 days;
- responses from the API this app uses are kept for 30 days by default;
- images may be scanned for illegal content and, if flagged, kept for review.

For current details, see [OpenAI's API data documentation](https://developers.openai.com/api/docs/guides/your-data).

## Where your data is kept

Your profile, meals and goals are stored in a database on a server I run with Railway, a cloud hosting provider, in its US West region in the United States.

When your app contacts the server, Railway records the request in its logs. A log entry includes:
- your network (IP) address;
- your device's software description (for example, its iOS version);
- the address requested within the app's service (for example, the date you are viewing);
- the result and timing.

The logs don't contain your access code, meal descriptions or photos. Under Railway's current plan, I can access these logs for 7 days. When a meal estimate fails, the error is recorded without your meal or photo.

There are currently no backups of the demo database. If that changes, I will update this policy, including how long backups keep deleted data.

## What the app does not do

The app has no advertising and no tracking across apps or websites. I don't use analytics or crash-reporting services. I don't sell your data or share it with anyone except as described above.

Other testers can't see your data: every record belongs to your access code's account, and the server only ever returns your own records.

**TestFlight.** You install NutriPal Demo with Apple's TestFlight app. TestFlight collects its own information, such as crash reports and any feedback or screenshots you choose to send, and shares it with me under [Apple's TestFlight terms](https://www.apple.com/legal/privacy/data/en/test-flight/).

## How long data is kept, and how to delete it

A meal you delete in the app is deleted from the database immediately. Everything else is kept until the demo ends or until you ask me to delete it.

**To delete your account and all its data,** email me at [nutripalsupport@gmail.com](mailto:nutripalsupport@gmail.com). I will delete your profile, goals, meals and access codes within 30 days of receiving your request, and confirm when it's done. You can also ask for a copy of your data. When the demo ends, I will delete the database.

If you lose your access code or think someone else has it, tell me. I will turn it off and give you a new one. Signing out in the app removes the code from your iPhone; it doesn't delete your data.

## Children

NutriPal Demo is not intended for anyone under 13, and the app doesn't accept an age under 13.

## Changes

If this policy changes, I will update this page and its effective date, and tell testers directly.

## Contact

NutriPal Demo — [nutripalsupport@gmail.com](mailto:nutripalsupport@gmail.com)
