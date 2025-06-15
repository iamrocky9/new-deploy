# CELPIP Writing Practice MVP (No API Key Required)

This is a minimal, deployable mock version of the CELPIP Writing Task 1 and Task 2 practice tool. It simulates realistic writing prompts, lets users submit answers, and returns mock scoring feedback — all **without needing an OpenAI API key**.

---

## 🚀 Demo

🟢 **Live version:** [Deploy it now →](https://vercel.com/new/clone?repository-url=https://github.com/openai-pilot/celpip-writing-no-api)

---

## ✨ Features

- ✅ Task 1 (Email Writing) and Task 2 (Survey Response)
- ✅ 50+ practice prompts included
- ✅ Mock scoring system with feedback (no API key needed)
- ✅ Mobile-friendly & lightweight
- ✅ Instant deploy to Vercel

---

## 📦 Tech Stack

- [Next.js](https://nextjs.org/)
- [React](https://reactjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vercel](https://vercel.com)

---

## 🧪 Local Development

```bash
git clone https://github.com/openai-pilot/celpip-writing-no-api.git
cd celpip-writing-no-api
npm install
npm run dev
```

Then visit [http://localhost:3000](http://localhost:3000)

---

## 🔐 Optional: Enable Real Scoring

To use GPT for real scoring:

1. Get an [OpenAI API key](https://platform.openai.com/account/api-keys)
2. Add this to your `.env.local` file:
   ```
   OPENAI_API_KEY=your-key-here
   ```

---

## 📝 To Do

- [ ] Add real Whisper voice input (optional)
- [ ] Save scores using Supabase or Firebase
- [ ] Add response timer + character count

---

## 📄 License

MIT — free to use, modify, and build on.
