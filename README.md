# Spotify-dashboard-with-tableau
CPE 329 BUSINESS INTELLIGENCE, Final Project, April-May 2021

[![PROJECT-BI.png](https://i.postimg.cc/g03KxKbq/PROJECT-BI.png)](https://postimg.cc/R3Vt8KFN)
Team :
1. Tussanakorn Rattanaburee
2. Trirat Arromrit
3. Jantharat Chumsang
4. Chanakarn Rungnisakarn

     ในการทำ Project ครั้งนี้ ทางกลุ่มเลือกที่จะมองในมุมมองของบริษัทที่เกี่ยวข้องกับการสร้างสรรค์เพลง (ค่ายเพลง) โดยบริษัทของเรานั้นจัดตั้งมาเป็นเวลานานและในปัจจุบันกำลังมองหาแนวทางการสร้างศิลปินและเพลงที่สามารถเจาะตลาดเพลงในรูปแบบแพลตฟอร์มสตรีมมิ่งออนไลน์ให้เพิ่มมากขึ้น เลยจำเป็นต้องนำเทคโนโลยี Business intelligent เข้ามาช่วยตอบความต้องการและการวางแผนในการทำ Project ในครั้งนี้ เพื่อให้ Project สามารถประสบความสำเร็จได้ดีมากยิ่งขึ้น
     
## Business Question
คำถามเชิงธุรกิจของทางกลุ่มเราในครั้งนี้ออกแบบมาเพื่อตอบความต้องการของค่ายเพลงที่ต้องการเปิดตัวศิลปินคนใหม่บนแพลตฟอร์มสตรีมมิ่งเพลงออนไลน์ Spotify ดังนั้นคำถามเชิงธุรกิจของเราจึงประกอบด้วย 3 คำถาม ดังนี้
- Descriptive I : แนวโน้มรูปแบบการฟังเพลงใน Spotify ในอดีต-ปัจจุบันเป็นอย่างไร
- Descriptive II : ลักษณะเพลงของนักร้องที่มีคาแรกเตอร์คล้ายกับศิลปินที่จะเปิดตัวที่ติด top chart ใน spotify เป็นอย่างไร
- Predictive : ควรทำเพลงลักษณะใดที่สามารถทำให้เพลงเปิดตัวสามารถติด top chart ในแพลตฟอร์มสตรีมมิ่งเพลงออนไลน์ Spotify

## Dataset
ในการทำ Project ในครั้งนี้ ทางกลุ่มได้นำข้อมูลการ Streaming บน Spotify และได้นำข้อมูลเกี่ยวคาแรคเตอร์ หรือ ลักษณะแนวเพลงที่ติด Top ของ Spotify มาใช้ในการทำ Dashboards และ ML Canvas โดยมีรายละเอียดชุดข้อมูลดังนี้
1. Spotify Dataset 1922-2021
website : https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks
2. Data for the songs in the Top 200 chart Year 2018 comes from the Spotify Charts website : https://spotifycharts.com/regional

ML Canvas : ในส่วนของการทำการจำลองการสร้าง Machine learning เพื่อตอบคำถามในหัวข้อของ Predictive Question ซึ่งทางกลุ่มเราได้เลือกใช้เครื่องมือ ML Canvas เพื่ออธิบายตัวอย่างการสร้าง ML และสรุปภาพรวมของการตั้งคำถาม และการทำงานของ Machine learning ที่จะนำมาประยุกต์ใช้

Tableau 2020.4 : ในการทำ Visualization ข้อมูลในครั้งนี้ ทางกลุ่มเลือกใช้เครื่องมือ Tableau Desktop และ Tableau Public ซึ่งสามารถทำให้การสร้าง Dashboard เป็นเรื่องที่สะดวกและเข้าใจได้ง่ายมากยิ่งขึ้น

## Machine Learning Canvas 
[![ML-canvas.png](https://i.postimg.cc/jSpXqFmS/ML-canvas.png)](https://postimg.cc/5Xmvnnfh)
## Digital Dashboard
[![Dashboard-1.png](https://i.postimg.cc/Z5BHSSfQ/Dashboard-1.png)](https://postimg.cc/hXnTLHR8)
## Summary
จากรายงานข้างต้น ทางกลุ่มของพวกเราเลือกที่จะมองในมุมมองของบริษัทเพลงหรือค่ายเพลง ซึ่งค่ายเพลงเหล่านี้กำลังต้องการที่จะปล่อยเพลงเปิดตัวของศิลปิน และมีความต้องการทำให้เพลงเปิดตัวสามารถติดอันดับ Top chart ใน Sportify ได้ ดังนั้นทางกลุ่มจึงได้เลือกใช้ชุดข้อมูลคาแรกเตอร์เพลงและการสตรีมมิ่งจาก Spotify Top chart มาใช้วิเคราะห์ โดยทางกลุ่มได้เริ่มจากคำถามในเชิง Descriptive business question ซึ่งคำถามคือการศึกษาแนวโน้มของการฟังเพลงของผู้ใช้ Spotify และการหาคาแรกเตอร์เพลงจากศิลปินที่มีบุคลิกที่ใกล้เคียง หรือมีการโปรโมทในลักษณะเดียวกันจากชุดข้อมูล Spotify ที่ทางกลุ่มได้มา ซึ่งข้อมูลเหล่านี้จะสามารถถูกตอบได้หมดผ่านการใช้ Dashboard ที่ทางกลุ่มได้จัดทำขึ้น และในส่วนของ Predictive ส่วนนี้จะทำการเอาค่าต่าง ๆ ของลักษณะเพลงที่ติด Top chart ของ Spotify มาทำการวิเคราะห์ด้วยรูปแบบโมเดล Machine learning ประเภท Clustering ซึ่งรูปแบบโมเดลดังกล่าวจะช่วยทำให้ทางค่ายเพลงสามารถนำเพลงที่ถูกกำหนดให้ใช้เป็นเพลงสาหรับการเปิดตัว เข้าสู่กระบวนการวิเคราะห์เพื่อหาความใกล้เคียงกับชุดข้อมูล Top chart ที่ทำการ Clustering เรียบร้อยแล้ว ซึ่งนั่นจะช่วยให้ทางค่ายเพลงสามารถวางแผนและตัดสินใจในการเลือกเพลงที่นำไปใช้ในการเปิดตัวให้ตรงกับกลุ่มผู้ฟัง และสามารถเป็นที่นิยมจนติด Top chart บนแพลตฟอร์ม Spotify ได้  
