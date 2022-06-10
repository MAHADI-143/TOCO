# py3 dec

dpkg -i py3dec.deb

pkg install clang
pkg install cmake
pkg install make
git clone https://github.com/zrax/pycdc
cd pycdc
chmod 777 pycdas.cpp
chmod 777 pycdc.cpp
cmake . 
make
mv 
pycdc $PREFIX/bin && mv pycdas $PREFIX/bin

pkg install python
git clone https://github.com/NoobDecompiler/dis3

cd dis3

python setup.py install


py3dec file.py
