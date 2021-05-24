<h1>CODE2</h1>
<h3>Program obliczający pole powierzchni prostokata, pole powierzchni całkowitej oraz objętość prostopadłościanu.
Zostały wykonane dwie wersje programu CODE2.</h3>
<ul>
  <li>CODE2V1 - wykorzystuje prosty plik Makefile</li>
  <li>CODE2V2 - ulepszona wersja CODE2V1, ponieważ zastosowano narzędzia Autotools</li>
</ul>
  

  Możliwe jest skolonowanie całego repozytorium poleceniem i bash:
    <ul>
  <li>git clone https://github.com/szylvvia/zadanie_2_code2.git</li>
  </ul>
  
  <h2>Jak zainstalować v1?</h2>
  
  <h3>Wersja v1</h3>
      <ul>
  <li>git clone -b v1 https://github.com/szylvvia/zadanie_2_code2.git</li>
  <li>tar -zxvf code2v1.tar.gz</li>
  </ul>
  
  Należy wydać polecenia w terminalu w katalogu code2v1:<br>
  <ol>
  <li>make</li>
     <li>sudo make install</li>
     <li> make clean //opcjonalnie w celu usuniecia zbednych plikow</li>
     <li>export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/lib</li>
   </ol>
    
 <h2>Jak odistalować v1?</h2> 
        <ul>
  <li>sudo make uninstall</li>
  </ul>
  
<h2>Jak zainstalować v2?</h2>
  <h3>Wersja v2</h3>
      <ul>
  <li>git clone -b v2 https://github.com/szylvvia/zadanie_2_code2.git</li>
  <li>tar -zxvf code2v2-3.0.tar.gz</li>
  </ul>
  
 Należy wydać polecenia w terminalu w katalogu code2v2:<br>
 
 <ol>
  <li>./configure </li>
	 <li>make</li>
   <li>sudo make install</li>
  </ol>
  
   <h2>Jak odistalować v2?</h2>
   Należy wydać polecenia w terminalu w katalogu code2v2:<br><br>
  <ul>
  <li>sudo make uninstall</li>
  </ul>
