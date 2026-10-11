MAMA COACHING – AUTO OPEN PORTAL (FREE PWA)

1. ZIP को Extract करें।
2. GitHub repository Mamacoaching/mama-coaching-app में index.html और sw.js को Replace करें (या सभी 7 फाइलें Upload करके Commit changes करें)।
3. Settings > Pages: main /(root) ही रखें।
4. 1–5 मिनट बाद वेबसाइट Refresh करें। पुराने version के लिए Ctrl+Shift+R करें या installed app बंद करके दोबारा खोलें।
5. अब ऐप शुरू होते ही मौजूदा Apps Script Portal iframe में खुलने की कोशिश करेगा।
6. अगर Google Apps Script की iframe/browser security के कारण blank/blocked दिखे, तो ऊपर "Portal नहीं खुला? यहाँ दबाएँ" पर क्लिक करें। इस सीमा को GitHub Pages से हटाया नहीं जा सकता।
7. पुराना Code.gs / Apps Script Index.html बदलने की जरूरत नहीं।
8. Icons मामाजी की तस्वीर वाले पिछले पैकेज से लिए गए हैं।
9. config.js में Portal URL वही है जो पिछले पैकेज में था। यदि यह Result Portal है, Registration Portal नहीं, तो सही deployed Registration Portal /exec URL डालें।

NOTE: यह PWA wrapper है; Apps Script की cross-origin restrictions के कारण सभी मोबाइल पर embedded login की गारंटी नहीं।
