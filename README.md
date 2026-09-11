<div align=center>
<a href="#"><img src="https://files.catbox.moe/tl36qw.png"/></a> 

<h1> ☠︎ 𝙋𝙃𝘼𝙉𝙏𝙊𝙈 𝙓 ☠︎ </h1>
<h3> 𝘛𝘩𝘦 𝘜𝘭𝘵𝘪𝘮𝘢𝘵𝘦 𝘞𝘩𝘢𝘵𝘴𝘈𝘱𝘱 𝘉𝘰𝘵 </h3>

  <a href="https://github.com/whiskeysockets/baileys"><img height="22" src="https://img.shields.io/badge/Baileys-000000?style=for-the-badge&logo=whatsapp&logoColor=green"/></a>
  <a href="#"><img height="22" src="https://img.shields.io/badge/NodeJS-000000.svg?&style=for-the-badge&logo=node.js&logoColor=green"/></a>
  <a href="https://gemini.google.com"><img height="22" src="https://img.shields.io/badge/Gemini-000000?style=for-the-badge&logo=googlegemini&logoColor=blue"/></a>
  <a href="https://cloudflare.com"><img height="22" src="https://img.shields.io/badge/Cloudflare-000000?style=for-the-badge&logo=Cloudflare&logoColor=orange"/></a>
</div>

<br>

> [!NOTE]
> **𝙋𝙃𝘼𝙉𝙏𝙊𝙈 𝙓** هو بوت واتساب متطور، خفيف الوزن، وسريع الاستجابة. يدمج بين قوة وكيل الذكاء الاصطناعي (AI Agent)، وإمكانيات المكالمات (VoIP)، وبوابة ويب مخصصة ولوحة تحكم للمستخدمين. تم بناؤه بعناية فائقة باستخدام **Baileys** و **NodeJS v24+** ليمنحك تجربة تحكم مطلقة وأداءً لا يُضاهى. 🌑⚡
> 
> ---
> 
> <p align=center><b>⚡ المميزات الخارقة | Features ⚡</b></p>
> 
> - [x] 🧠 وكيل ذكاء اصطناعي متقدم باستخدام Gemini.
> - [x] 📞 مكالمات صوتية وفيديو 1:1 بجودة عالية.
> - [x] 🔄 دعم الجلسات المتعددة (Multi Sessions).
> - [x] 🗄️ قواعد بيانات مرنة: SQLite / MongoDB.
> - [x] 💬 دعم رسائل الذكاء الاصطناعي الغنية والأزرار التفاعلية.
> - [x] 🌐 نفق Cloudflared للوصول إلى لوحة الويب من أي مكان.
> - [x] 📦 اعتماديات خفيفة وأداء عالٍ (Minimal Dependencies).

---

<table align=center height=100>
  <td>
  <sub>
    
```env
         --- هيكل المشروع | Project Structure ---
PHANTOM-X
├── 📁lib
│   ├── 📁package
│   │   ├── 📁ai            # أنظمة الذكاء الاصطناعي
│   │   ├── 📁voip          # أنظمة المكالمات
│   │   └── 📁website
│   │       ├── 📁views     # واجهات الويب HTML
│   │       └── 📄server.js # خادم الويب
│   ├── 📁scrapers          # أدوات جلب البيانات
│   ├── 📁utils             # الأدوات المساعدة
│   ├── 📄config.js         # إعدادات وتفضيلات البوت
│   ├── 📄main.js           # الملف الرئيسي
│   └── 📄start.js          # نقطة التشغيل
├── 📁data
│   ├── 📁sessions          # حفظ الجلسات
│   ├── 📁tunnel            # بيانات النفق
│   └── 📁tmp               # الملفات المؤقتة
├── 📁plugins               # الإضافات والأوامر
├── 📄.env                  # التوكنات والمتغيرات السرية
├── 📄CHANGELOG.md          # سجل التحديثات
├── 📄LICENSE               # الترخيص
├── 📄package.json          # إعدادات المشروع
└── 📄README.md             # واجهة المشروع
```
</sub>

  </td>
