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
<hr>
<h2 id="til-sintaksisi">Til sintaksisi</h2>
<p><strong>C#</strong> dasturlash tili <strong>katta va kichik harflarni farqlaydi</strong>. Ya’ni <code>KattaHarf</code> va <code>kattaharf</code> — <strong>ikki xil nom</strong> hisoblanadi. Shu sababli o‘zgaruvchi, funksiya va sinf nomlarini yozishda harflar registriga doimo e’tibor berish kerak.</p>
<p>O‘zgaruvchilarni nomlashda odatda ikki xil uslub qo‘llaniladi:</p>
<ul>
<li>
<p><strong>pastki chiziq</strong> yordamida:</p>
<p><code>mening_yoshim</code></p>
</li>
<li>
<p><strong>bir nechta so‘zdan iborat nomlarda har bir so‘zni bosh harf bilan yozish</strong> (CamelCase yoki PascalCase):</p>
<p><code>meningYoshim</code></p>
</li>
</ul>
<p>Bu uslublar kodni o‘qilishi va tushunilishini ancha osonlashtiradi.</p>
<h3 id="oddiy-c-dasturiga-misol">Oddiy C# dasturiga misol</h3>
<p>Quyida C# tilida yozilgan eng oddiy dastur namunasi keltirilgan:</p>
<pre class=" language-c"><code class="prism # language-c">namespace  MyApp 
<span class="token punctuation">{</span> 
	public  class  Program 
	<span class="token punctuation">{</span> 
		public  <span class="token keyword">static</span>  <span class="token keyword">void</span>  <span class="token function">Main</span><span class="token punctuation">(</span><span class="token punctuation">)</span>
    <span class="token punctuation">{</span>
			Console<span class="token punctuation">.</span><span class="token function">WriteLine</span><span class="token punctuation">(</span><span class="token string">"Salom, Dunyo!"</span><span class="token punctuation">)</span><span class="token punctuation">;</span>
		<span class="token punctuation">}</span>
	<span class="token punctuation">}</span>
<span class="token punctuation">}</span>
</code></pre>
<p>Bu dastur ekranga <strong>“Salom, Dunyo!”</strong> matnini chiqaradi.</p>
<p>Agar kodni soddaroq ko‘rinishda yozmoqchi bo‘lsak, quyidagi ifoda ham yetarli bo‘ladi:</p>
<p><code>Console.WriteLine("Salom, Dunyo!");</code></p>
<h3 id="muhim-eslatmalar">Muhim eslatmalar</h3>
<ul>
<li>
<p><strong>Kalit so‘zlar</strong> (<code>namespace</code>, <code>class</code>, <code>public</code>, <code>static</code>, <code>void</code> va hokazo) <strong>kichik harflarda</strong> yoziladi.</p>
</li>
<li>
<p><strong>Standart sinflar va metodlar</strong> esa odatda <strong>bosh harf bilan</strong> boshlanadi (<code>Console</code>, <code>WriteLine</code>).</p>
</li>
<li>
<p>Ushbu yozish qoidalariga rioya qilish — C# da <strong>yaxshi amaliyot (best practice)</strong> hisoblanadi va keyinchalik ham shunga amal qilish tavsiya etiladi.</p>
</li>
</ul>
<h3 id="console.writeline-haqida"><code>Console.WriteLine</code> haqida</h3>
<p><code>Console.WriteLine()</code> metodi qavs ichidagi qiymatni <strong>ekranga chiqarish</strong> uchun ishlatiladi.</p>
<p>Masalan:</p>
<p><code>Console.WriteLine(1 + 1);</code></p>
<p>Natija:</p>
<p><code>2</code></p>
<p>Yoki matn chiqarish uchun:</p>
<p><code>Console.WriteLine("Bu matn");</code></p>
<p>Shuningdek, o‘zgaruvchilarni ham chiqarish mumkin:</p>
<pre><code>int son = 10;
Console.WriteLine(son);
</code></pre>
<h2 id="o‘zgaruvchi-turlari">O‘zgaruvchi turlari</h2>
<p><strong>C#</strong> dasturlash tili bir nechta asosiy <strong>o‘zgaruvchi turlariga (data types)</strong> ega. Quyidagi jadvalda eng ko‘p ishlatiladigan turlar keltirilgan:</p>

