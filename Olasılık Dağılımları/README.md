# Statistics_documentation


<h1>Olasılık Dağılımları</h1>

<h2>Kesikli Olasılık Dağılımları:</h2>
<ul>
<li>Bernoulli Dağılımı</li>
<li>Binom Dağılımı</li>
<li>Poisson Dağılımı</li>
<li>Geometrik Dağılım</li>
<li>Hipergeometrik Dağılım</li>
<li>Negatif Binom Dağılımı</li>
<li>Multinomiyal Dağılım</li>
</ul>
<h2>Sürekli Olasılık Dağılımları:</h2>
<ul>
<li>Normal Dağılım (Gauss Dağılımı)</li>
<li>Üniform Dağılım</li>
<li>Beta Dağılımı</li>
<li>Gamma Dağılımı</li>
<li>Exponential Dağılımı</li>
<li>Weibull Dağılımı</li>
<li>Pareto Dağılımı</li>
<li>Log-Normal Dağılımı</li>
<li>Cauchy Dağılımı</li>
<li>Student-t Dağılımı</li>
<li>F Dağılımı</li>
<li>Laplace Dağılımı</li>
</ul>
    
<h1>Olasılık Dağılımları</h1>

<h2>Kesikli Olasılık Dağılımları:</h2>
<ol>
<li><strong>Bernoulli Dağılımı:</strong>
<ul>
<li>Bir deneyde sadece iki olası sonuç (başarılı/başarısız, evet/hayır) bulunan deneyler için kullanılır.</li>
<li>Bu dağılım, bir denemenin başarı olasılığını (p) ve başarısızlık olasılığını (q = 1 - p) temsil eder.</li>
<li>Tek bir deneme sonucu için olasılık kütle fonksiyonu (PMF) şu şekildedir: P(X=x) = p^x * q^(1-x) (x=0,1)</li>
</ul>
</li>
<li><strong>Binom Dağılımı:</strong>
<ul>
<li>Bağımsız n deneme sonucunda r başarı sayısını modellemek için kullanılır.</li>
<li>Bu dağılım, belirli bir deneme sayısı n, başarı olasılığı p ve başarısızlık olasılığı q = 1 - p ile karakterizedir.</li>
<li>Olasılık kütle fonksiyonu (PMF) şu şekildedir: P(X=r) = C(n, r) * p^r * q^(n-r)</li>
</ul>
</li>
<li><strong>Poisson Dağılımı:</strong>
<ul>
<li>Belirli bir zaman aralığında nadir olarak gerçekleşen olayların sayısını modellemek için kullanılır.</li>
<li>Poisson Dağılımı, sürekli zaman aralıkları ve düşük olasılıklı nadir olaylarla ilgilenir.</li>
<li>Olayların ortalama frekansını λ ile ifade eder.</li>
<li>Olasılık kütle fonksiyonu (PMF) şu şekildedir: P(X=k) = (e^(-λ) * λ^k) / k!</li>
</ul>
</li>
<li><strong>Geometrik Dağılım:</strong>
<ul>
<li>Bağımsız denemelerde başarı olasılığı p olan bir olayın ilk başarıya ulaşma denemesinin olasılığını modellemek için kullanılır.</li>
<li>Olasılık kütle fonksiyonu (PMF) şu şekildedir: P(X=k) = (1 - p)^(k-1) * p (k=1,2,3,...)</li>
</ul>
</li>
<li><strong>Hipergeometrik Dağılım:</strong>
<ul>
<li>Rastgele örneklemelerde, popülasyondan çekilen belirli örneklem sayılarıyla ilgili problemleri modellemek için kullanılır.</li>
<li>N: Toplam popülasyon, K: İyi durumdaki toplam öğe sayısı, n: Çekilecek örneklem sayısı.</li>
<li>Olasılık kütle fonksiyonu (PMF) şu şekildedir: P(X=k) = (C(K, k) * C(N-K, n-k)) / C(N, n) (k=min(K,n), min(K,n)+1, ..., max(0,n-K)+min(K,n))</li>
</ul>
</li>
<li><strong>Negatif Binom Dağılımı:</strong>
<ul>
<li>Başarıları saymak için kesikli bir olasılık dağılımıdır.</li>
<li>Bir denemede başarı olasılığı p olan bir olayı düşünelim. r başarıya ulaşmak için kaç deneme yapmamız gerektiğini (başarısızlık sayısını) modellemek için kullanılır.</li>
<li>Olasılık kütle fonksiyonu (PMF) şu şekildedir: P(X=n) = C(n-1, r-1) * p^r * q^(n-r)</li>
</ul>
</li>
<li><strong>Multinomiyal Dağılım:</strong>
<ul>
<li>Birden fazla kategoride birden fazla kez deney yapıldığında kullanılır.</li>
<li>Örneğin, bir zarı üç kere atıp her sonuç için olasılıkları modellemek için kullanılabilir.</li>
<li>Olasılık kütle fonksiyonu (PMF) şu şekildedir: P(X1=x1, X2=x2, ..., XK=xK) = (n! / (x1! * x2! * ... * xK!)) * (p1^x1) * (p2^x2) * ... * (pK^xK)</li>
</ul>
</li>
</ol>

