# Multi-Store Price Portal: Vercel + Supabase

Persistent online deployment package. This build intentionally refuses to start without `DATABASE_URL`, preventing accidental writes to Vercel's temporary filesystem.

## Routes
- Developer login: `/developer/login`
- Store login: `/login`

Read `DEPLOY_STEP_BY_STEP_HINDI.txt` before deployment.
