# TUGAS 4

Nama : Karmila Novi Arfiana

Kelas : TI 3C / 09

NIM : 2041720073

## Langkah-langkah praktikum

### Uji Coba PySpark
Menjalankan service dari pyspark terlebih dahulu dengan perintah 

<code>cd spark-2.0.0-bin-hadoop2.7</code>

<code>bin/pyspark</code>

![](ss/1.png)

1. Uji coba  <code> Accumulator.py </code>
![](ss/2.png)

2. Uji coba <code> BroadCast.py </code>
![](ss/3.png)


3. Uji coba <code> LogAnalytics.py </code>
![](ss/4.png) <br>
![](ss/5.png) <br>

4. Uji coba <code> PairRDD.py </code> <br>
![](ss/6.png)

5. Uji coba <code> UnderstandingRDD.py </code>
![](ss/7.png) <br>
![](ss/8.png) <br>
![](ss/9.png) <br>

6. Uji coba <code> WordCount.py </code>
![](ss/10.jpg) <br>
![](ss/11.jpg) <br>


### Uji Coba Scala
Menjalankan service dari sparkshell terlebih dahulu dengan perintah
<code>cd spark-2.0.0-bin-hadoop2.7</code>

<code>bin/spark-shell</code>

![](ss/11.png) <br>

Jalankan juga service cloudera manager dengan perintah: <br>

<code> sudo /home/cloudera/cloudera-manager --express --force </code>
kemudian login pada browser. Setelah itu, jalankan service HDFS

![](ss/12.png) <br>


1. Uji coba <code> SystemCommandsOutput.scala </code>
![](ss/13.png) <br>
![](ss/14.png) <br>

2. Uji coba <code> SystemCommandsReturnCode.scala </code>
![](ss/15.png) <br>
![](ss/16.png) <br>
Sukses menampilkan list file pada folder /tmp (temporary file)