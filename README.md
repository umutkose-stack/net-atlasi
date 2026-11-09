# Net Atlası · öğrenci ve veli sayfası

Öğrenciler ve veliler, öğretmenden aldıkları kullanıcı adı ve şifreyle yalnızca kendi deneme sonuçlarını görür.
Öğretmen, panelde görünen **yönetici girişi** ile bütün öğrencileri salt okunur olarak görür.

- `index.html`: giriş ve sonuç sayfası
- `data.json`: şifreli sonuçlar (AES-GCM, PBKDF2-SHA256 150.000 tur). Her öğrencinin kaydı kendi şifresiyle, yönetici kaydı da yönetici şifresiyle şifrelenir; şifresiz okunamaz.

## Güncelleme

1. Net Atlası panelinde **Veri ve Excel → GitHub öğrenci sitesine aktar → data.json indir**.
2. Bu repoda **Add file → Upload files** ile `data.json`'u yükle ve **Commit changes**'e bas.
