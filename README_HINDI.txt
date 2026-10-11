MAMA COACHING FREE INSTALLABLE WEB APP (PWA)

यह ZIP वेबसाइट पर लगाने के लिए है, Android APK नहीं है। कोई Code.gs या Index.html बदलने की जरूरत नहीं।

1. ZIP Extract करें। GitHub पर FREE account बनाएं।
2. GitHub में New repository बनाएं, नाम रखें mama-coaching-app, Visibility PUBLIC.
3. Add file > Upload files से index.html, config.js, manifest.webmanifest, sw.js और icons folder की दोनों PNG फाइलें उसी structure में अपलोड करें। Commit changes करें।
4. Settings > Pages > Build and deployment > Deploy from a branch > main / (root) > Save करें।
5. कुछ मिनट बाद आपका लिंक होगा: https://YOUR-GITHUB-USERNAME.github.io/mama-coaching-app/
6. Android Chrome में लिंक खोलें; Install App button आए तो दबाएँ, अन्यथा Chrome ⋮ > Add to Home screen > Install.
7. Student Portal चलाने के लिए Open Portal ↗ दबाएँ। Portal यहाँ खोलें button embedded view आजमा सकता है।

IMPORTANT: config.js में दिया URL आपके Screenshot के Verification Link से लिया गया है। यह Student Registration Portal का वही deployment है या नहीं, इसे जरूर जांचें। अगर अलग है, config.js में window.MAMA_PORTAL_URL के अंदर अपना Registration Portal /exec URL लगाएं, Commit करें।

इस PWA में Google Apps Script और Google Sheets मौजूदा रहेंगे। Google Apps Script iframe login कुछ browser में block हो सकता है; Open Portal हमेशा fallback है। यह APK नहीं है और ऑफलाइन Google Forms/Results नहीं चलेंगे। GitHub Pages free tier की शर्तें और usage limits लागू होती हैं।

Security: Repo public है, इसमें कोई PIN, Spreadsheet ID, student data या private API key न डालें।

नया अपडेट: icons/icon-192.png और icons/icon-512.png में मामाजी के चित्र वाला MAMA COACHING आइकन जोड़ा गया है। GitHub Pages पर पुराने icons और index.html को नए फाइलों से बदलें। Chrome में पुराना आइकन दिखे तो पहले installed shortcut हटाकर दोबारा install करें।

यह चित्र एक डिजाइन-आधारित चित्रण है, सत्यापित आधिकारिक फोटोग्राफ नहीं। यदि आपको बिल्कुल वही असली फोटो चाहिए तो फोटो अपलोड करें।
