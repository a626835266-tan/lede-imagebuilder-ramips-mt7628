# Imagebuilder for ar71xx generic  

## System Requirement  

- x86_64 platform  
- ubuntu or other linux  
- You need to install necessary software  

```bash  
$ sudo apt-get update
$ sudo apt-get install subversion build-essential git-core libncurses5-dev 
zlib1g-dev gawk flex quilt libssl-dev xsltproc libxml-parser-perl mercurial 
bzr ecj cvs unzip git wget
```  

## Download the Source  

```bash  
$ git clone https://github.com/gl-inet/lede-imagebuilder-ramips-mt7628.git
$ cd lede-imagebuilder-ramips-mt7628
```  

## Configuration  

You can change images.json file to install or remove packages for your  
preference.  

## Create Image  

We can use gl_image utility to create image quickly. You can issue  
`gl_image --help` for help.  

For GL-MT300N-V2 of v2.27:  
```bash  
$ ./gl_image -i v1 -p gl-mt300n-v2 -v 2.27
```  

Available image or profile is listed in images.json.  


