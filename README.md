# Family Nutrition Tracker

Static frontend for the Supabase project. Upload these files to the root of `YarKram/Family-nutrition-tracker`.

## Deploy with Netlify
1. Open https://app.netlify.com/ and sign in with GitHub.
2. Add new site → Import an existing project → GitHub.
3. Select `YarKram/Family-nutrition-tracker`.
4. Build command: leave blank. Publish directory: `.`.
5. Deploy.

The app uses the existing Supabase URL and publishable key in `index.html`. The key is intended for browser use; database access is protected by RLS. Never put a Supabase service-role key in frontend code.

## Scope of this starter
- Email OTP sign-in; family profiles; meal, weight and water logs; private meal photo upload; CSV export.
- Starter weekly menu and shopping checklist.
- Profile values are intentionally not pre-filled because the specification's example values need confirmation.
- Nutrition values are entered manually. Photo-based calorie estimation is not implemented.
- True push notifications while the site is closed are not implemented; browser notification support requires an additional push backend.
- The menu shuffle is a basic prototype and does not calculate recipe ingredients or portion sizes.
