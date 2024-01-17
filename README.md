<h1>Laboratorium 13</h1>
<h2>Dominika Skolimowska</h2>
<p>Aby serwer byl dostepny w ramach Ingresu, nalezalo wprowadzic ponizsze zmiany w pliku values.yaml. Trzeba bylo wykorzystac NodePort oraz ustawic <i>enabled</i> w ingressie na <i>true</i>.</p>
<img src='values.png'/>
<p>Nastepnie nalezalo przeprowadzic instalacje:</p>
<img src ='install.png'/>
<p>Nalezy sprawdzwic czy zostaly utworzone service, pody oraz ingress:</p>
<img src="svc.png"/>
<img src="pod.png"/>
<img src="ingress.png"/>
<p>Teraz probujemy sie polaczyc:</p>
<img src="curl.png" />
<p>I sprawdzamy logi poda: </p>
<img src="logs.png"/>
<p>Wszystko dziala tak jak nalezy!</p>