</table>

<div align=center>
  <a href="#"><img height="20" src="https://img.shields.io/badge/Change_log-006600.svg?&style=for-the-badge&logo=files&logoColor=white"/></a>
  <a href="#"><img height="20" src="https://img.shields.io/badge/Discussion-ffffff.svg?&style=for-the-badge&logo=livechat&logoColor=black"/></a>
</div><br>

*✥┉┉┉┉┉┉⦉🧠⦊┉┉┉┉┉┉✥*

<details> 
  <summary align=left><b>🧠 عن وكيل الذكاء الاصطناعي | About AI Agent</b></summary>
<p align=center>──────────────</p>

<h4 align=center >⚙️ كيف يعمل نظام الشفاء التلقائي (AutoHeal)؟</h4>

> ```mermaid
> flowchart LR
>     A@{ shape: odd, label: "أمر المستخدم" } --> Error
>     Error process@==> C@{ shape: diamond, label: "خادم Gemini
> Gemma-4-31b-it"}
>     C --> D@{ shape: circle, label: "⏳" }
>     D ==> E[✅ كتابة وحفظ]
>     D ==> F[❌ إيقاف الشفاء]
>     E --> G[تم بنجاح]
>     F --> H[تسجيل كفشل]
>
> process@{ animate: true }
> style Error stroke:#f00
> ```

<table align=center>
  <tr>
    <td><b>النموذج</b></td>
    <td><b>الاستخدام</b></td>
  </tr>
  <tr>
    <td>Gemini 3.1 Lite-Flash</td>
    <td>المحادثات اليومية السريعة</td>
  </tr>
  <tr>
    <td>Gemini 3.1 Lite</td>
    <td>المحادثات اليومية المعقدة</td>
  </tr>
 <tr>
    <td>Gemma-4-31b-it</td>
    <td>نظام الشفاء التلقائي والبرمجة</td>
  </tr>
  <tr>
    <td>Gemma-4-26b-a4b-it</td>
    <td>نظام الشفاء التلقائي والبرمجة</td>
  </tr>
</table>

<h4 align=center>🛠️ كيفية إضافة أداة جديدة</h4>
  
<details>
  <summary align=center><sub>جميع مساعدات MCP (All MCP Helpers)</sub></summary>
  
