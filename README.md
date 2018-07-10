# tekcft.php
100 e Kadar Sıralanan Sayıların tek'mi çift'mi olduğunu ayıran  php kodu


$tek=0; $cıft=0;

for ($i=1; $i <=100 ; $i++) { // 1 den başlayıp 100 e kadar sayı sıralayacaktır echo "$i Sayı : ".$i; if ($i%2==0) { // Sayı Çift ise aşşağıdaki bloğu çalıştırır echo " Bu sayı Çifttir"; echo "
"; echo "

"; $cıft++; }else { // Sayı Tek ise aşşağıda else bloğunu çalıştırır echo " Bu sayı Tektir"; echo "
"; echo "
"; $tek++;
} }

echo "Çift sayısı $cıft kadar"; echo " "; // kaç tane çift sayısı olduğunu gösterir echo "Tek sayısı $tek kadar"; // kaç tane tek sayısı olduğun gösterir
