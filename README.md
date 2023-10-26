# Ubah direktori kerja ke tempat Anda ingin menyimpan proyek
cd/payh/to/your/workspace
# clone repositori ke komputer anda
git clone <URL_repositori>
# Masuk ke direktori proyek yang telah dicloning
cd javaVersionControlPratice

# Buat file java sederhana(Contoh:Main.Java)
# Isi file dengan kode sederhana, misal
# public class Main {
# public static void main(String[] args) {
#        System.out.println("Halo");
#    }
# }

# Tambahkan perubahan ke indeks Git
git commit -m "Added a simple Java program"

# Dorong perubahan ke repositori jarak jauh
git push origin master