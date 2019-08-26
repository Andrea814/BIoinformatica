# Instalación de FASTQC

Se inicia colocando el siguiente comando en la consola:

`$ sudo apt-get install fastqc`

Despues de esto pedira autorizacion para espacio de almacenamiento se lo otorgamos y la instalacion finalizará.

# Instalación de CUTADAPT
 ### Instalación con conda

 En la consola se coloca el comando:

` $ conda install -c bioconda cutadapt`

### Instalación con pip

  Usando el comando:

`$ sudo python3 -m pip install --upgrade cutadapt `

En necesario tener los paquetes anteriores ya instalados.

#  Instalación de TrimGalore

Es necesario tener ya instalados los paquetes anteriores ára ṕder instalar este paquete, entonces se coloca el comando:

` $ curl -fsSL https://github.com/FelixKrueger/TrimGalore/archive/0.6.0.tar.gz -o trim_galore.tar.gz tar xvzf trim_galore.tar.gz`

Posteriormente para saber que ya lo tenemos instalado corremos el paquete con el siguiente comando:

` $TrimGalore-0.6.0/trim_galore`

Si corre sin ningun error es que fue instalados satisfactoriamente.

# Instalación de SPAdes

Se instala con el comando:
` $ sudo apt install spades`

Para rectificar la instalacion se escribe:

` $ spades.py --test`

Nos btrindara la infromacion del paquete en nuestro sistema siendo la version que esta instalada.

# Instalación de velvet
 Se utilixa nuevamente el comando:

` $ sudo apt-get install velvet`

# Instalación de c-shell

 Repitiendo el paso anterior se usa el comando:

` $ sudo apt-get install tcsh`

Para estar seguro que la Instalación se realizó correctsmente se usa el comando:

`$ tcsh`

Esto correra el programa.

# Instalación de MUMmer3.2
 ## Primer paso

 Es necesario descargar eñ archivo tar [][27b92a46]

  [27b92a46]: https://sourceforge.net/projects/mummer/files/ "De la siguiente pagina"

  ## Segundo paso

  Descomprimir el archovo con el comando

` $tar -xvzf MUMmer3.0.tar.gz `

 ## Tercer paso
 Ahora si se instala con el comando:

` $ mummer`
