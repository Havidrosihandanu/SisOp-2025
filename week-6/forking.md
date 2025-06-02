

## code
```c
#include <stdio.h>
#include <unistd.h>
#include <sys/wait.h>

int main() {
    pid_t pid = fork();

    if (pid < 0) {
        perror("Fork gagal");
        return 1;
    } else if (pid == 0) {
        printf("Proses anak (PID: %d)\n", getpid());
    } else {
        printf("Proses induk (PID: %d) dengan anak PID: %d\n", getpid(), pid);
        wait(NULL);
        printf("Proses anak telah selesai\n");
    }
    return 0;
}
```

## hasil
![Forking](forking.png)
## kesimpulan

Apa yang terjadi ?
program akan menunjukan bagiamana cara membuat proses baru menggunakan fork() dan menunggu proses anak selesai.
saat program ini dijalankan akan memanggil fungsi fork dan membuat proses induk dan salinan yang berfungsi sebagai proses anak. yang nanti akan berjalan secara paralel.
Jika fork() berhasil, maka:
Proses anak akan mencetak pesan yang menunjukkan bahwa ia adalah proses anak, serta mencetak ID prosesnya sendiri (getpid()).
Proses induk akan mencetak pesan yang menunjukkan bahwa ia adalah proses induk, mencetak ID-nya, dan juga mencetak ID dari proses anak (yang dikembalikan oleh fork()).
Setelah itu, proses induk akan memanggil wait(NULL), yang berfungsi untuk menunggu proses anak selesai sebelum melanjutkan. Setelah proses anak selesai, proses induk akan mencetak pesan tambahan bahwa proses anak telah selesai.



