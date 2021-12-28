# gitbash-missing-bins

This repo contains a few binaries missing, when installing software (such as sdkman) after gibash.

```
cd
mkdir bin
mkdir git
cd git
git clone https://github.com/mike-seger/gitbash-missing-bins.git
cp gitbash-missing-bins/mingw64/bin/* bin/
echo 'export PATH=~/bin:$PATH' >>.bashrc
source .bashrc
```


## Disable file download restriction in IE
To fix this issue follow these steps,
- From Internet Explorer go to Tools menu (gear icon).
- Click Security tab.
- Highlight the Internet icon then click on Custom level button.
- Scroll down and find the File Download setting under Downloads section.
- Here, change the option to Enable, then click OK button.

