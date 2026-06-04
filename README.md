# ◉ orbit

your **second** **brain**!!
Orbit is a private WhatsApp-style self-chat app where you brain dump anything from texts voice memos images etc into a self-chat and AI organises it into tasks, events, reminders and ideas in the background. 
I decided to build this because I personally text myself a lot (and in the notes app) as a way to brain dump and give future me reminders, but after a while looking for notes got messy. Orbit integrates AI to organise them and also 'resurface memories'. Focus and brainspace is limited and orbit acts as an external ****memory** **storage** **and **recalls** important info for you. 

**Currently refining and adjusting, please let me know if you have any tips/suggestions/advice! Its my first time building an app on my own. **

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

## End goal
Publish to appstore and playstore!
## Comments
once again, do let me know if you have any thoughts/suggestions! 
