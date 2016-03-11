# spiff_spark
Procesado tweets Spark

Recibimos un conjunto de tweets en cada línea algo como:
@Chady2009	18 Dec 2010	من اجل الخبزة..شاب يحاول الانتحار... https://www.facebook.com/video/video.php?v=132433530151270 #sidibouzid  @t_kahlaoui  behi?


De aquí queremos obtener:

        autor: que es lo que viene tras la primera arroba, @Chady2009
	    menciones: las arrobas que vengan después del autor: @t_kahlaoui
		url:  https://www.facebook.com/video/video.php?v=132433530151270 
		etiquetas: todo lo que tenga un # delante de la palabra: #sidibouzid





