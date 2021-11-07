# DWDM21
## Data Warehouse &amp; Data Mining 2021

นางสาวเบญญาภา ระภูเขียว 623020527-6

## Group Name : Numberone

1. **นางสาวเบญญาภา ระภูเขียว 623020527-6**

2. **นายศิริวัฒน์ ภูลำสัตย์ 623020765-0**

3. **นายธนิก พิมภิบาล 623021049-1**

4. **นางสาววนิศรา จงใจ 623021054-8**

5. **นายวิฆเนศ เกียรติเกษมสุข 623021055-6**


# สารบัญเนื้อหา

## บทที่1 
* [introduction](https://github.com/Benza1611/DWDM21/blob/main/Homework-Chapters-1.pdf)
  * ความหมายของ Data Mining
  * Knowladge Discovery (KDD) Process
  * ขั้นตอนในการทำ Data Mining
 
 ## บทที่ 2 
### Lecture
  * [สรุปการบ้านคาบ 1 Know your data](https://github.com/Benza1611/DWDM21/blob/main/Homework-Chapters-2.1.pdf)
    * ประเภทข้อมูล
    * ประเภทของชุดข้อมูล : การบันทึกข้อมูล
    * ประเภทของชุดข้อมูล : กราฟและเครือข่าย
    * ประเภทของชุดข้อมูล : ข้อมูลที่มีเวลาเข้ามาเกี่ยวข้อง
    * ประเภทของชุดข้อมูล : ข้อมูลเชิงพื้นที่
    * ลักษณะสำคัญของข้อมูล
### Googlecolab 
 * ประกอบไปด้วย 3 ส่วน ได้แก่
    * [Basic Python](https://github.com/Benza1611/DWDM21/blob/main/Data101(Chapter2).ipynb)
      * Casting
      * Data Structure
        * วิธีการสร้าง list ว่าง
        * การชึ้ต่าใน list (indexing)
        * list slicing
        * list + list
      * Loop
        * Nested loop
      * Condition (if statement)
      * Function
      * [Mount G Drive](https://github.com/Benza1611/DWDM21/blob/main/Data102(Chapter2).ipynb)
        * .head() .tail()
        * Boxplot
        * Tine Series Plot
   * [Data Visualization](https://github.com/Benza1611/DWDM21/blob/main/Data_Visualization.ipynb)
      * Scatter plot
      * Plot
      * Bar chart
      * Histogram
   * [Distance Numpy](https://github.com/Benza1611/DWDM21/blob/main/Distance_Numpy.ipynb)
     * Numpy Array
       * สร้าง numpy araay (matrix)
       * Matrix transpose
       * สร้าง matrix เริ่มต้น (zeros,one)
       * สร้าง matrix random
       * matrix properties
     * Indexing & Slicing
     * Useful functions
     * วน loop เอง
       * Summation
     * Distance Matrix
       * Euclidean Distance (L2-norm)
     * Distance function
       * Euclidean Distance (L1-norm)
     * Distance of Binary Value

## บทที่ 3 
* [Data Preprocessing](https://github.com/Benza1611/DWDM21/blob/main/Data_Prepocessing_(Chapter_3).ipynb)
  * Meta Data (Data ที่ใช้อธิบาย Data)
  * ชี้ข้อมูลในตาราง
    * ชี้แบบธรรมดา
    * ชี้แบบ .iloc[]
  * Missing Values
    * Handling Missing Value 1 (ลบค่า missing)
    * Handling Missing Value 1.5 (ลบค่า missing เฉพาะ Colum ที่เราสนใจ)
    * Handling Missing Value 2 (แทนด้วย class ใหม่ (unknown)) 
    * Handling Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
    * Handling Missing Value 4 (แทนด้วย ค่ากลาง)
    * Handling Missing Value 5 (แทนด้วย ค่ากลาง samples ใน class เดียว)
  * Select data by value [PD] 
    * สร้าง list ของ boolean
    * นำ list ของ boolean มาเลือกค่าในตาราง
    * ต่อตารางแนวแกน Y [PD}
    * Handling Missing Value 5 (แทนด้วย ค่ากลาง samples ใน class เดียว)(ต่อ)
    * การเรียงข้อมูล [PD]
  * Outlier
    * Pandas'looping (iterrows)
  * การรวมตาราง Data Integration (ต่อตารางในแนวแกน x )
    * รวม 2 ตาราง (.merge())
    * เลือกเฉพาะ Column ที่ต้องการมาแปะ (.map())
    * ตารางรอง (ตารางด้านขวา) ต้องไม่มี index ซ้ำ*
    * Group by (pandas)
    * [PD] save ตารางเอาไปใช้ที่อื่น
    * [PD]การสร้างตาราง