<table>
<thead>
<tr>
<th>Tur</th>
<th>Tavsif</th>
</tr>
</thead>
<tbody>
<tr>
<td><code>int</code></td>
<td>Butun sonlar</td>
</tr>
<tr>
<td><code>float</code></td>
<td>Kasrli son (kam aniqlik)</td>
</tr>
<tr>
<td><code>double</code></td>
<td>Kasrli son (yuqori aniqlik)</td>
</tr>
<tr>
<td><code>decimal</code></td>
<td>Juda yuqori aniqlikdagi sonlar</td>
</tr>
<tr>
<td><code>string</code></td>
<td>Matn (satr)</td>
</tr>
<tr>
<td><code>char</code></td>
<td>Bitta belgi</td>
</tr>
</tbody>
</table><p>Bu turlarni o‘rganishdan oldin <strong>o‘zgaruvchi</strong> va <strong>o‘zgarmas (konstanta)</strong> tushunchalarini ko‘rib chiqamiz.</p>
<hr>
<h3 id="o‘zgaruvchilar-va-o‘zgarmaslar">O‘zgaruvchilar va o‘zgarmaslar</h3>
<p><strong>O‘zgaruvchi</strong> — dastur davomida e’lon qilinib, uning qiymatini <strong>o‘zgartirish mumkin</strong> bo‘lgan xotira joyidir.</p>
<p>Masalan:</p>
<p><code>int yosh = 18; yosh = 19;</code></p>
<p>Bu yerda <code>yosh</code> o‘zgaruvchisining qiymati dastur davomida o‘zgartirildi.</p>
<p><strong>O‘zgarmaslar (konstantalar)</strong> esa faqat <strong>bir marta e’lon qilinadi</strong> va keyinchalik ularning qiymatini o‘zgartirib bo‘lmaydi. Dastur davomida qiymati <strong>doim bir xil</strong> bo‘lib qoladi.</p>
<p><code>const int MaksimalYosh = 100;</code></p>
<hr>
<h3 id="char-tipi-haqida"><code>char</code> tipi haqida</h3>
<p><code>char</code> — <strong>bitta belgini</strong> saqlash uchun mo‘ljallangan turdir:</p>
<p><code>char belgi = 'A';</code></p>
<p>Texnik jihatdan <code>char</code> ham <strong>raqamli tur</strong> hisoblanadi. Har bir belgi kompyuter xotirasida <strong>son ko‘rinishida</strong> saqlanadi.</p>
<h4 id="bit-va-bayt-tushunchasi">Bit va bayt tushunchasi</h4>
<ul>
<li>
<p><strong>Bit</strong> — eng kichik axborot birligi (<code>0</code> yoki <code>1</code>)</p>
</li>
<li>
<p><strong>Bayt</strong> — 8 ta bitdan iborat</p>
</li>
</ul>
<p>Demak:</p>
<p><code>1 bayt = 8 bit</code></p>
<p>8 ta bit yordamida:</p>
<p><code>2⁸ = 256 ta turli kombinatsiya</code></p>
<p>hosil qilish mumkin.</p>
<p>Shu kombinatsiyalar yordamida belgilar maxsus kodlar orqali ifodalanadi. Masalan:</p>
<ul>
<li>
<p><code>'A'</code> belgisi ma’lum bir <strong>sonli kodga</strong></p>
</li>
<li>
<p>bu kod esa <strong>ikkilik sanoq sistemasida</strong> <code>0</code> va <code>1</code> lar ketma-ketligiga mos keladi</p>
</li>
</ul>
<p>Xuddi shu prinsip sonlar uchun ham amal qiladi.</p>
<hr>
<h3 id="sonli-turlar-haqida-qisqacha">Sonli turlar haqida qisqacha</h3>
<ul>
<li>
<p><strong><code>int</code></strong><br>
4 bayt (32 bit) joy egallaydi va <strong>butun sonlarni</strong> saqlaydi.</p>
</li>
<li>
<p><strong><code>float</code></strong><br>
Kasrli sonlar uchun ishlatiladi, lekin aniqligi pastroq.</p>
</li>
<li>
<p><strong><code>double</code></strong><br>
<code>float</code> ga nisbatan <strong>aniqligi yuqori</strong>, ko‘pincha standart tanlov hisoblanadi.</p>
</li>
<li>
<p><strong><code>decimal</code></strong><br>
Juda yuqori aniqlik talab qilinadigan holatlarda (masalan, <strong>moliyaviy hisob-kitoblar</strong>) ishlatiladi.</p>
</li>
</ul>
<p>Misol:</p>
<p><code>int a = 10; double b = 3.14; decimal c = 99.99m;</code></p>

