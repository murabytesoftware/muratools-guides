# MuraTools: free browser tools

A documentation and examples hub for [MuraTools](https://muratools.netlify.app/), with free utilities for PDF, images, text and developer workflows. No account is required to use the available tools.

دليل وأمثلة لأدوات [MuraTools](https://muratools.netlify.app/) المجانية للـPDF والصور والنصوص والمطورين، من غير حساب لاستخدام الأدوات المتاحة.

> This is documentation, not a source-code release. The live website is the place to use the tools. / ده مستودع توثيق، مش إصدار للكود المصدري. استخدم الأدوات من الموقع.

## Start with these workflows / جرّب المهام دي

### HTML to Markdown

[Open the converter / افتح المحول](https://muratools.netlify.app/tools/html-to-markdown/)

Convert headings, paragraphs, links, lists and code blocks locally in your browser. Active content such as scripts and iframes is omitted. This is a content converter, not a lossless round trip.

حوّل العناوين والفقرات والروابط والقوائم وأجزاء الكود داخل المتصفح. المحتوى النشط زي السكريبتات وiframes بيتم استبعاده. التحويل مش بيحافظ على كل تفاصيل HTML الأصلية.

Try / جرّب:

```html
<ul><li>Parent<ul><li>Child</li></ul></li><li>Second</li></ul>
```

The child should remain nested under Parent, with Second as a separate item. Check the rendered Markdown before publishing it.

المفروض Child يفضل عنصر فرعي تحت Parent، وSecond يبقى عنصر منفصل. راجع عرض Markdown قبل النشر.

### Image compression / ضغط الصور

[Open Image Compressor / افتح ضاغط الصور](https://muratools.netlify.app/tools/image-compressor/)

Choose output format and quality, optionally resize, then compare the result before saving. JPEG/WebP compression can be lossy. PNG output is lossless, so its quality slider does not reduce file size. AVIF support depends on the browser.

اختار صيغة الإخراج والجودة، وغيّر المقاس لو محتاج، وبعدها قارن النتيجة قبل الحفظ. ضغط JPEG وWebP ممكن يقلل التفاصيل. إخراج PNG بدون فقد، وعشان كده شريط الجودة مش بيقلل حجمه. دعم AVIF بيعتمد على المتصفح.

## Privacy and limits / الخصوصية والحدود

These two tools process supported input locally in your browser. Review each tool's own notes before using other workflows. Large files may exceed device or browser limits. Keep your originals and verify exported results.

الأداتين دول بيعالجوا المدخلات المدعومة محليًا في المتصفح. راجع شرح أي أداة تانية قبل استخدامها. الملفات الكبيرة ممكن تتجاوز قدرة الجهاز أو المتصفح. احتفظ بالأصل وراجع الناتج.

## Project links / روابط المشروع

- [MuraTools](https://muratools.netlify.app/)
- [Murabyte](https://murabyte.netlify.app/)
- [Commercial products on Gumroad / المنتجات المدفوعة](https://murabyte.gumroad.com/)

Free-to-use access does not grant a source-code license. This repository does not contain paid product source. Examples may use synthetic data. No performance or business outcome is guaranteed.

الاستخدام المجاني مش ترخيص للكود المصدري. المستودع مش بيحتوي على كود منتجات مدفوعة. الأمثلة ممكن تكون ببيانات تجريبية. مفيش ضمان لنتيجة أداء أو دخل معين.

Prepared with AI assistance. / أُعد بمساعدة الذكاء الاصطناعي.
