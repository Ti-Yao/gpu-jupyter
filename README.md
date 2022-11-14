docker run -it --rm --gpus '"device=0"' -d -it -p 8848:8888 -v /home/tina/Project:/home/jovyan/work -e GRANT_SUDO=yes -e JUPYTER_ENABLE_LAB=yes --user root tiyao/gpu-jupyter

docker run -it --rm --gpus '"device=1"' -d -it -p 8858:8888 -v /home/tina/Project:/home/jovyan/work -e GRANT_SUDO=yes -e JUPYTER_ENABLE_LAB=yes --user root tiyao/gpu-jupyter
