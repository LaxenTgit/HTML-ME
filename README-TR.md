# 🔐 SecureAuth Challenge

**Difficulty:** Easy  
**Platform:** GitHub Pages (yep, this is a free CTF)  
**Category:** Web / Steganography / Brute Force

---

## 🎯 Ne Bu?

TryHackMe ve Hack The Box dışında, kendini denemek isteyen **web pentester'lar** için tasarlanmış basit bir CTF challenge'ı.

Eski bir sunucuda unutulmuş admin paneli bulundu. Görevin: giriş yap ve flag'i al.

---

## 🚩 Kurallar

- SQL injection yok — tamamen client-side auth
- Kullanıcı adı kodda yok, ama "görünürde" bir yerde
- Şifre her oturumda değişiyor, 6 haneli ve sadece rakamlardan oluşuyor
- Brute force serbest (hatta bekleniyor :D)
- XSS Attack serbest :muscle:

---

## 💡 İpuçları

1. Source kodu incele
2. Görsel her zaman sadece görsel değildir
3. 000000'dan başlayıp denemekten vazgeçme

---

## 🛠️ Gerekli Araçlar

- Tarayıcı DevTools (Ctrl+U)
- `zsteg`, `StegSolve`, veya kendi Python script'in
- Hydra / Burp Suite / wfuzz
- Sabır

---

## 🚀 Başla

[https://laxentgit.github.io/HTML-ME/](https://laxentgit.github.io/HTML-ME/)

---

## 🏆 Flag Formatı

flag{xxxxx_xxxxx_xxxxx_xxxxxx_XXXXXX}

---

Built with ☕ by [@LaxenTgit](https://github.com/LaxenTgit)