<table>
  <thead>
    <tr>
      <th>القسم</th>
      <th>الدالة</th>
      <th>الوصف</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="3"><strong>الجلسات وسجل المحادثات</strong></td>
      <td><code>getSession(jid)</code></td>
      <td>الحصول على مصفوفة سجل المحادثة</td>
    </tr>
    <tr>
      <td><code>resetSession(jid)</code></td>
      <td>مسح سجل المحادثة</td>
    </tr>
    <tr>
      <td><code>getPinnedNotesReadOnly(jid)</code></td>
      <td>الحصول على الملاحظات المثبتة</td>
    </tr>
    <tr>
      <td rowspan="4"><strong>التفاعل مع الذكاء الاصطناعي</strong></td>
      <td><code>runAgent(conn, m, text, opts)</code></td>
      <td>تشغيل دورة الذكاء الاصطناعي والحصول على الرد</td>
    </tr>
    <tr>
      <td><code>runAgentConfirmed(conn, m, opts)</code></td>
      <td>استئناف دورة الذكاء الاصطناعي بانتظار التأكيد</td>
    </tr>
    <tr>
      <td><code>callTool(name, args)</code></td>
      <td>استدعاء أداة أخرى مسجلة بالاسم</td>
    </tr>
    <tr>
      <td><code>listTools() / countTools()</code></td>
      <td>عرض / عد الأدوات المسجلة</td>
    </tr>
    <tr>
      <td rowspan="4"><strong>الهويات والصلاحيات</strong></td>
      <td><code>getUserIdentity(jid, db, conn)</code></td>
      <td>الحصول على اسم/رقم/مالك/منطقة المرسل</td>
    </tr>
    <tr>
      <td><code>checkGroupAdminOrOwner(groupJid)</code></td>
      <td>التحقق مما إذا كان المرسل مشرفاً أو مالكاً</td>
    </tr>
    <tr>
      <td><code>readGroupSettings(groupJid)</code></td>
      <td>قراءة إعدادات المجموعة من التخزين الدائم</td>
    </tr>
    <tr>
      <td><code>readOwnerList()</code></td>
      <td>عرض قائمة مالكي البوت المسجلين</td>
    </tr>
    <tr>
      <td rowspan="2"><strong>التخزين الدائم ("العقل")</strong></td>
      <td><code>loadBrain() / saveBrain(brain)</code></td>
      <td>قراءة/كتابة ai-brain.json</td>
    </tr>
    <tr>
      <td><code>ensureBrainGroupSlot(brain, jid)</code></td>
      <td>التأكد من وجود فتحة المجموعة في العقل</td>
    </tr>
    <tr>
      <td rowspan="10"><strong>الويب والوسائط</strong></td>
      <td><code>searchWebGrounded(query)</code></td>
      <td>بحث ويب دقيق وموجه</td>
    </tr>
    <tr>
      <td><code>captureWebsiteScreenshot(url)</code></td>
      <td>أخذ لقطة شاشة لصفحة ويب</td>
    </tr>
    <tr>
      <td><code>fetchWebsiteHtmlFallback(url)</code></td>
      <td>جلب كود HTML الخام للصفحة</td>
    </tr>
    <tr>
      <td><code>peekFetchBuffer(url, headers)</code></td>
      <td>معاينة ملف Buffer من رابط</td>
    </tr>
    <tr>
      <td><code>peekfetchVideoBuffer(url, maxBytes, headers)</code></td>
      <td>معاينة فيديو Buffer من رابط</td>
    </tr>
    <tr>
      <td><code>detectPlatform(url)</code></td>
      <td>اكتشاف المنصة (يوتيوب/تيك توك/الخ)</td>
    </tr>
    <tr>
      <td><code>peekAnalyzeWithVision(mediaItems, platform, url, context)</code></td>
      <td>تحليل الوسائط باستخدام نموذج الرؤية</td>
    </tr>
    <tr>
      <td><code>buildMediaPart(m)</code></td>
      <td>استخراج صورة/فيديو/صوت من الرسالة</td>
    </tr>
    <tr>
      <td><code>fetchSocialMulti(url)</code></td>
      <td>أداة تحميل شاملة لوسائل التواصل</td>
    </tr>
    <tr>
      <td><code>downloadUserImageAsUrl(m)</code></td>
      <td>رفع صورة المستخدم والحصول على رابطها</td>
    </tr>
    <tr>
      <td rowspan="3"><strong>أدوات الملفات والبيانات</strong></td>
      <td><code>readFileToolCore(file_path, offset)</code></td>
      <td>المنطق الأساسي لأداة "قراءة ملف"</td>
    </tr>
    <tr>
      <td><code>buildSimpleDiff(oldStr, newStr)</code></td>
      <td>إنشاء مقارنة نصية بين نصين</td>
    </tr>
    <tr>
      <td><code>parseDbKeyPath(key_path)</code></td>
      <td>تحليل مسار المفتاح للوصول لقاعدة البيانات</td>
    </tr>
    <tr>
      <td rowspan="7"><strong>تنفيذ الإضافات (متقدم/داخلي)</strong></td>
      <td><code>resolvePlugin(command)</code></td>
      <td>العثور على الإضافة المطابقة للأمر</td>
    </tr>
    <tr>
      <td><code>resolveCustomPrefixPlugin(rawInput)</code></td>
      <td>نفس الشيء، للأوامر ذات البادئة المخصصة</td>
    </tr>
    <tr>
      <td><code>execPluginCommand(command, argsStr, opts)</code></td>
      <td>تشغيل أمر/إضافة موجودة في البوت</td>
    </tr>
    <tr>
      <td><code>execEval(code, opts)</code></td>
      <td>تقييم كود JS خام (للمالك فقط، خطير)</td>
    </tr>
    <tr>
      <td><code>classifyPluginRisk(name, plugin)</code></td>
      <td>تصنيف مستوى خطر الإضافة</td>
    </tr>
    <tr>
      <td><code>accessLabel(level) / riskBadge(level)</code></td>
      <td>مساعِدتا ملصقات/شارات مستوى الخطر</td>
    </tr>
    <tr>
      <td><code>pluginRequirements(plugin)</code></td>
      <td>الحصول على متطلبات الوصول للإضافة</td>
    </tr>
    <tr>
      <td><code>getDangerousDocReason(m)</code></td>
      <td>التحقق مما إذا كانت الرسالة/الملف يبدو خطيراً</td>
    </tr>
    <tr>
      <td rowspan="8"><strong>معالجة الأخطاء والأنظمة الداخلية</strong></td>
      <td><code>handleError(conn, m, err, pluginName)</code></td>
      <td>معالج/مبلغ الأخطاء المركزي</td>
    </tr>
    <tr>
      <td><code>isTransientApiError(err)</code></td>
      <td>التحقق مما إذا كان خطأ API مؤقتاً</td>
    </tr>
    <tr>
      <td><code>getApiKeys() / getNextKey() / rotateKey() / resetRateLimit(jid)</code></td>
      <td>إدارة مجموعة مفاتيح API</td>
    </tr>
    <tr>
      <td><code>normalizeApiKeys(input)</code></td>
      <td>تنسيق/تنظيف قائمة مفاتيح API الخام</td>
    </tr>
    <tr>
      <td><code>getPersonality()</code></td>
      <td>الحصول على شخصية البوت/موجه النظام</td>
    </tr>
    <tr>
      <td><code>MODELS</code></td>
      <td>خريطة لنماذج الذكاء الاصطناعي المتاحة</td>
    </tr>
    <tr>
      <td><code>setCurrentContext(...)</code></td>
      <td>إدارة الحالة/الدور الداخلي</td>
    </tr>
    <tr>
      <td><code>hasPending() / confirmPending() / cancelPending()</code></td>
      <td>إدارة الحالة/الدور الداخلي</td>
    </tr>
  </tbody>
