# InitKivy

Una aplicación "hello worl" usando kivy 

## Generar APK con BUILDOZER en ubuntu20.04  o WSL(ubuntu20.04)

### INSTALAR
~~~
pip3 install --user --upgrade buildozer
sudo apt update
sudo apt install -y git zip unzip openjdk-8-jdk python3-pip autoconf libtool pkg-config zlib1g-dev libncurses5-dev libncursesw5-dev libtinfo5 cmake libffi-dev libssl-dev
pip3 install --user --upgrade Cython==0.29.19 virtualenv  # the --user should be removed if you do this in a venv

# add the following line at the end of your ~/.bashrc file
export PATH=$PATH:~/.local/bin/
~~~
### Directorio
~~~
main.kv  main.py
~~~
~~~
RUN: buildozer init
RUN: buildozer android debug deploy run
~~~
 ### El APK esta en la carpeta bin

