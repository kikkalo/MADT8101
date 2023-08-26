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
  
  ```
  Cluster ID : 0

  Most common words include : [('สินค้า', 4), ('ดี', 4), ('คุณภาพ', 1), ('กลิ่น', 1), ('ติด', 1), ('ทน', 1), ('ราคา', 1), ('ก', 1), ('กกรอ', 1), ('ห่อ', 1)]
  
  Cluster ID : 1
  
  Most common words include : [('กลิ่น', 6), ('หอม', 5), ('จาง', 3), ('ติดทน', 2), ('ก', 1), ('กกฉีด', 1), ('เลิก', 1), ('งาน', 1), ('หอมหอม', 1), ('ลอง', 1)]
  
  Cluster ID : 2
  
  Most common words include : [('ดี', 3), ('สินค้า', 2), ('ส่งเร็ว', 1), ('แพ็คมา', 1), ('มส่ง', 1), ('ไว', 1), ('ราคา', 1), ('ช้อปปี้ไลฟ์', 1), ('คุ้ม', 1), ('อยกลิ่น', 1)]
  ```
  
* Cosine Similarity
  
  ```
  Cluster ID : 0

  Most common words include :[('กลิ่น', 2), ('จาง', 2), ('ติด', 2), ('คน', 2), ('เรื่อง', 2), ('เปลี่ยนแพคเกจ', 1), ('อัพราคา', 1), ('รู้สึก', 1), ('แถม', 1), ('ทน', 1)]
  
  Cluster ID : 1
  
  Most common words include :[('กลิ่น', 6), ('หอม', 5), ('ดี', 4), ('สินค้า', 2), ('คุณภาพ', 2), ('ติด', 1), ('ทน', 1), ('ราคา', 1), ('package', 1), ('แข็งแรง', 1)]
  
  Cluster ID : 2
  
  Most common words include :[('กลิ่น', 9), ('ซื้อ', 5), ('ดี', 4), ('ขวด', 4), ('ราคา', 4), ('สินค้า', 3), ('หอม', 3), ('ตัว', 3), ('สั่ง', 3), ('ลด', 3)]
  ```

  เนื่องจากวิธี Cosine Similarity มีการแจกแจงในแต่ละคลัสเตอร์ได้เข้าใจและชัดเจนกว่า จึงเลือกตั้งชื่อคลัสเตอร์จากวิธี Cosine Similarity เป็นดังนี้

  Cluster ID : 0
  Group Name: "Longevity of Scent"
  
  Cluster ID : 1
  Group Name: "Product Quality and Fragrance"
  
  Cluster ID : 2
  Group Name: "Purchase Experience and Pricing"
