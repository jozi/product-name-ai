# نام‌گذاری هوشمند محصول 🎯

یک ابزار هوشمند برای تولید نام‌های خلاقانه محصولات در پلتفرم بسلام با استفاده از هوش مصنوعی

## ✨ ویژگی‌ها

- 🤖 تولید نام هوشمند با استفاده از OpenAI GPT
- 🔄 دریافت خودکار اطلاعات محصول از لینک بسلام
- ✍️ امکان ورود دستی اطلاعات محصول
- 📏 تنظیم طول نام پیشنهادی (کوتاه، متوسط، بلند)
- 🎯 تنظیمات شخصی‌سازی برای شامل کردن:
  - نام برند
  - دسته‌بندی
  - ویژگی‌های محصول
- 🎨 رابط کاربری مدرن و ریسپانسیو
- 📱 سازگار با موبایل و دسکتاپ
- 🔍 نمایش تصاویر و ویژگی‌های محصول به صورت کشویی

## 🚀 شروع به کار

### پیش‌نیازها

- Node.js 18 یا بالاتر
- npm یا yarn
- کلید API از OpenAI
- کلید API از Helicone (اختیاری - برای مانیتورینگ)

### نصب و راه‌اندازی

1. کلون کردن مخزن:
```bash
git clone https://github.com/jozi/product-name-ai.git
cd product-name-ai
```

2. نصب وابستگی‌ها:
```bash
npm install
# یا
yarn install
```

3. ساخت فایل متغیرهای محیطی:
```bash
cp .env.example .env.local
```

4. تنظیم متغیرهای محیطی در فایل `.env.local`:
```env
OPENAI_API_KEY=your_openai_key
HELICONE_API_KEY=your_helicone_key  # اختیاری
```

5. اجرای برنامه در محیط توسعه:
```bash
npm run dev
# یا
yarn dev
```

6. مشاهده برنامه در مرورگر:
```
http://localhost:3000
```

## 🛠️ تکنولوژی‌ها

- **Framework**: [Next.js 13+](https://nextjs.org/)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **AI**: [OpenAI GPT](https://openai.com/)
- **Monitoring**: [Helicone](https://helicone.ai/)
- **Icons**: [Heroicons](https://heroicons.com/)

## 📝 نحوه استفاده

1. لینک محصول بسلام را وارد کنید یا اطلاعات محصول را به صورت دستی وارد کنید
2. تنظیمات مورد نظر برای طول نام و ترجیحات را انتخاب کنید
3. دکمه "تولید نام‌های پیشنهادی" را بزنید
4. نام‌های پیشنهادی به همراه توضیحات نمایش داده می‌شوند
5. با کلیک روی دکمه کپی، نام مورد نظر را کپی کنید

## 🤝 مشارکت

از مشارکت شما استقبال می‌کنیم! لطفاً موارد زیر را رعایت کنید:

1. Fork کردن مخزن
2. ساخت branch جدید (`git checkout -b feature/amazing-feature`)
3. Commit کردن تغییرات (`git commit -m 'Add amazing feature'`)
4. Push کردن به branch (`git push origin feature/amazing-feature`)
5. ایجاد Pull Request

## 📄 لایسنس

این پروژه تحت لایسنس MIT منتشر شده است. برای اطلاعات بیشتر به فایل [LICENSE](LICENSE) مراجعه کنید.

## 📞 پشتیبانی

برای گزارش مشکلات یا پیشنهادات، لطفاً یک [issue](https://github.com/jozi/product-name-ai/issues) ایجاد کنید.
