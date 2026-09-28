# JojosC

Türkçe, statik ve mobil uyumlu karakter atlası. `index.html` dosyasını tarayıcıda açın. Karakter kayıtları `characters.js` içindeki `window.JOJO_CHARACTERS` dizisindedir; yeni karakter eklemek için mevcut bir kaydı kopyalayıp `id`, Part, doğrulanmış alanlar ve olayları güncelleyin. Doğrulanmayan biyografik alanları boş bırakmayın; `Kaynaklarda belirtilmemiş` veya `Bilinmiyor` olarak yazın.

## Görsel ekleme

Karakter portrelerini `assets/characters/` klasörüne koyun. Varsayılan dosya adı karakter `id`’siyle aynı olmalı ve `.webp` uzantısı kullanmalı. Örnek: `jodio-joestar.webp`. `characters.js` kaydında `image: 'assets/characters/daha-farkli-dosya.png'` belirterek başka ad veya format seçebilirsiniz. Kayda eklenen görseller ana sayfadaki açılış sekansında da sıralı, alt/üst dönüşümlü animasyonla kullanılır. Görseller henüz eklenmediğinde dekoratif arka plan yerinde kalır.

Ana sayfa arka planında kullanıcının sağladığı All Star Battle R görselinden Jonathan, Joseph, Jotaro, Josuke, Giorno, Jolyne, Johnny ve Josuke Higashikata (Part 8) portre şeritleri çıkarılmıştır. Sekiz portre aynı klasörde durur; bu dosyalar karakter profillerinde de görünür.

Şimdilik beş Stand görseli `assets/stands/` klasöründedir: Stone Free, Gold Experience, Crazy Diamond, Star Platinum ve Hermit Purple. Görseller karakter profilindeki Stand kartında ve açılan Stand panelinde gösterilir.

## Veri ve kaynak ilkesi

Arşiv manga/anime canon’undaki veya Araki’nin açıkça doğruladığı bilgiler için hazırlanmıştır. Kayıtların `source` alanını ilgili manga Part’ı ve varsa resmî JoJo portalı ile güncel tutun. Part 9 sürmekte olduğundan yeni gelişmeleri aynı dosyada eklemek yeterlidir. Part 7–9 manga Part’larıdır.

## Erişilebilirlik

Aramada `/` ile odaklanabilir, ok tuşlarıyla sonuç seçebilir ve `Enter` ile açabilirsiniz. `Escape` panelleri kapatır. Hareket azaltma tercihi animasyonu kapatır.