</table>

</div>
</details>

<sub>
  
```javascript
/*
  ctx()   -> يُرجع حالة المحادثة الحالية (دائماً محدثة، مدعومة بوحدة داخلية في mcp.js). الحقول الشائعة:
               - currentJid : معرف المحادثة/المستخدم الذي يرسل الرسالة
               - conn       : اتصال واتساب النشط (لإرسال الرسائل يدوياً)
               - isOwner    : صحيح إذا كان المرسل هو مالك البوت
               - isROwner   : صحيح إذا كان المرسل "مالكاً حقيقياً"
               - timezone   : المنطقة الزمنية المهيئة للمرسل، مثل "Africa/Cairo"

  الأدوات تستورد المساعدات مباشرة من '../mcp.js'. لا توجد مشكلة استيراد دائري:
  mcp.js لا يستورد الملفات في ./tools statically -- بل يحملها بـ import() ديناميكيًا،
  لذا فإن استيراد mcp.js من ملف أداة آمن تماماً.
*/
import { ctx, searchWebGrounded } from '../mcp.js'

export default [
    {
        name: 'check_weather',
        description: 'التحقق من الطقس لمدينة محددة. استخدمه عندما يسأل المستخدم عن الطقس، مثلاً: "ما هو الطقس في القاهرة؟"',
        parameters: {
            city: { type: 'string', description: 'اسم المدينة، مثل "القاهرة"', required: true }
        },
        execute: async ({ city }) => {
            const { currentJid } = ctx()
            if (!currentJid) return 'سياق المحادثة غير متاح'

            // const result = await searchWebGrounded(`current weather in ${city}`)

            return `الطقس في ${city}: مشمس، 30 درجة مئوية`
        }
    }
]
```

</sub>
</details>

*✥┉┉┉┉┉┉⦉💬⦊┉┉┉┉┉┉✥*

