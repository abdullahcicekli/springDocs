# Java SpringBoot Dökümantasyonu

Bu dökümantasyon "Java Spring Boot" notlarımı içermektedir.


## 1-) Merhaba Dünya !

Her programlama dilinde başlangıç projesi olan "Merhaba Dünya!" programı.
https://start.spring.io/ sitesinden spring projemizi başlatabiliriz.

Dependencies'den "Spring Web" seçerek projemizi oluşturabiliriz.

```
package com.hhaydikodlayalim.hkhelloworld;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController // API için gerekli spring tool'u
@RequestMapping("/hello") //Path Belirtilir.
public class MerhabaAPI {

    @GetMapping // Http Metodu Belirlenir.
    public String merhaba(){ // Method Oluşturulur.
        return "Merhaba"; // Return Edilecek işlemler yapılır.
    }
}
```


## Faydalı Linkler

-	https://mvnrepository.com/
-	https://start.spring.io/
