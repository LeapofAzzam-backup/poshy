<p align="center">
	<img title="Poshy" alt="Poshy" src="images/poshy-logo-shadowed.png" width="256">
	<h1>Poshy, an extensible shell written in Python</h1>
</p align "center">

You can contact us via [our Discord!](https://discord.gg/R5ExvA63Jz)

Poshy is a work-in-progress shell written in Python. As of now, it has no configuration files.

## Usage
Clone this repo (or download as a ZIP file) and run `python3 ./poshy.py`.

## AYP DOCUMENTATION
AYP (All your plugins) are simple plugins that run before the shell does. There's not API you need to learn before making a plugin or program.

For the file structure and installation, AYP recommends you use `bash` for the simplicity of the installation. The things you need to learn before starting are:

1. That we strictly moderate your plugins
2. That we can control them
3. That you must **NOT** make some sort of virus on your AYP plugin

The file structure is:

1. Using `curl` or `wget` to download the bundle
2. Extract the bundle
3. Put it in the `programs` dir and
4. Run ```echo 'import bin.programs.<AYPNAME> >> ayploader.py``` in terminal, while replacing \<AYPNAME> with your package name

Package manager coming soon, make sure you make `carapace` as your installation hosting subdomain 