<details>
   <summary align=left><b>💬 أنواع الرسائل | Message types</b></summary>
   <p align=center>──────────────</p>

<details> <summary>📖 الرسائل الأساسية (Basic)</summary>
  <sub>
    
```javascript
conn.reply(m.chat, 'مرحباً بالعالم!', m)

/** @الوسائط
رابط — 'https://example.com/audio.mp3'
محلي — '/path/to/video.mp4'

@الخيارات
إرسال كمستند — { document:true }
إرسال كملاحظة صوتية — { ptt: true }
**/
conn.sendFile(m.chat, media, "file.png", "مرحباً بالعالم!", m, { options })

conn.sendContact(m.chat, [
  ['201234567890', 'PHANTOM X'],
  ['209876543210', 'Shadow']
], m)

conn.react(m.chat, '👍', m.key)
```
</sub></details>

<details> <summary>📍 الموقع التفاعلي (Location)</summary>
  <sub>
  
```javascript
conn.sendLocUrl(
        m.chat,
        'https://example.com/thumb.jpg',
        'العنوان',
        'الموقع',
        'النص',
        'التذييل',
        'https://example.com',
         m )
```

</sub></details>

<details> <summary>🖼️ معاينة الروابط (Url Preview)</summary>
  <sub>
    
```javascript
conn.sendUrlPreview(
  m.chat,
  'https://example.com/thumb.jpg',
  'https://example.com مرحباً بالعالم!',
  'عنوان المعاينة',
  'وصف الرابط',
  'IMAGE',   // true للجودة العالية
  m
)
```
</sub></details>

<details> <summary>🛒 العروض الدائرية (Carousel)</summary>
  <sub>
    
```javascript
conn.sendButton(m.chat, {
    text: 'تفاعل مع العروض الدائرية!',
    footer: 'PHANTOM X',
    cards: [
        {
            image: { url: './path/to/image.jpg' },
            caption: 'الصورة 1',
            footer: 'تذييل 1',
            nativeFlow: [{ text: 'المصدر', url: 'https://example.com', useWebview: true }]
        },
        {
            image: { url: 'https://example.com/image.png' },
            caption: 'الصورة 2',
            footer: 'تذييل 2',
            ltoText: 'عرض جديد!',
            ltoCode: 'PHANTOM',
            ltoUrl: 'https://example.com',
            nativeFlow: [{ text: 'المصدر', url: 'https://example.com' }]
        }
    ]
}, m)
```
</sub></details>

<details> <summary>🔖 أزرار NativeFlow</summary>
  <sub>

```javascript
conn.sendButton(m.chat, {
    image: { url: './path/to/image.jpg' },
    caption: 'تفاعلي!',
    footer: 'بوتي',
    optionText: 'اختر الخيارات',
    optionTitle: 'اختر الخيارات',
    ltoText: 'PHANTOM X',
    ltoCode: 'Phantom bot',
    ltoUrl: 'https://example.com',
    nativeFlow: [
        { text: '👋🏻 تحية', id: '#Greeting' },
        { text: '📞 اتصال', call: '20123456789' },
        { text: '📋 نسخ', copy: 'Phantom bot' }, 
        { text: '🌐 المصدر', url: 'https://example.com', useWebview: true },
        {
            text: '📋 اختيار',
            sections: [
                { title: '✨ القسم 1', rows: [{ header: '', title: '🏷️ كوبون', description: '', id: '#CouponCode' }] },
                { title: '✨ القسم 2', highlight_label: '🔥 شائع', rows: [{ header: '', title: '💭 سر', description: '', id: '#Secret' }] }
            ],
        }
    ]
}, m)
```
</sub></details>

<details> <summary>🗓️ رسائل الذكاء الاصطناعي الغنية (AI Rich)</summary>
  <sub>

