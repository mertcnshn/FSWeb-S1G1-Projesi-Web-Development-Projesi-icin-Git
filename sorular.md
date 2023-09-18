# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?

Git, yazılım geliştirme süreçlerinde kullanılan, hız odaklı, distributed bir sürüm kontrol ve kaynak kod yönetim sistemidir. 

2. Git ile GitHub arasında ne fark var?

Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz gelişmiş portal/bulut benzeri sistemdir.

3. Neden bir branch oluşturuyoruz?

Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projenin o anki halini bozmamak için branch kullanılabilir.

4. Pull Request'in amacı nedir?

Fork edilen projenin üzerinde çalışılarak yapılan değişiklikler, projenin sahibine pull request şeklinde gönderilebilir. Pull request olarak göndermenin anlamı; proje üzerinde değişiklik yaptım, sen de bu değişiklikleri onaylayarak  projene merge et demek anlamına gelir. Bazı değişiklikleri yaptıktan sonra, bir pull request talebinde bulunarak bu kodu bir şubeye geri gönderebilirsiniz. Kısacası Pull request talebi, temelde branch’den sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.

5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?

Git’te branch değiştirmek için checkout komutunu kullanılır. Git checkout dedikten sonra branch adımızı yazmamız yeterli. Eğer branch adımızı hatırlamıyorsak git branch yazarak bütün branchleri listelenebilir. Main branchine geçmek için git checkout main komutu kullanılabilir.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Git fetch komutunda veriler sadece indirilirken, git pull komutunda veriler indirilir ve yerel depoda yüklemeler yapılır. Git fetch komutu veriyi getirme işlevini yerine getirirken, git pull komutu veriyi getirme ve birleştirme işlevini yerine getirir. Git'de merge işlemi ise başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir.

7. Merge conflict nedir?

Merge conflict genellikle aynı dosya üzerinde değişiklikler yapıldığında ortaya çıkar. Aynı satırda yapılan değişiklikler veya takımdaki bir kişinin bir satırı silmesi durumunda ortaya çıkabilir. Bu durumda Git dosyayı conflicted (çakışmalı) olarak işaretler. Git status komutunu çalıştırıldığında Git size branch'inde entegre edilmemiş dosyalar olduğu yazacaktır.

8. Merge conflict'i nasıl çözeriz?

Çakışmayı düzeltmek için dosyamızı açıp çakışan satırları düzeltmemiz gerekiyor. Dosyamızın içeriğinin ne olacağına karar verip kaydettikten sonra normal bir commit işlemi ile çakışmayı çözme işlemini tamamlanır.
