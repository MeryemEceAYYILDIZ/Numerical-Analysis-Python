<div align="center">
  <a href="#english">🇬🇧 English</a> | <a href="#türkçe">🇹🇷 Türkçe</a>
</div>

---

<h2 id="english">🧮 Numerical Analysis & Algorithm Design (Python)</h2>

This repository contains my academic and practical implementations of Numerical Analysis methods. The focus of these projects is to translate complex mathematical theorems into functional Python algorithms without relying on built-in math libraries or external packages. 

Alongside the raw code, this repository includes digitized handwritten mathematical proofs, showcasing a strong theoretical foundation in calculus, matrix algebra, and algorithmic error calculation.

### Projects & Algorithms Overview

#### Python Implementations (Algorithms from Scratch)
* **Taylor Series & Truncation Error (`TaylorSerisi.py`):** Calculates polynomial approximations for trigonometric functions, computing iterative steps, factorials, and the resulting truncation error dynamically[cite: 29].
* **Bisection Method (`Odev2`):** Custom root-finding algorithm dividing intervals to solve non-linear equations like $x^3-2x^2-5=0$ and $x^3+4x^2-10=0$ over 4 strictly controlled iterations[cite: 30, 31].
* **Newton-Raphson Method (`Odev3`):** Tangent-based root finding for exponential functions like $f(x)=4e^{-0.5x}-x$[cite: 33]. This project also includes an analytical edge-case demonstration where the method fails and oscillates around a local minimum for $f(x)=x^{1/3}$, proving algorithmic limitations[cite: 32].
* **Basic Lab Exercises (`UygulamaDersindeCozulenler`):** Fundamental Python exercises solving introductory mathematical models.

#### Theoretical Mathematical Analysis (PDF Notes)
* **Hessian Matrix (`Odev4.pdf`):** Handwritten derivations and step-by-step solutions of the Hessian Matrix (second-order partial derivatives) for multi-variable scalar functions[cite: 35].
* **Iterative Error/Cost Calculation (`Odev5.pdf`):** Handwritten calculations computing hypothesis $\Theta$ updates over 4 iterations, laying the manual mathematical groundwork for Gradient Descent and Linear Regression optimizations[cite: 36].
* **Finite Differences & Pascal's Triangle (`Odev6.pdf`):** A research assignment exploring the relationship between forward/backward finite difference formulas and the binomial coefficients of Pascal's Triangle[cite: 34].

### Technologies & Concepts
* **Language:** Python 3 (Pure Python, no external mathematical libraries used).
* **Mathematical Concepts:** Root Finding, Iterative Convergence, Partial Derivatives (Hessian), Truncation Errors, Finite Differences, Gradient Updates.


---

<h2 id="türkçe">🧮 Sayısal Analiz ve Algoritma Tasarımı (Python)</h2>

Bu depo, Sayısal Analiz (Numerical Analysis) metotlarının akademik ve pratik uygulamalarını içermektedir. Projelerin temel odak noktası, hazır matematik kütüphaneleri kullanılmadan, karmaşık matematiksel teoremlerin çalışan Python algoritmalarına dönüştürülmesidir.

Kodların yanı sıra, çok değişkenli kalkülüs, matris cebiri ve algoritmik hata hesaplamalarına dair güçlü bir teorik altyapıyı kanıtlayan el yazısı matematik ispatlarının dijitalleştirilmiş (PDF) hallerini de barındırmaktadır.

### Projeler ve Algoritmalar

#### Python Uygulamaları (Sıfırdan Algoritmalar)
* **Taylor Serisi ve Kesme Hatası (`TaylorSerisi.py`):** Fonksiyonların polinom yaklaşımlarını, iteratif adımları, faktöriyel hesaplamalarını ve oluşan kesme hatasını (truncation error) dinamik olarak hesaplayan algoritma[cite: 29].
* **İkiye Bölme (Bisection) Metodu (`Odev2`):** $x^3-2x^2-5=0$ ve $x^3+4x^2-10=0$ gibi doğrusal olmayan denklemlerin köklerini, belirli aralıkları daraltarak 4 iterasyonda bulan özel algoritma[cite: 30, 31].
* **Newton-Raphson Metodu (`Odev3`):** $f(x)=4e^{-0.5x}-x$ gibi üstel fonksiyonlar için türev tabanlı kök bulma[cite: 33]. Proje ayrıca, $f(x)=x^{1/3}$ denklemi üzerinden algoritmanın yerel minimum etrafında salınım yaparak (diverge) başarısız olduğu sınır durumlarının (edge-case) ispatını da içerir[cite: 32].
* **Laboratuvar Çözümleri (`UygulamaDersindeCozulenler`):** Temel matematiksel modellerin çözüldüğü Python alıştırmaları.

#### Teorik Matematik Analizleri (PDF Notları)
* **Hesse Matrisi / Hessian Matrix (`Odev4.pdf`):** Çok değişkenli skaler fonksiyonlar için ikinci dereceden kısmi türevlerden oluşan Hesse Matrisi'nin el yazısı türetimleri ve adım adım örnek çözümleri[cite: 35].
* **İteratif Hata ve Güncelleme Hesaplamaları (`Odev5.pdf`):** Gradyan İniş (Gradient Descent) ve Doğrusal Regresyon optimizasyonlarının manuel matematiksel altyapısını oluşturan, 4 iterasyonluk $\Theta$ hipotez güncellemelerinin el yazısı hesaplamaları[cite: 36].
* **Sonlu Farklar ve Pascal Üçgeni (`Odev6.pdf`):** İleri ve geri yönlü sonlu fark formüllerinin Pascal Üçgeni'ndeki binom katsayıları ile olan matematiksel ilişkisini inceleyen araştırma ödevi[cite: 34].

### Kullanılan Teknolojiler ve Konseptler
* **Dil:** Python 3 (Saf Python, harici kütüphane kullanılmamıştır).
* **Matematiksel Konseptler:** Kök Bulma, İteratif Yakınsama, Kısmi Türevler (Hessian), Kesme Hataları, Sonlu Farklar, Gradyan Güncellemeleri.
