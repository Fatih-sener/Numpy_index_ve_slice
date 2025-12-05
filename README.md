# NumPy Dizilerinde İndeksleme ve Dilimleme (Slicing)

Bu script, tek boyutlu bir NumPy dizisi (vektör) üzerinde veri erişim yöntemlerini demonstre eder. Python listelerine benzer şekilde NumPy da **0-tabanlı indeksleme** (zero-based indexing) kullanır.

## Kapsanan Teknikler
Kod içerisinde aşağıdaki erişim yöntemleri örneklenmiştir:
* **Single Element Indexing (`vector[i]`):** Belirli bir indisteki elemana erişim.
* **Slicing (`vector[start:stop]`):** Belirli bir aralıktaki verileri alma (Bitiş indisi dahil değildir).
* **Negative Indexing (`vector[-1]`):** Diziye sondan erişim sağlama.
* **Strided Slicing (`vector[start:stop:step]`):** Belirli bir adım sayısı (artış miktarı) ile veriyi atlayerek alma.
