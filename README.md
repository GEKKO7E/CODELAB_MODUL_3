Proyek Kalkulator Sederhana (Java)
Proyek ini adalah implementasi program kalkulator yang sangat dasar menggunakan bahasa Java. Tujuannya adalah untuk mendemonstrasikan konsep variabel, operasi aritmatika, dan cara kerja Git commit.

Kode Program (Kalkulator.java)
// Nama file: Kalkulator.java
public class Kalkulator {

    public static void main(String[] args) {
        // 1. Deklarasi Variabel
        // 'int' digunakan untuk menyimpan bilangan bulat.
        int angkaPertama = 10;
        int angkaKedua = 25;
        int hasil;

        // 2. Proses Penjumlahan
        // Menjumlahkan isi dari dua variabel dan menyimpannya di variabel 'hasil'.
        hasil = angkaPertama + angkaKedua;

        // 3. Menampilkan Hasil
        // Mencetak kalimat beserta nilai dari variabel 'hasil' ke konsol.
        System.out.println("Hasil penjumlahan " + angkaPertama + " + " + angkaKedua + " adalah: " + hasil);
    }
}
Kondisi Proyek Sebelum Commit
Ketika Anda baru saja membuat file Kalkulator.java atau memodifikasinya, proyek Anda berada dalam keadaan "belum di-commit".

Tampilan di IntelliJ IDEA:
Nama file Kalkulator.java akan berwarna merah (jika file baru) atau biru (jika file dimodifikasi).
File tersebut akan muncul di bawah daftar "Changes" atau "Unversioned Files" di dalam jendela Commit (Ctrl + K).
Status di Terminal (git status):
Jika Anda menjalankan git status di terminal, outputnya akan terlihat seperti ini:

On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        src/main/java/Kalkulator.java

nothing added to commit but untracked files present (use "git add" to track)
Ini artinya Git melihat ada file baru, tetapi file tersebut belum "didaftarkan" untuk disimpan dalam riwayat.

Kondisi Proyek Sesudah Commit
Setelah Anda menulis pesan commit (misalnya, "Menambahkan program kalkulator") dan menekan tombol Commit, Anda telah berhasil menyimpan sebuah "foto" dari kondisi proyek Anda saat itu.

Tampilan di IntelliJ IDEA:
Nama file Kalkulator.java akan kembali berwarna putih (normal).
Daftar "Changes" di jendela Commit akan menjadi kosong.
Status di Terminal (git status):
Jika Anda menjalankan git status lagi, outputnya akan berubah menjadi:

On branch master
nothing to commit, working tree clean
Ini artinya semua perubahan sudah disimpan dengan aman di riwayat Git lokal Anda dan tidak ada pekerjaan yang tertunda. Proyek Anda sekarang dalam keadaan "bersih" dan siap untuk perubahan selanjutnya atau untuk di-push ke GitHub.