```javascript
await conn.aiRich()
    .setTitle('رسالة ذكاء اصطناعي غنية') 
    .addText('[رابط](https://example.com)\nاستشهاد [](https://example.com)')
    .addImage('https://example.com/image.png')
    .addCode('javascript', `console.log('Hello World')`)
    .addHtml(["<html>مرحباً</html>", "تبويب 1"], ["<html>أهلاً</html>", "تبويب 2"]),
    .addTable([
        ['الاسم', 'PHANTOM X'],
        ['النبذة', 'أنا مطور'],
        ['العمر', 'غير محدد']
    ])
    .addSource([['https://example.com/favicon.ico', 'https://example.com', 'المصدر']])
    .addTip('نصيحة')
    .addSuggest(['متابعة', 'إلغاء'])
    .send(m.chat, { quoted: m })
      
 // شريط تقدم متحرك
 await conn.aiRich()
  .addProcess("جاري التحميل...")
  .send(m.chat)
```
</sub></details>

<details> <summary>📦 الملصقات (Sticker)</summary>
  <sub>

```javascript
/** @الوسائط
رابط — 'https://example.com/image.png'
محلي — '/path/to/image.png'
**/

// ملصق
conn.sendSticker(m.chat, media, { packname: "PHANTOM", author: "X" }, m)
 
// حزمة ملصقات
conn.sendStickerPack(m.chat, {
   cover: { url: media },
   stickers: [
      { data: { url: media } },
      { data: { url: media } },
   ],
   name: 'حزمة ملصقاتي',
   publisher: 'ناشر الحزمة',
   description: 'وصف الحزمة'
})
```
</sub></details>

<details> <summary>📞 المكالمات (Call)</summary>
  <sub>

```javascript
/** @الوسائط
رابط — 'https://example.com/audio.mp3'
محلي — '/path/to/video.mp4'
**/

// صوت
const call = await conn.call('20123456789', media)

// فيديو
const call = await conn.call('20123456789', media, {
  videoSource: media
})

// صامت
const call = await conn.call('20123456789', 'silence')

// صوت كمكالمة فيديو
const call = await conn.call('20123456789', Audio, {
  isVideo: true
})
```
</sub></details>
</details>

*✥┉┉┉┉┉┉⦉⚙️⦊┉┉┉┉┉┉✥*
  
<details>
   <summary><b>🚀 التثبيت والتشغيل | Install and Run</b></summary><br>

<table align="center">
  <tbody>
    <tr>
      <td rowspan="4"><b>المتطلبات | REQUIREMENTS</b></td>
      <td><b>الخادم</b></td>
      <td colspan="2">500MB RAM, 1GB Storage, Support IP:Port <br> <code>-</code></td>
    </tr>
    <tr>
      <td><b>NodeJS</b></td>
      <td colspan="2">24 أو أعلى <br> <code>pkg install nodejs</code></td>
    </tr>
    <tr>
      <td><b>Python</b></td>
      <td colspan="2">Python 3.10+ <br> <code>pkg install python</code></td>
    </tr>
    <tr>
      <td><b>FFMPEG</b></td>
      <td colspan="2">أحدث إصدار <br> <code>pkg install ffmpeg</code></td>
    </tr>
  </tbody>
</table>

<sub align=left>

```bash
$ git clone https://github.com/PHANTOM-X/PHANTOM-X.git
$ mv .env.example .env
$ nano .env
$ node .
```
</sub>

<div align=center>

  <a href="#"><img height="25" align=right src="https://img.shields.io/badge/Size-100_MB-black?style=for-the-badge"/> </a>
  
  <a href="#"><img height="25" align=left src="https://img.shields.io/badge/Deploy-black?style=for-the-badge&logo=4chan&logoColor=blue"/></a>

</div>

</details>

<br>
<div align=center>

*✥┉┉┉┉┉┉⦉🖤⦊┉┉┉┉┉┉✥*
<h3> ☠︎ حقوق الملكية والتطوير | Developed by ☠︎ </h3>
<h2> 𝕻𝕳𝕬𝕹𝕿𝕺𝕸 𝕏 | 𝕾𝖍𝖆𝖉𝖔𝖜 </h2>
<p> "الكود هو شعري، والظلال هي مساحتي." </p>
*✥┉┉┉┉┉┉⦉⚔️⦊┉┉┉┉┉┉✥*

</div>