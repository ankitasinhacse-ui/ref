হাদিসের API
in Chapter Endpoints
- Sahih Bukhari: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Bukhari/Chapter/1.json` here 1 to 97 jsons
- Sahih Muslim: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Muslim/Chapter/1.json` here 1 to 56 jsons
- Sunan Abu Dawood: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/AbuDaud/Chapter/1.json`   here 1 to 43 jsons
- Sunan Ibn Majah: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Ibne-Mazah/Chapter/1.json`  here 1 to 37 jsons
- Sunan An-Nasa'i: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Al-Nasai/Chapter/1.json`  here 1 to 50 jsons
- Sunan At-Tirmidhi: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/At-tirmizi/Chapter/1.json`  here 1 to 46 jsons

also add endpoints where all hadith will shows 
in Hadith Endpoints
- Sahih Bukhari: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Bukhari/hadith/1.json` to  here 1 to 7563 jsons
json structure:

```
{
  "hadith": {
    "hadith_id": 1,
    "narrator": "‘আলক্বা",
    "bn": "আমি ‘উমর ই",
    "ar": "حَدَّثَنَا الْحُمَيْدِيُّ عَبْد مَا هَاجَرَ إِلَيْهِ",
    "grade_id": 2,
    "grade": "সহিহ হাদিস",
    "grade_color": "#46B891",
    "note": null,
    "chapter": {
      "chapter_number": "1"
    }
  }
}

```



- Sahih Muslim: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Muslim/hadith/1.json` here 1 to 7453 jsons


```

{
  "hadith": {
    "hadith_id": 3,
    "narrator": "ইয়াহ্‌ইয়া বি",
    "bn": "তাঁরা উভয়ে ব",
    "ar": "وَحَدَّثَشَيْئًا ‏.",
    "grade_id": 2,
    "grade": "সহিহ হাদিস",
    "grade_color": "#46B891",
    "note": null,
    "chapter": {
      "chapter_number": "1"
    }
  }
}

```




- Sunan Abu Dawood: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/AbuDaud/hadith/1.json` here 1 to 5274 jsons

```

    {
      "hadith": {
        "hadith_id": 1,
        "narrator": "মুগী",
        "bn": "নবী।",
        "ar": "حَدَّثَنَلنَّبِيّبَ أَبْعَدَ ‏.‏",
        "grade_id": 12,
        "grade": "হাসান সহিহ",
        "grade_color": "#46B891",
        "note": null,
        "chapter": {
          "chapter_number": "1"
        }
      }
    }

```



- Sunan Ibn Majah: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Ibne-Mazah/hadith/1.json` here 1 to 4341 jsons
- 

```

    {
      "hadith": {
        "hadith_id": 1,
        "narrator": "(রাঃ)",
        "bn": "রত থাকো। [১]",
        "ar": "حهُوا».",
        "grade_id": 2,
        "grade": "সহিহ হাদিস",
        "grade_color": "#46B891",
        "note": "সহীহাহ ৮৫০।",
        "chapter": {
          "chapter_number": "0"
        }
      }
    }

```



- Sunan An-Nasa'i: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Al-Nasai/hadith/1.json` here 1 to 5758 jsons



```


    {
      "hadith": {
        "hadith_id": 1,
        "narrator": "আবূ হুরায়রা (রাঃ)",
        "bn": "তার হাত রাতে কোথায় পৌঁছেছিল।",
        "ar": " صحيح ق ",
        "grade_id": 1,
        "grade": "নির্ণীত নয়",
        "grade_color": "#F0AD4E",
        "note": null,
        "chapter": {
          "chapter_number": "1"
        }
      }
    }



```




Sunan At-Tirmidhi: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/At-tirmizi/hadith/1.json` here 1 to 3956 jsons



```


    {
      "hadith": {
        "hadith_id": 1,
        "narrator": "ইবনু উমার (রাঃ)",
        "bn": "ইবনু মাজাহ- (২৭২)",
        "ar": "حَدَّثَنَانِ ‏.‏",
        "grade_id": 2,
        "grade": "সহিহ হাদিস",
        "grade_color": "#46B891",
        "note": "মাইর আল-হুযালী।",
        "chapter": {
          "chapter_number": "1"
        }
      }
    }

```







## here all hadith meta data which u can implement in the hadith page as well, i also added demo structure of each meta 
- Sahih Bukhari: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Bukhari/Meta/bukhari.json` 
structure of json

```


      "1": {
        "title": "ওহীর সূচনা অধ্যায়",
        "hadis_range": "১ - ৭"
      },
      "2": {
        "title": "ঈমান",
        "hadis_range": "৮ - ৫৮"
      },

```


- Sahih Muslim: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Muslim/Meta/muslim.json` 

```

      "1": {
        "title": "ঈমান",
        "hadis_range": "১ - ৪২১"
      },
      "2": {
        "title": "তাহারাত (পবিত্রতা)",
        "hadis_range": "৪২২ - ৫৬৫"
      },

```



- Sunan Abu Dawood: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/AbuDaud/Meta/abudaud.json`


```


      "1": {
        "title": "পবিত্রতা অর্জন",
        "hadis_range": "০১ – ৩৯০"
      },
      "2": {
        "title": "সালাত (নামায)",
        "hadis_range": "৩৯১ – ১১৬০"
      },


```



- Sunan Ibn Majah: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Ibne-Mazah/Meta/ibnemajah.json`  


```


      "0": {
        "title": "ভূমিকা",
        "hadis_range": "১ - ২৬৬"
      },
      "1": {
        "title": "পবিত্রতা ও তার সুন্নাতসমূহ",
        "hadis_range": "২৬৭ - ৬৬৬"
      },

```



- Sunan An-Nasa'i: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/Al-Nasai/Meta/nasa'i.json` 


```


      "1": {
        "title": "পবিত্রতা",
        "hadis_range": "০১ - ৩২৪"
      },
      "2": {
        "title": "পানির বর্ণনা",
        "hadis_range": "৩২৫ - ৩৪৭"
      },

```



- Sunan At-Tirmidhi: `https://cdn.jsdelivr.net/gh/md-rifatkhan/hadithbangla@main/At-tirmizi/Meta/at-tirmizi.json` 


```


      "1": {
        "title": "পবিত্রতা",
        "hadis_range": "১-১৪৮"
      },
      "2": {
        "title": "সালাত (নামায)",
        "hadis_range": "১৪৯-৪৫১"
      },

```



