PROFITX — मोबाइल से APK बनाने की गाइड

यह पैकेज GitHub Actions के जरिए आपके Android मोबाइल से APK बनवाने के लिए है। लैपटॉप जरूरी नहीं, लेकिन GitHub अकाउंट और इंटरनेट जरूरी है।

ऐप की सीमा:
- यह केवल डेमो स्क्रीन है।
- BUY/SELL उदाहरण रैंडम डेमो हैं।
- XM MT5 या Quotex से लाइव डेटा नहीं जुड़ा है और ट्रेड अपने-आप नहीं लगाएगा।
- डेमो सिग्नल पर असली ट्रेड न करें।

मोबाइल से APK:
1. Chrome में https://github.com/ खोलकर Sign in करें।
2. New repository बनाएं: profitx-mobile (Public चुनें; इससे आसान workflow चलेगा)।
3. ZIP को मोबाइल File Manager में Extract करें।
4. GitHub repository में Add file → Upload files चुनें।
5. Extract किए हुए फोल्डर के अंदर की सभी चीजें अपलोड करें। .github फोल्डर भी जरूर अपलोड करें।
6. Commit changes दबाएं।
7. Actions टैब खोलें। “Build ProfitX Android APK” workflow चलने दें या Run workflow दबाएं।
8. पूरा होने पर workflow run खोलें। नीचे Artifacts में ProfitX-debug-APK डाउनलोड करें।
9. Artifact ZIP Extract करें और app-debug.apk इंस्टॉल करें।

अगर GitHub मोबाइल पेज पर विकल्प न दिखें तो Chrome के ⋮ मेन्यू से Desktop site चालू करें।

यह Debug/Test APK होगा, Play Store वाला signed release नहीं। GitHub पर broker password, API key या MT5 login कभी अपलोड न करें।
