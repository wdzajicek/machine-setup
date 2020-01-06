# Upgrade The Stock Nano Installation

macOS 10.14.6 comes with GNU nano version 2.0.6. Latest version is 4.x.

"GNU nano is written in C and thus very easy to build from source." Run the following commands to download and
compile. Substitute `<nano-X.X>` with a nano version (e.g. `nano-4.7`) from https://www.nano-editor.org/. 
Additionally, substitute `<vX>` with the major version # preceded with a 
'v' e.g. `v4`):
```bash
curl -O  https://www.nano-editor.org/dist/<vX>/<nano-X.X>.tar.gz
tar xvzf <nano-X.X>.tar.gz
cd <nano-X.X>
./configure
make
make install
```

To install nano-4.7 you would run:
```bash
curl -O  https://www.nano-editor.org/dist/v4/nano-4.7.tar.gz
tar xvzf nano-4.7.tar.gz
cd nano-4.7
./configure
make
make install
```

