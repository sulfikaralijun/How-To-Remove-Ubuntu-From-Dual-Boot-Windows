# How-To-Remove-Ubuntu-From-Dual-Boot-Windows

pertama hapus disk ubuntu dari disk management, kemduain buka diskpart dengan cara menjalankan cmd sebagai administarot, dan ketik diskpart dan enter.
1. ketik `list disk` dan lihat nomor disk termpat ubuntu dintall
2. kemudian select disk yag dpilih denagn commnad `sel disk <nomot disk>`
3. liat partition yang ada dengan `list partition`, kemduain slect lagi partrtin system dengan `sel partition <nomot partisi sistem>`
4. kemduain ketik `assign letter=z`, kemduian enter dan exit.
5. ketik `z:` dan enter, kemudian `cd EFI` kemudian `dir` untuk melihat nama distro yang mau di hapus.
6. ketik `rd ubuntu /s` dan ketik y.
