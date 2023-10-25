## 1.1 Latar Belakang
        MFN STORE adalah aplikasi online store, Aplikasi ini hampir sama dengan shopee bedanya adalah jika shopee serba ada, 
        Nah MFN STORE ini media khusus untuk para user mengeksplor fashion dari ujung kepala sampai ujung kaki.
        
## 1.2 Deskripsi Teknologi Informasi
        Teknologi Informasi itu sebuah media bagi manusia dalam mengembangkan wawasan, media berkomunikasi antar manusia, 
        media bagi pelajar dalam mengembangkan keilmuan dan pengetahuannya karna tidak cukup sampai di kelas saja untuk belajar, 
        juga media bagi manusia untuk berkreasi dan berinovasi dalam teknologi informasi. 
        
## 1.3 Branding
      Merk : MFN STORE
      Tagline : The best deals are just one click away!
      Campaign : Aplikasi untuk menemukan ide fashion  
      Target User : -user 13+
                            - Untuk user yang bingung ide untuk fashion 
                            - Untuk user yang ingin menanyakan tentang produk pada seller
                            
## 2. User Story


      Sebagai|Saya ingin|Sehingga|Level Prioritas 
      ---|---|---|---
      Customer|Mencari casual fashion|Bisa mendapatkan ide fashion setiap harinya|⭐⭐⭐⭐⭐
      Customer|Chat seller|Bisa konsultasi tentang masalah produk|⭐⭐⭐⭐⭐
      Customer|Mencari fashion untuk liburan|Bisa mendapatkan ide fashion saat liburan|⭐⭐⭐⭐
      Seller|Chat customer|Bisa membalas chat customer|⭐⭐⭐ 
      Seller|Memposting produk|Bisa menjual produk|⭐⭐⭐⭐
      Customer|Menyimpan dulu produk|Bisa menyimpan dulu idenya di dalam keranjang dan mencari yang lebih cocok|⭐⭐⭐
      
## 3. Struktur Data 
      Untuk mmebuat bermacam grafik (struktur data) menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html]
      ```mermaid
      erDiagram
          SELLER ||--o{ PRODUK : MEMPOSTING
          SELLER {
            String username
            String password
            String custNumber
            String orderAddress
          }
          CUSTOMER ||--|{ PRODUK : MEMBELI
          CUSTOMER {
            String username
            String orderNumber
            String deliveryAddress
          }
          PRODUK {
            String produkName 
            int quality
            float pricePerItem
          }
          SELLER ||--|{ CUSTOMER : MENGUNJUNGI_TOKO
        ```
              
## 4. Arsitektur Sistem

      Database-
      
## 5. Teknologi, Library, dan Framework
      Teknologi : - react native
                  -         
      Library :
      Framework :
## 6. Desain User Experience dan User Interface

      slide 1 : https://ibb.co/kG1094m
      slide 2 : https://ibb.co/MR9yzxs
      slide 3 : https://ibb.co/C2HVRt4
      slide 4 : https://ibb.co/mNdtxKn
