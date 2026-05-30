# ◉ orbit

Your second brain. .

A private WhatsApp-style self-chat app where you brain dump anything and AI silently organises it into tasks, events, reminders and ideas.

## Tech Stack
- React Native + Expo
- Supabase (database + edge functions)
- OpenAI GPT-4o mini (AI extraction)

## Current Features
- Chat interface to brain dump thoughts
- AI extracts tasks, events, reminders and ideas automatically
- Organised tab shows all extracted items
- Search through your messages
- Onboarding flow with personalisation
- Free and Pro plan structure

## Setup
1. Clone repo
2. Open snack.expo.dev and paste App.js contents
3. Add Supabase credentials in App.js
4. Deploy edge function from /functions/extract-message
5. Add OPENAI_API_KEY and SUPABASE_SERVICE_ROLE_KEY to Supabase secrets

## Roadmap plan
- [ ] Real email auth via Supabase
- [ ] Stripe payments for Pro plan
- [ ] Voice notes
- [ ] Memory resurfacing
- [ ] Insights tab
- [ ] Play Store release
## Comments
let me know if you have any thoughts/suggestions! 
