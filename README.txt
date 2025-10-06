
Indian Aviation Academy - Deploy Ready React Project
--------------------------------------------------

Contents:
- package.json
- public/index.html
- src/ (React source)
- README (this file)

Instructions (Hindi) — Vercel पर deploy करने के लिए:
1) अपने कंप्यूटर पर GitHub अकाउंट बनाएं (यदि नहीं है) और ये प्रोजेक्ट GitHub पर push करें:
   - git init
   - git add .
   - git commit -m "Initial commit - Indian Aviation Academy"
   - Create a GitHub repo and push.

2) Vercel पर जाएँ (https://vercel.com) और "Import Project" -> "From Git" चुनें और अपने GitHub repo को select करें.
   Vercel स्वतः ही `npm install` और `npm run build` चलाकर साइट deploy कर देगा.

3) Deploy होने के बाद Vercel आपको एक temporary URL देगा (जैसे https://your-project.vercel.app).
   - Vercel Dashboard -> Settings -> Domains -> Add -> indianaviationacademy.limited
   - Vercel आपको DNS records देगा (A / CNAME). इन्हें अपने domain provider (जहां domain खरीदा है) की DNS settings में जोड़ें.
   - DNS update के बाद domain लगभग 1-2 घंटे में live हो जाएगा.

यदि आप **Netlify** का उपयोग करना चाहते हैं:
1) GitHub पर push करें और Netlify में "New Site from Git" चुनें और repo connect करें.
2) Build command: npm run build
   Publish directory: build

यदि आप चाहें तो मैं:
- ZIP के साथ एक step-by-step स्क्रीनशॉट guide भी दे सकता/सकती हूँ, या
- GitHub repo create करके direct Vercel से deploy करने में मदद कर सकता/सकती हूँ.

Contact:
Phone: +91 91492 17021
Email: info@indianaviationacademy.com
