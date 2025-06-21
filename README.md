# Comparing-Embedding-Methods
Comparing Embedding Methods for Indonesian Text Classification
# About the data
This corpus is derived from several freely accessible Indonesian news website for research purpose only. The news websites are: 

- kompas.com is a registered trademark of  PT. Kompas Cyber Media. https://inside.kompas.com/about-us
- tempo.co is a registered trademark of  PT INFO MEDIA DIGITAL. https://www.tempo.co/about
- merdeka.com is a registered trademark of  PT KAPAN LAGI DOT COM NETWORKS. https://www.merdeka.com/company/tentang-kami.html
- republika.co.id is a registered trademark of  PT Republika Media Mandiri. https://www.republika.co.id/page/about
- viva.co.id is a registered trademark of  PT. Viva Media Baru. https://www.viva.co.id/tentang-kami
- tribunnews.com is a registered trademark of PT Tribun Digital Online. http://www.tribunnews.com/about-us      

The corpus is a part of bachelor thesis work of Aad Miqdad Muadz Muzad. Please cite this publication if you use this corpus in your research:

MUZAD, Aad Miqdad Muadz; RAHUTOMO, Faisal. Korpus Berita Daring Bahasa Indonesia Dengan Depth First Focused Crawling. Prosiding Sentrinov (Seminar Nasional Terapan Riset Inovatif), [S.l.], v. 2, n. 1, p. 11-20, oct. 2016. ISSN 2477-2097. Available at: <http://proceeding.sentrinov.org/index.php/sentrinov/article/view/163>.

We crawled several categories of the websites for 6 months from July 2015 until December 2015. The corpus contains 150,466 news articles. The authors are not responsible for any further use of this corpus against laws.

The corpus is stored in JSON and XML format. The JSON format has this structure: \
{ \
“sumber”: “”, \
“Tanggal”: “”, \
“kategori”: “”, \
“judul”: “”, \
“isi”: “”, \
“link”: “” \
} \
