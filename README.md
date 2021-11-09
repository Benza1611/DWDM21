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

 ## บทที่ 4 
  * [ Data Warehousing and On-line Anaalytical Processing](https://github.com/Benza1611/DWDM21/blob/main/Chapter_4.pdf) 
     * Data Warehouse : Basic concepts
     * Data Warehouse Mining : Data Cube and OLAP
     * Data Warehouse Disng and Usage
     * Data Warehouse Implementation

## บทที่ 5 
#### Lecture
  * [สรุป Chapter 6](https://github.com/Benza1611/DWDM21/blob/main/Chapter_6.pdf)
#### Googlecolab
  * [Association Rules](https://github.com/Jaomiew/DWDM21/blob/main/Chapeter6_Association_Rules.ipynb)
    * Besic Concepts
       * K-itemsets
       * ลบ records ที่ถูก cancel ออกไป
       * Plot graph of Itemsets
       * Frequence Itemsets to Association Rule
    * Efficient Pattern Mining Methods
       * Apriori
       * Support

## บทที่ 6 
 * ประกอบไปด้วย 3 ส่วยย่อย คือ
   * [Desition Tree](https://github.com/Benza1611/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
      * Load Data
      * Train Model
         * import(เรียกใช้ algorithm ที่เราต้องการ)
         * define (กำหนด paramiters ให้กับ model)
         * train (ฝึกสอนตัวแบบ)
      * plot tree
      * Evaluation
        * Random
      * Advanced Tree
        * import
        * Define
        * Train
      * TEST
      * Start here
        * Import
        * Define
        * Train
        * Evaluate
   * [KNN](https://github.com/Benza1611/DWDM21/blob/main/Chap_7_Classification_(KNN_NN).ipynb)
       * Load data
       * Split Data
       * Train Model
         * import
         * knn1
         * knn2
         * knn3
       * Retrain & Evaluate
       * Neural Network
         * import
         * Define
         * Train - Test
         * ANN 2
         * ANN 3
   * [Evaluation](https://github.com/Jaomiew/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
       * Load data
       * Split Data
       * สร้าง Model ทำนาย
         * import
         * Define
         * Train
       * Evaluation

## บทที่ 7 
#### Lecture
  * [สรุป Classifier](https://github.com/Benza1611/DWDM21/blob/main/Chapter_8_Classifier.ipynb)
#### Googlecolab
  * [Clustering](https://github.com/Benza1611/DWDM21/blob/main/Chap8_Clustering.ipynb)
     * K-means
         * Generate Data
         * Explore Data
         * Clustering
           * import
           * Define
           * Fit-Predict
         * Exanple Application (Color Quantization)
           * นับจำนวนสี
           * จัดกลุ่มให้เหลือ 16 สี
           * แปลงข้อมูลให้อยู่ในรูป row-column
           * ใช้ centroid เป็นตัวแทนของสี
           * แทนสีคืนลงไป
      * Hierachical Clustering
      * Clustering Evaluation
 * [Cluster Analysis:Basic Concepts and Methods](https://github.com/Benza1611/DWDM21/blob/main/Chapter_10.pdf)
     * K-Means คืออะไร?
     * Clustering แบบลำดับชั้น
     * Cluster ที่ดี มี 4 ข้อ อะไรบ้าง?

## MiniExam
   * [Mid Term](https://github.com/Benza1611/DWDM21/blob/main/MiniExam.ipynb)

## Project
   * [Project ล่าสุด](https://github.com/Benza1611/DWDM21/blob/main/Project_%E0%B8%A5%E0%B9%88%E0%B8%B2%E0%B8%AA%E0%B8%B8%E0%B8%94.ipynb)
   * [PowerPoint]()
