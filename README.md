# Github checklist

1. ¿Cuál es el punto de partida?
	- si ya existe: clonar -> 

			$ git clone [url]

	- si no existe: iniciar y subir -> 

			$ git init
			$ git remote add origin [url]

2. ¿Qué voy a hacer?
	- revisar el código: moverme por las ramas

			# para ver las ramas
			$ git branch 

			# para ir a otra rama
			$ git checkout [nombre]

	- agregar código: crear y cerrar ramas

			# crear e ir a esa rama
			$ git checkout -b [nombre_rama]

			# hacer cambios en los archivos

			# agregar esos cambios a staging
			$ git add .
			
			# cuando ya tenga todos los cambios, crear commit
			$ git commit -m "mensaje del commit" 

			# podemos hacer push o seguir trabajando
			$ git push origin [nombre_rama]

			# o también, puedo cerrar la rama

			# voy a la rama destino
			$ git checkout [nombre_rama_destino]

			# hago merge con el nombre de la rama que quiero cerrar
			$ git merge [nombre_rama_cerrar]

			# hacer push con el merge
			$ git push origin [nombre_rama_destino]


			1. remoto: master
						staging
						pepita

			2. clone

			3. 	remoto: master
						staging	
						pepita

				local: master
						staging
						pepita

			4. crear rama dev

			5. remoto: master
						staging
						pepita

			   local: master
			   		staging
					pepita
			   		 dev

			6. hice muchos cambios sobre dev

			7. 	merge de dev sobre pepita

			8. voy a pepita

			9 desde pepita hago merge de dev dentro de pepita






	- modificar el código
	- devolver las versiones


