# Come installare
	1) installare git
		a) Su distribuzioni Debian o derivate eseguire
			```sh
			apt install git
			```
		b) Su distribuzioni RHEL o derivate eseguire
			```{r, engine='bash', rhel_install_git}
			yum install git
			```		
		c) Su distribuzioni Archlinux o derivate eseguire
			```{r, engine='bash', archlinux_install_git}
			pacman -S git
			```
		d) Su altre distribuzioni consultare la propria documentazione di riferimento 
			o cercare su google come installare git su quella distribuzione
	2) Clonare il repository iisdalmine-logger
			```{r, engine='bash', git_clone_iisdalmine_logger}
			git clone https://github.com/amreo/iisdalmine-logger.git
			```
	3) Installare gli script
		```{r, engine='bash', cd_iisdalmine_logger}
		cd iisdalmine-logger
		```
		a) Se è installato un ambiente grafico (ovvero ha la GUI oltre la CLI)
			```{r, engine='bash', install_desktopentry}
			./install-desktopentry
			```
		b) Se non è installato un ambiente grafico (ovvero ha solo la CLI)
			```{r, engine='bash', install}
			./install
			```
	4) Configurare gli script
		```{r, engine='bash', iisdalmine_configure}
		iisdalmine-configure
		```
# Come eseguire
	*) per fare il login eseguire 
		```{r, engine='bash', iisdalmine_login}
		iisdalmine-login
		```		
	*) per fare il logout eseguire
		```{r, engine='bash', iisdalmine_login}
		iisdalmine-login
		```		
