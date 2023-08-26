# Voice of Customer
<p align="center">
<img src= "https://github.com/kikkalo/MADT8101/assets/115805661/f4872226-a4bc-4043-be73-5b997dfddf40" width="300" />
<img src= "https://github.com/kikkalo/MADT8101/assets/115805661/8a307fae-c7f0-4aef-9231-28ed90cd9de4" width="225" />
</p>

## Data
* [Butterfly Thai Perfume](https://shopee.co.th/butterflythaiperfume.official/5829923780)
  
  ![image](https://github.com/kikkalo/MADT8101/assets/115805661/10fba19f-8073-4cc8-9ced-3513fa05fa02)


## Method
* Topic Modeling with LDA
* Document clustering using K-mean and Cosine Similarity

## Results
* Topic Modeling with LDA

   ![image](https://github.com/kikkalo/MADT8101/assets/115805661/d461ffdb-335c-4669-84e3-196e79841b5e)

  คีย์เวิร์ดที่เหมือนกันจากทั้ง 3 กลุ่มคือ "กลิ่น", "หอม"
  แสดงว่า ลูกค้ามีความคิดเห็นเชิงบวกต่อกลิ่นของน้ำหอม

* K-mean

  ![image](https://github.com/kikkalo/MADT8101/assets/115805661/f8080188-c139-4cc5-a771-e2c2a6a3377f)

* Cosine Similarity

  ![image](https://github.com/kikkalo/MADT8101/assets/115805661/e008dfb8-e248-45c9-9a38-492c1d27e98d)

  เนื่องจากวิธี Cosine Similarity มีการแจกแจงในแต่ละคลัสเตอร์ได้เข้าใจและชัดเจนกว่า จึงเลือกตั้งชื่อคลัสเตอร์จากวิธี Cosine Similarity เป็นดังนี้

  Cluster ID : 0
  Group Name: "Longevity of Scent"
  
  Cluster ID : 1
  Group Name: "Product Quality and Fragrance"
  
  Cluster ID : 2
  Group Name: "Purchase Experience and Pricing"
