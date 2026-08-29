 SIT313 P2 - Welcome Email

Sign-up feature on the DEV@Deakin page, backed by an ExpressJS API that
subscribes users and sends them a welcome email via the Elastic Email
REST API.

Setup requirements

1. Install dependencies:
   
   npm install


2. Sign up at https://elasticemail.com/ and then go to Settings → API →
   Create API Key, and give it full access leve. Copy the key.

   We also need a verified sender email of ours: Settings → Domains and verify the email address. 

3. Start the server:
   
   npm run dev
   

4. Open `http://localhost:3000` in browser. The Express server also
   serves `public/index.html`.



Check terminal to see a line showing the
Elastic Email status and MessageID once it's accepted. The HTTP response
above will show a `200` status code.


