Bootstrap: docker
From: ubuntu:16.04

%post
    apt-get update && apt-get install -y wget
    echo 'Downloading the Paraview Installer'
    wget -O /opt/ParaView-5.7.0-RC2-osmesa-MPI-Linux-Python3.7-64bit.tar.gz "https://www.paraview.org/paraview-downloads/download.php?submit=Download&version=v5.7&type=binary&os=Linux&downloadFile=ParaView-5.7.0-RC2-osmesa-MPI-Linux-Python3.7-64bit.tar.gz"
    tar zxvf /opt/ParaView-5.7.0-RC2-osmesa-MPI-Linux-Python3.7-64bit.tar.gz -C /opt/
    chmod -R 777 /opt/
   
#%runscript
#    exec '$@' 
