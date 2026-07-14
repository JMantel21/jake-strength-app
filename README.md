# Jake's Strength App — Version 0.8

## New in Version 0.8
- Private Supabase email sign-in
- Passwordless magic-link authentication
- Automatic cloud backup
- Local-first/offline operation
- Debounced automatic synchronization after changes
- Cloud restore
- Cross-device sign-in foundation
- Version 0.7 local-data migration
- Cloud & Account screen
- Connection and sync-status indicators
- Oura and Apple Health bridge database foundation

## Supabase project
This build is configured for:
- Project URL: https://gzjowieqgzebrgupjgtn.supabase.co
- GitHub Pages redirect: https://jmantel21.github.io/jake-strength-app/

Only the browser-safe Supabase publishable key is included. Never add a service-role key to this repository.

## Required Supabase setup
Run `jake_strength_supabase_setup.sql` before deploying this version.

Authentication URL Configuration should include:
- Site URL: https://jmantel21.github.io/jake-strength-app/
- Redirect URL: https://jmantel21.github.io/jake-strength-app/
- Optional local redirect: http://localhost:8000/

## First sign-in
1. Deploy Version 0.8.
2. Open the live GitHub Pages app.
3. Enter your email.
4. Open the Supabase magic-link email on the same iPhone.
5. The app imports existing Version 0.7 local data and creates your private cloud row.

## How sync works
- Every change saves locally immediately.
- Cloud upload follows automatically when online.
- Opening the app on another device restores the newest cloud copy after sign-in.
- Manual Sync Now and Restore Cloud Copy controls are available under More -> Cloud & Account.

## Deployment
Replace the repository files with this folder's contents, commit, and push.

Service-worker cache: `jakes-strength-v08`

After GitHub Pages deploys:
1. Open the site in Safari.
2. Refresh once.
3. Close the Home Screen app fully.
4. Reopen it.
