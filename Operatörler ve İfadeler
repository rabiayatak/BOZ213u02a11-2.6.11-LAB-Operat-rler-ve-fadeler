hour = int(input("Starting time (hours): "))
mins = int(input("Starting time (minutes): "))
dura = int(input("Event duration (minutes): "))

# 1. Adım: Tüm zamanı dakika cinsinden toplayalım
toplam_dakika = mins + dura

# 2. Adım: Bu dakikaların içindeki fazladan saatleri bulalım (tam bölme yapıyoruz)
ekstra_saat = toplam_dakika // 60

# 3. Adım: Kalan dakikaları bulalım (mod alıyoruz)
kalan_dakika = toplam_dakika % 60

# 4. Adım: Saatleri toplayalım
toplam_saat = hour + ekstra_saat

# 5. Adım: Saat 24'ü geçerse diye 24'e bölümünden kalanı alalım
son_saat = toplam_saat % 24

# 6. Adım: Sonucu ekrana yazdıralım
print(son_saat, ":", kalan_dakika, sep="")
