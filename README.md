# SCAV_P3
S'han adjuntat els diferents outputs de les comandes (streams i vídeos) en el repositori de github

# EX1

En el primer exercici, la comanda el que fa és el següent:

-Reescala el vídeo en 3 formats

-Aplica diferents bitrates a cadascún d'ell (víde i àudio)

-Creem les diferents carpetes i m3u8 (HLS)


# EX2
Primer necessitem fragmentar el vídeo amb bent4
![alt text](https://github.com/Aleix20/SCAV_P3/blob/main/ex2_fragmented_video.png)

Una vegada ja tenim el nostre vídeo fragmentat, apliquem DASH i encriptem el vídeo de la següent manera:
![alt text](https://github.com/Aleix20/SCAV_P3/blob/main/ex2_fragmented_video_dashencrypt.png)

Per últim, podem observar la creació d'una carpeta output, on podem veure informació sobre l'arxiu MPD:
![alt text](https://github.com/Aleix20/SCAV_P3/blob/main/ex2_encryptedMPD_info.png)


# EX3

A l'exercici 3, he intentat fer el live stream en local, utilitzant broadcast com a IP, podia accedir amb ffplay des de el propi ordinador, però si provava des de un altre dispositiu en la mateixa xarxa, em refusava la connexió (segurament, ports tancats, tot i que no vaig aconseguir que funcionés):
![alt text](https://github.com/Aleix20/SCAV_P3/blob/main/ex31.png)
![alt text](https://github.com/Aleix20/SCAV_P3/blob/main/ex32.png)



# EX4
 
 Per últim, he aconseguit extreure un m3u8 d'un streaming de twitch(ex4twitch.m3u8), en aquest cas, vaig decarregar un fragment (ex4twitch.ts), on podem observar la següent informació sobre els codecs(àudio i vídeo):
 
 ![alt text](https://github.com/Aleix20/SCAV_P3/blob/main/ex4_codecInfo.png)

 
