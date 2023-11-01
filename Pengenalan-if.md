## 1.1 Latar Belakang
        Go Fashion adalah aplikasi online store, Aplikasi ini hampir sama dengan shopee bedanya adalah jika shopee serba ada, 
        Nah Go Fashion ini media khusus untuk para user mengeksplor fashion dari ujung kepala sampai ujung kaki.
        
## 1.2 Deskripsi Teknologi Informasi
        Teknologi Informasi itu sebuah media bagi manusia dalam mengembangkan wawasan, media berkomunikasi antar manusia, 
        media bagi pelajar dalam mengembangkan keilmuan dan pengetahuannya karna tidak cukup sampai di kelas saja untuk belajar, 
        juga media bagi manusia untuk berkreasi dan berinovasi dalam teknologi informasi. 
        
## 1.3 Branding
      Merk : Go Fashion
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
      Customer|Membuat akun|Bisa membuat profile di akun pribadi|⭐⭐⭐⭐
      Customer|Mengikuti akun toko|Mendapat kabar terbaru tentang toko|⭐⭐⭐⭐
      SELLER|mengikuti customer|Membuka akses agar customer tidak tertinggal kabar tentang toko|⭐⭐⭐
      
      
## 3. Struktur Data 
      Untuk mmebuat bermacam grafik (struktur data) menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html]
      ```mermaid
      erDiagram
          SELLER ||--|{ PRODUK : MEMPOSTING
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
          CUSTOMER ||--|{ SELLER : MENGUNJUNGI_TOKO
        ```
              
## 4. Arsitektur Sistem

      Database-Amazon Web Server-Java-Figma-Java swing-Netbeans
      
## 5. Teknologi, Library, dan Framework
      Teknologi : - react native
                  -         
      Library :
      Framework :
## 6. Desain User Experience dan User Interface
