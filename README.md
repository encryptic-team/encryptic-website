# encryptic-website
Assets for the non-app portion of encryptic.org

# Contributing

If you want to contribute to Encryptic's website, you're welcome !

If you want to edit CSS, you'll need to install [sass](https://sass-lang.com/install) (command line) first. After you've made your changes to the SASS files, you need to compile them using the following commands in the root directory:

`$ ./sass-compile.cmd`

if it doesn't work, use

`$ sass-compile.cmd`

Alternatively, you can also make live changes to scss files by using the following command in the directory of the scss file you're changing:

`$ sass --watch style.scss style.css`
It will compile the scss file into the css one everytime you save the scss document. Very easy and efficient for live testing. 
