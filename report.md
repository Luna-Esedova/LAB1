# Layihə Hesabatı

## 1. Ümumi məlumat

Bu iş üç ayrı Python proqramından ibarətdir. Proqramlar istifadəçi daxil etmələrini qəbul edir və sadə şərt operatorları və siyahılar vasitəsilə nəticə göstərir.

## 2. BMI Hesablama

**Məqsəd:** Çəki və boy göstəricilərinə əsasən Bədən Kütlə İndeksini (BMI) hesablamaq.

**İş prinsipi:**
1. İstifadəçidən çəkini kiloqramla (`kg`) alır.
2. Boyu metr ilə (`hm`) alır.
3. `BMI = kg / (hm * hm)` düsturu ilə nəticəni hesablayır.
4. `if/elif` şərtləri ilə kateqoriya çap edir.

**Mövcud kateqoriyalar:** `Underweight`, `Normal Weight`, `Overweight`, `Obese`.

**Müşahidə:** Kodda `BMI == 18.5`, `24.9` ilə `25.0` arasındakı dəyərlər və bəzi sərhəd halları üçün heç bir nəticə çap olunmaya bilər. Boy sıfır daxil edilərsə, sıfıra bölmə xətası baş verər.

## 3. Chinese Zodiac Sign

**Məqsəd:** Doğum ilinə əsasən Çin bürcünü göstərmək.

**İş prinsipi:**
1. İstifadəçidən doğum ilini tam ədəd kimi alır.
2. `birth_year % 12` hesablayır.
3. Qalıq dəyərinə görə 12 addan birini çap edir: Monkey, Rooster, Dog, Pig, Rat, Ox, Tiger, Rabbit, Dragon, Snake, Horse və Sheep.

**Müşahidə:** Proqram yüklənmiş kodda verilən qalıq uyğunluğunu birbaşa tətbiq edir. Çin Yeni ili yanvarın və ya fevralın əvvəlində başladığı üçün yalnız doğum ilinə əsaslanan bu sadələşdirilmiş yanaşma bəzi doğum tarixlərində ənənəvi Çin bürcü ilə fərqlənə bilər.

## 4. Find Birthday

**Məqsəd:** Beş dəstdə verilən suallara istifadəçinin cavabları ilə 1–31 aralığındakı doğum gününü müəyyən etmək.

**İş prinsipi:**
1. Proqram beş ədəd siyahısını göstərir.
2. Hər siyahı üçün istifadəçidən `1` (bəli) və ya `0` (xeyr) cavabı istəyir.
3. Cavab `1` olduqda müvafiq olaraq 1, 2, 4, 8 və ya 16 əlavə edir.
4. Sonda hesablanan günü çap edir.

**Müşahidə:** Bu üsul ikilik say sisteminin çəkilərindən istifadə edir. Düzgün cavablar verildikdə 1–31 aralığında nəticə əldə edilə bilər. Proqram daxil edilən cavabların yalnız `0` və ya `1` olmasını ayrıca yoxlamır.

## 5. İstifadə olunan Python anlayışları

- `input()` — istifadəçidən məlumat almaq.
- `int()` və `float()` — daxil edilən dəyərləri ədəd tipinə çevirmək.
- `if/elif` — şərtə uyğun qərar vermək.
- `%` — bölmədən qalığı hesablamaq.
- Siyahılar (`list`) — günlər qruplarını saxlamaq.
- `print()` — nəticələri ekrana çıxarmaq.

## 6. Nəticə

Bu üç proqram Python-un əsas anlayışlarını — istifadəçi daxil etmələrini, hesablamaları, şərt operatorlarını və siyahıları — nümayiş etdirir. Daha etibarlı istifadə üçün BMI sərhədləri və giriş yoxlamaları təkmilləşdirilə bilər.
