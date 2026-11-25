# בוקיש-טק

דף הנחיתה של בוקיש-טק – בית תוכנה משפחתי בערבה. אתר סטטי (HTML אחד ותמונות), בלי שלב בנייה.

## עדכון
עורכים את `public/index.html` ודוחפים ל-`main`. Cloudflare (Workers Builds) מעלה את הגרסה החדשה תוך כדקה.

## Cloudflare
פרויקט Worker בשם `bokish-tech` שמחובר למאגר (Deploy command: `npx wrangler deploy`), לפי `wrangler.jsonc`.
הכתובת: https://bokish-tech.abokish.workers.dev (צריך ש-workers.dev יהיה Enabled ב-Settings ← Domains & Routes).
קבצי האתר נמצאים בתיקייה `public/`.
