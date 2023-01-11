# Projeler

1.Insertion Sort
[22,27,16,2,18,6] dizisini Insertion Sort algoritması ile çalıştırırsak; dizinin 2.elemanı yani 27 başlangıç elemanı seçilir. 27 ile 22 kıyaslanıp küçükse soluna büyükse sağına yazılır. Buradaki durumda büyük o yüzden sağda kalır.

Dizinin 3.elemanı olan 16, önce 27 ile sonra 22 ile kıyaslanır. Küçük olduğu için sola yazılır. Yeni dizi [16,22,27,2,18,6] olur.

Dizinin 4.elemanı olan 2 kıyaslanıp sola alınır. Yeni dizi [2,16,22,27,18,6] olur.

Dizinin 5.elemanı olan 18 sol tarafla kıyaslanır ve yazılır. Yeni dizi [2,16,18,22,27,6] olur.

Dizinin son elamanı olan 6 da kıyaslanıp yazılır. Böylelikle [2,6,16,18,22,27] sıralı dizisi elde edilir.

18 sayısı dizinin en son basamağından bir önce yerleştirildiği için Worst Case'e yakındır ama Average Case senaryosu kapsamına girer.

Big O Notation = İşlem sayısı n, n-1, n-2...1 şeklinde olacağından, işlem sayısı toplamı n.(n+1)/2; dominant faktörü n²'dir. O(n²)

Selection Sort
[22,27,16,2,18,6]

[2,27,16,22,18,6]--> En küçük sayıyı buluyoruz ve en başa yazıyoruz. (n tane eleman)

[2,6,16,22,18,27]--> (n-1) eleman içinden tekrar en küçük sayıyı bulup ikinci sıraya yazıyoruz.

[2,6,16,22,18,27]--> (n-2) eleman içinden tekrar en küçük sayıyı buluyoruz zaten üçüncü sırada.Dokunmuyoruz.

[2,6,16,18,22,27]--> Bu şekilde giderek bitiriyoruz. Küçükten büyüğe sıralamış olduk.
