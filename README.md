# Google Docs API :page_facing_up:
:woman:Addin Nabilal Huda 16520342
### Apa itu Google Docs API?
Ketika kita mengolah data dalam jumlah yang besar serta ingin menampilkannya pada dokumen, kita pasti akan kesulitan karena waktu yang dibutuhkan amat lama. Seringkali, proses mengolah data yang lama memperlambat kerja suatu tim maupun perusahaan. Google docs API memberikan fasilitas berupa automatisasi dokumen, membuat dokumentasi dalam jumlah yang besar, serta menghasilkan dokumen kontrak maupun faktur secara otomatis. 

### Bulk Document Creation, Content Management, dan Workflow Management
Bagi kita yang terbiasa mengolah dokumen yang sama setiap bulannya secara normal, mengapa kita tidak meminta Google untuk melakukannya? Kita dapat memogram dokumen dan menghubungkannya dengan database yang kita miliki. Selain itu, ketika kita bekerja tim, kita dapat mengatur dokumen untuk dapat dilihat, diedit, dan dishare oleh tim. Google Docs API memudahkan user untuk mengimpor serta mengekspor konten ke database yang kita miliki. 

### Metode 
Metode yang digunakan secara garis besar berupa membuat dokumen(create), menerima konten dari dokumen tertentu (get), dan batchUpdate yang secara otomatis menampilkan update bilamana terjadi perubahan konten dokumen. Metode get dan batchUpdate memerlukan parameter berupa ID dokumen. Kita dapat melihat dokumen ID ini pada URL dokumen yang bersangkutan, contohnya seperti: https://docs.google.com/document/d/documentId/edit. Untuk menjalankan metode batchUpdate, kita perlu melakuan request object. Setiap object pada batchUpdates memiliki fungsi yang berbeda-beda dengan user dapat request berbagai macam objek dalam satu dokumen. Ketika user melakukan suatu request yang salah, update tidak akan terbaca. Biasanya, perubahan dilakukan pada body content yang memuat empat elemen structural yakni paragraph, section break, table, table of contents. Kebanyakan elemen dalam body memiliki indeks untuk mengawali dan mengakhiri property.

### Fitur Batch Update
Secara garis besar, batching merupakan metode untuk mengatur sesuatu menjadi group. Ide dalam programming aalah mengelompokkan hal-hal yang memiliki kesamaan untuk selanjutnya memudahkan programmer dalam melakukn pemrosesan. Dalam bekerja dengan Google Docs batching menjadi sangat penting karena akan memudahkan user dalam bekerja, mempercepat server, serta menghemat waktu dan kuota internet. Google docs memberikan fasilitas berupa batch update untuk melakukan batching. Melakukan batch update berarti kita membuat beberapa perubahan dalam dokumen dengan sekali kerja. Fitur ini dapat meningkatkan performa terlebih ketika kita bekerja dalam tim yang besar.

Google menyediakan berbagai bahasa untuk mengautomatisasi dokumen seperti python, java, php, dan sebagainya. Hal ini memudahkan aplikasi untuk terintegrasi dengan dokumen menggunakan input dari user dan sistem.

#### Referensi:
https://developers.google.com/docs/api