<h1>Sürekli Olasılık Dağılımları</h1>
<h2>Sürekli Olasılık Dağılımları:</h2>
<ol>
<li><strong>Normal Dağılım (Gauss Dağılımı):</strong>
<ul>
<li>En yaygın kullanılan sürekli olasılık dağılımıdır.</li>
<li>Merkezi limit teoremi gereği pek çok doğal süreçte rastgele değişkenlerin dağılımları genellikle normal dağılıma yakınsar.</li>
<li>Ortalama (μ) ve standart sapma (σ) ile tanımlanır.</li>
<li>Tek zirveli ve simetrik bir dağılımdır.</li>
<li>Çan şeklinde bir grafik ve negatif sonsuza ve pozitif sonsuza doğru uzanan kuyruklara sahiptir.</li>
</ul>
</li>
<li><strong>Üniform Dağılım:</strong>
<ul>
<li>Belirli bir aralıkta tüm değerlerin eşit olasılıkla gerçekleştiği dağılımdır.</li>
<li>A ve B gibi iki parametre ile tanımlanır ve değerler arasında homojen bir dağılım gösterir.</li>
<li>Tüm olasılık yoğunluk fonksiyonları (PDF) eşit olduğundan grafiği düz bir çizgidir.</li>
</ul>
</li>
<li><strong>Beta Dağılımı:</strong>
<ul>
<li>Olasılık değerlerinin aralığını modellemek için kullanılır ve genellikle oranları temsil etmek için tercih edilir.</li>
<li>İki şekillendirme parametresi (α ve β) ile tanımlanır.</li>
<li>0 ile 1 arasındaki değerler için kullanılır ve çeşitli şekillere sahip olabilir.</li>
</ul>
</li>
<li><strong>Gamma Dağılımı:</strong>
<ul>
<li>Pozitif sürekli değişkenlerin modellenmesi için kullanılır ve özellikle süreç zamanları gibi alanlarda sıkça kullanılır.</li>
<li>İki parametre (α ve β) ile tanımlanır.</li>
<li>Eksponeksiyon dağılımının genelleştirilmiş halidir.</li>
</ul>
</li>
<li><strong>Exponential Dağılımı:</strong>
<ul>
<li>İlk olayın gerçekleşmesi arasındaki sürenin modellemesinde kullanılır.</li>
<li>Yarıçaplanma süresi (λ) olarak bilinen tek bir parametresi vardır.</li>
<li>Belleksiz (memoryless) dağılım olarak bilinir, yani gelecekte bir olayın gerçekleşme süresi geçmiş olayların gerçekleşme süresine bağlı değildir.</li>
</ul>
</li>
<li><strong>Weibull Dağılımı:</strong>
<ul>
<li>Ömrü modellemek için kullanılan bir dağılımdır ve özellikle güvenilirlik analizlerinde yaygın olarak kullanılır.</li>
<li>İki parametre (λ ve k) ile tanımlanır ve farklı şekillere sahip olabilir.</li>
</ul>
</li>
<li><strong>Pareto Dağılımı:</strong>
<ul>
<li>Zenginlik ve gelir dağılımlarını modellemek için kullanılır.</li>
<li>Pareto prensibine dayalı olarak zenginlerin daha zengin, yoksulların daha yoksul olma eğilimine işaret eder.</li>
</ul>
</li>
<li><strong>Log-Normal Dağılımı:</strong>
<ul>
<li>Logaritma dönüşümü sonrası normal dağılıma benzer, ancak asıl değişkenin üzerindeki pozitif değerler için kullanılır.</li>
<li>Finansal piyasalarda ve stok fiyatları gibi alanlarda sıkça kullanılır.</li>
</ul>
</li>
<li><strong>Cauchy Dağılımı:</strong>
<ul>
<li>Ortalaması ve varyansı tanımsız olduğundan diğer dağılımlardan farklıdır.</li>
<li>Dışarıdaki etkilerden dolayı bazen güvenilmez olabilir.</li>
</ul>
</li>
<li><strong>Student-t Dağılımı:</strong>
<ul>
<li>Küçük örneklem büyüklüklerinde kullanılan ve normal dağılıma benzeyen bir dağılımdır.</li>
<li>Daha geniş kuyruklara sahiptir, bu nedenle normal dağılıma göre daha ağırdır.</li>
<li>T-testi ve diğer hipotez testlerinde kullanılır.</li>
</ul>
</li>
<li><strong>F Dağılımı:</strong>
<ul>
<li>İki varyansı karşılaştırmak için kullanılan bir dağılımdır.</li>
<li>Özellikle regresyon analizinde, ANOVA testlerinde ve varyans analizlerinde kullanılır.</li>
</ul>
</li>

<li><strong>Laplace Dağılımı:</strong>
<ul>
<li>İki taraflı bir üniform dağılımın oluşturduğu bir dağılımdır.</li>
<li>Sıçramalar veya diğer ani değişimlerin modellemesi için kullanılır.</li>
</ul>
</li>
