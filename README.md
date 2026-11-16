# GetJoy

The GetJoy beta site (beta.getjoy.com).

- `index.html` is the whole site: the same page as the Claude prototype. It detects where it is running.
- Events and photos are read from Supabase storage; signups, bookmarks and feedback are saved in a Supabase table.
- No keys that need protecting are in this repository. The Supabase key in the page is the publishable one.
