# আমার গ্রন্থাগার

মোবাইলে অ্যাপ হিসেবে ইন্সটলযোগ্য (PWA), ইন্টারনেট ছাড়াও চলে।

## GitHub-এ পাবলিশ (মোবাইল থেকেই করা যায়)
1. github.com-এ লগইন করে **New repository** → নাম দিন `amar-granthagar` → **Public** → Create।
2. **uploading an existing file** লিংকে ঢুকে এই ফোল্ডারের সব ফাইল (`index.html`, `sw.js`, `manifest.webmanifest`, `.nojekyll`, `icons` ফোল্ডার) আপলোড করে **Commit changes** দিন।
3. **Settings → Pages → Source: Deploy from a branch → Branch: main / (root) → Save**।
4. ১–২ মিনিট পর লিংক হবে: `https://আপনার-ইউজারনেম.github.io/amar-granthagar/`

## মোবাইলে ইন্সটল
- **Android (Chrome):** লিংক খুলুন → ⋮ মেনু → **Install app / Add to Home screen**।
- **iPhone (Safari):** লিংক খুলুন → Share বাটন → **Add to Home Screen**।

## আপডেট দিলে
`index.html` বদলান, আর `sw.js`-এর প্রথম লাইনে `amar-granthagar-v1` → `v2` করুন। তাহলে ফোনে নতুন ভার্সন আসবে।
