# Switches 

## 1.  Basic Configuração

| - Hostename:

	 hostname SW1!

| - Senha do root console:

	enable secret senhaAdmin

| - Senha do console:

	 line console 0
	 password senha123
	 history size 10
	 login

| - Senha remota console:

	line vty 1 15
	password senha123
	login

| - Encriptação:

	enable service-ncrypton

| - Mensagem banner:

	banner motd # Apenas usuarios permitidos #

| - Salvar a configuração:

	wr
	OR
	copy running-config startup-config
