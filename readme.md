TP 1 Simulación.

Versión Python

Para instalar dependencias:

- pip3 install jupyterlab

Para correr:

jupyter-lab tp1.ipynb

Versión Julia

Instalar Julia 

https://julialang.org/downloads/

En ubuntu:

wget https://julialang-s3.julialang.org/bin/linux/x64/1.5/julia-1.5.2-linux-x86_64.tar.gz
tar -xvzf julia-1.5.2-linux-x86_64.tar.gz
sudo cp -r julia-1.5.2 /opt/
sudo ln -s /opt/julia-1.5.2/bin/julia /usr/local/bin/julia

Para instalar notebook:

correr Julia

julia> using Pkg
julia> Pkg.add("IJulia")
julia> using IJulia
julia> notebook()

Después se puede levantar desde ahí o igual que en python usar:

jupyter-lab y seleccionar el kernel de Julia o el archivo de Julia (y ya el kernel queda bien)
