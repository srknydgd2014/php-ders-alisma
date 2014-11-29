  <?php
    $dosya = fopen ("serkan.txt", "w" );
    $say=date("H:i:s");
    $yazim = fwrite($dosya,$say." "."serkan"."\n");
    $kapat = fclose($dosya);
    var_dump($yazim);
    ?>
