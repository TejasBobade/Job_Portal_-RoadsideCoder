# 00:05:46 Setup React App with Shadcn UI
-  npm create vite@latest
- project name -> JobPortal_Hired
- cd JobPortal_Hired
- npm install
- install shadcn ui -> https://ui.shadcn.com/docs/installation/vite -> Follow the steps

# 00:10:10 Shadcn UI Components
- npx shadcn@latest add button
- npx shadcn@latest add accordion
- npx shadcn@latest add carousel
- npx shadcn@latest add card
- npx shadcn@latest add drawer
- npx shadcn@latest add input
- npx shadcn@latest add label
- npx shadcn@latest add radio-group
- npx shadcn@latest add textarea

# 00:14:00 Defining the App Routes
-  npm i react-router-dom
- create a route in App.jsx
- src -> create new folder(layouts) -> create new file(app.layout.jsx)
- src -> create new folder(pages) -> create new file ->
landing.jsx
job-listing.jsx
my-jobs.jsx
onboarding.jsx
post-job.jsx
saved-job.jsx

# 00:19:32 Header Component
- components -> create new file (theme-provider.jsx)

# 00:27:09 Supabase Setup
- supabase -> https://supabase.com/dashboard/projects
- new organization
- connect -> AppFrameworks -> copy past
- create new file (.env) in root
- create new folder(utils) -> create new file (supabase.js) 
- npm i @supabase/supabase-js

- > clerk -> https://dashboard.clerk.com/apps/app_2qvvbRZGYDtcvnhJSaDB6yUJEu9/instances/ins_2qvvbWlJzuuLdVIw8VPLMPyb0vm
- npm install @clerk/clerk-react
- npm install @clerk/themes

# 00:32:54 Connecting Supabase with Clerk
- > How to connect supabase with clerk
- https://supabase.com/partners/integrations/clerk
- cleark -> JWT Templates -> https://dashboard.clerk.com/apps/app_2qvvbRZGYDtcvnhJSaDB6yUJEu9/instances/ins_2qvvbWlJzuuLdVIw8VPLMPyb0vm/jwt-templates -> new template
- supabase -> settings -> api -> JWT settings

# 00:35:58 Landing Page
- for courser we need data
- src -> cerate new folder(data) -> create new file(companies.json)
-  npm i embla-carousel-autoplay -> install auto carousel
- faq section -> data -> cretae file(faq.json)