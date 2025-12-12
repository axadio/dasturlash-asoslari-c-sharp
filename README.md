---


---

<h1 id="kitob-nomi">Kitob nomi</h1>
<h2 id="bob-kirish">1-bob: Kirish</h2>
<h3 id="kompyuter-nima">1.1. Kompyuter nima?</h3>
<h4 id="misollar">1.1.1. Misollar</h4>
<p><strong>Bu qalin matn</strong></p>
<p><em>Bu kursiv matn</em></p>
<p><em><strong>Bu qalin+kursiv</strong></em></p>
<p><s>O‘chirilgan matn</s></p>
<ul>
<li>Birinchi</li>
<li>Ikkinchi
<ul>
<li>Ichki element</li>
</ul>
</li>
</ul>
<ol>
<li>Boshlash</li>
<li>O‘rnatish</li>
<li>Ishga tushirish<br>
<code>Console.WriteLine()</code></li>
</ol>
<pre class=" language-csharp"><code class="prism  language-csharp"><span class="token keyword">using</span> System<span class="token punctuation">;</span>

<span class="token keyword">class</span> <span class="token class-name">Program</span>
<span class="token punctuation">{</span>
    <span class="token keyword">static</span> <span class="token keyword">void</span> <span class="token function">Main</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
    <span class="token punctuation">{</span>
        Console<span class="token punctuation">.</span><span class="token function">WriteLine</span><span class="token punctuation">(</span><span class="token string">"Salom, dunyo!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
    <span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<blockquote>
<p>Bu yerda muhim izoh yoziladi.<br>
<img src="rasm.png" alt="Rasm nomi"><br>
<a href="https://learn.microsoft.com">Microsoft C# documentation</a></p>
</blockquote>

<table>
<thead>
<tr>
<th>Tur</th>
<th>Tavsif</th>
</tr>
</thead>
<tbody>
<tr>
<td>int</td>
<td>Butun son</td>
</tr>
<tr>
<td>double</td>
<td>O’nlik son</td>
</tr>
<tr>
<td>string</td>
<td>Matn</td>
</tr>
</tbody>
</table><hr>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> no</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" checked="true" disabled="">  yes</li>
</ul>
<h1 id="dasturlash-asoslari-c">Dasturlash asoslari: C#</h1>
<h2 id="muallif-asadbek-soyibjonov"><strong>Muallif:</strong> Asadbek Soyibjonov</h2>
<p><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br></p>
<h2 id="kirish">Kirish</h2>
<p>Dasturlashni o‘rganish har bir insonda turlicha boshlanadi — kimdir webdan, kimdir mobil dasturlardan, boshqalar esa algoritmlardan yoki tizim dasturlashdan kirishadi. Qaysi nuqtadan boshlash to‘g‘ri degan savolga esa yagona javob yo‘q; hammasi o‘quvchining maqsadiga, qiziqishiga va kelajakdagi yo‘nalishiga bog‘liq.</p>
<p>Ko‘pchilik uchun dasturlashning asosiy tushunchalarini o‘rganishda <strong>C++ tili</strong> tavsiya qilinadi, chunki u past darajadagi ishlash tamoyillarini ham yaxshi ko‘rsatib bera oladi. Ammo bu kitobda biz <strong>C tili yoki C++</strong> emas, balki <strong>C#</strong> tiliga e’tibor qaratamiz. Xo‘sh, nega aynan C#?</p>
<p>Dastlab dasturlash tillari kompyuterga buyruq berish, ma’lum jarayonlarni avtomatlashtirish uchun yaratilgan. Eng qadimgi keng tarqalgan tillardan biri — <strong>C</strong> tili edi. U bugungi zamonaviy tillardagi ko‘plab qulayliklarga ega bo‘lmagan, procedural, ya’ni “berilgan vazifani bajar” tamoyiliga asoslangan edi. Keyinchalik unga obyektga yo‘naltirilgan dasturlash imkoniyatlarini qo‘shish maqsadida <strong>C+Objects</strong> tilini yaratishdi va u vaqt o‘tib <strong>C++</strong> nomini oldi.</p>
<p>Vaqt o‘tishi bilan texnologiya rivojlandi, ehtiyojlar kengaydi, dasturchilar esa yanada qulay, xavfsiz va qudratli til izlashardi. Nihoyat, 2000-yilda Microsoft tomonidan yangi til — <strong>C#</strong> taqdim qilindi. Ko‘p jamoalarda uni “Microsoft Java” deb tanqid qilishgan bo‘lsa-da, aslida C# C oilasiga mansub bo‘lib, unga bir qator zamonaviy funksiyalar, kuchli sintaksis va kengaytirilgan imkoniyatlar qo‘shilgan edi. Dastlab tilning nomi <strong>C cool</strong> bo‘lishi rejalashtirilgan, biroq mualliflik huquqi masalalari sabab nom <strong>C# (C sharp)</strong> deb tasdiqlandi.</p>
<p>Endi “asosiy tushuncha uchun nega C# tanlandi?” degan savolga javob beramiz.</p>
<p><strong>C++ bilan boshlash ko‘pchilik uchun qiyin bo‘ladi.</strong> Murakkab sintaksis, qo‘lda xotira boshqaruvi, ko‘p texnik tafsilotlar boshlang‘ich bosqichda o‘rganishni og‘irlashtiradi. C# esa shu qiyinchiliklarni ancha soddalashtiradi, tushunarliroq, zamonaviyroq va ixcham yozish imkonini beradi. Shu sababli boshlang‘ich bosqichda C# bilan ishlash yoqimli va samarali bo‘ladi.</p>
<p>Bugungi kunda C# yordamida <strong>Windows ilovalari, veb-saytlar, mobil ilovalar, hamda ayniqsa o‘yinlar</strong> ishlab chiqiladi. Hozirgi AAA o‘yinlarning katta qismi yoki Unity platformasida, yoki .NET texnologiyalari yordamida tayyorlanadi. Buning sababi — C#ning keng qamrovli ekotizimi, tez ishlab chiqish imkoniyatlari va “<strong>bir marta yozing — ko‘p platformada ishlating</strong>” falsafasidir.</p>
<p>Shu bilan, biz C# bilan dasturlash asoslarini o‘rganishni boshlaymiz.</p>

