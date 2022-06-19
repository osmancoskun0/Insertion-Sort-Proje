## <h3 style="background-color: darkblue; font-weight:bold;"><span style="color:orange;">[22,27,16,2,18,6]</span> --> insertion sort ile yeniden sıralama yapılacak</h3>


1.  -   Adım No:1 <br>
        <span style="color:orange;">[2,27,16,22,18,6]</span>

    -   Adım No:2 <br>
        <span style="color:orange;">[2,6,16,22,18,27]</span>

    -   Adım No:3 <br>
        <span style="color:orange;">[2,6,16,18,22,27]</span>

    Sıralama 3 adımda tamamlandı.

2.  Big-O gösterimi;

    Insertion Sort n tane elemanı kadar n defa sorgu yaptığından dolayı o(n<sup>2</sup>)

3.  
    - Best Case; aranılan elemanın ilk olması durumunda "o(n)",
    - Average Case; aranılan elemanın ortadaki olması durumunda "o(n<sup>2</sup>)",
    - Worst Case; aranılan elemanın sonuncu olması veya hiç olmaması durumunda "o(n<sup>2</sup>)",

    olarak çözüm kümesi verir.

4.  "18" dizinin ortadaki elemanı olduğu için **Average Case** kapsamına girmektedir.


   
<h3 style="background-color: darkgreen; font-weight:bold;"><span style="color:orange;">[7,3,5,8,2,9,4,15,6] </span> --> insertion sort ile yeniden sıralama yapılacak sıralamanın ilk 4 adımı </h3>

1.  -   Adım No:1 <br>
        <span style="color:orange;">[2,3,5,8,7,9,4,15,6]</span>

    -   Adım No:2 <br>
        <span style="color:orange;">[2,3,4,8,7,9,5,15,6]</span>

    -   Adım No:3 <br>
        <span style="color:orange;">[2,3,4,5,7,9,8,15,6]</span>
    
    -   Adım No:4 <br>
        <span style="color:orange;">[2,3,4,5,6,9,8,15,7]</span>


        ![ekran resmi](/img/ekran-resmi.png "ekran resmi")