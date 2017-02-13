# Come installare
1. Installare git
	* Su distribuzioni Debian o derivate eseguire
		```sh
		apt install git
		```
  	* Su distribuzioni RHEL o derivate eseguire
		```sh
		yum install git
		```		
	* Su distribuzioni Archlinux o derivate eseguire
        ```sh
        pacman -S git
        ```
	* Su altre distribuzioni consultare la propria documentazione di riferimento 
	  o cercare su google come installare git su quella distribuzione
2. Clonare il repository iisdalmine-logger
    ```sh
    git clone https://github.com/amreo/iisdalmine-logger.git
    ```
3. Installare gli script
    ```sh
    cd iisdalmine-logger
    ```
    * Se è installato un ambiente grafico (ovvero ha la GUI oltre la CLI)
    	```
    	./install-desktopentry
    	```
    * Se non è installato un ambiente grafico (ovvero ha solo la CLI)
    	```sh
    	./install
    	```
4. Configurare gli script
	```sh
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
