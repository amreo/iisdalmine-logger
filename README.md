# Come installare
	1. installare git
		* Su distribuzioni Debian o derivate eseguire
		```sh
		apt install git
		```
		* Su distribuzioni RHEL o derivate eseguire
			```
			yum install git
			```		
		* Su distribuzioni Archlinux o derivate eseguire
			```
			pacman -S git
			```
		* Su altre distribuzioni consultare la propria documentazione di riferimento 
			o cercare su google come installare git su quella distribuzione
	2. Clonare il repository iisdalmine-logger
			```
			git clone https://github.com/amreo/iisdalmine-logger.git
			```
	3. Installare gli script
		```
		cd iisdalmine-logger
		```
		a) Se è installato un ambiente grafico (ovvero ha la GUI oltre la CLI)
			```
			./install-desktopentry
			```
		b) Se non è installato un ambiente grafico (ovvero ha solo la CLI)
			```
			./install
			```
	4. Configurare gli script
		```
		iisdalmine-configure
		```
# Come eseguire
	* per fare il login eseguire 
		```
		iisdalmine-login
		```		
	* per fare il logout eseguire
		```
		iisdalmine-login
		```		
