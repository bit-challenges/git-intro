# 🚀 GitHub įvadas: Fork, Pull Request ir bendradarbiavimas

Sveiki, BIT studentai! 🎉 Ši repozitorija skirta praktikuoti GitHub bendradarbiavimo įrankius

## 🛠 Užduotis

1. **Fork'inkite šią repozitoriją** į savo GitHub paskyrą.
2. **Klonuokite savo fork į savo kompiuterį**:
```
git clone https://github.com/JŪSŲ_GITHUB_USERNAME/git-intro.git
```
3. **Sukurkite naują branch su savo vardu**:
```
git checkout -b vardas-pavarde
```
4. **Atidarykite ```studentai/students.json```** ir pridėkite savo informaciją (žiūrėkite pavyzdį žemiau).
5. **Commit ir push pakeitimus:**
```
git add .
git commit -m "Pridėjau savo informaciją"
git push origin vardas-pavarde
```
6. **Sukurkite Pull Request** per GitHub.
7. **Laukite patvirtinimo! ✅**

## 👀 Pavyzdys: kaip užpildyti students.json
```
[
    {
        "name": "Simas Jankūnas",
        "group": "54",
        "github": "https://github.com/SmartLoom/"
    },
    {
        "name": "Jūsų vardas, pavardė",
        "group": "Jūsų BIT grupės numeris / pavadinimas",
        "github": "Jūsų GitHub paskyros nuoroda"
    }
]
```
#### 🎯 SVARBU: Neperrašykite kitų studentų duomenų, o tiesiog pridėkite savo įrašą į masyvą.