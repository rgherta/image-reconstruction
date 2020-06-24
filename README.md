# image-reconstruction

sudo docker run -it --rm -v /home/roman/Documents/image-reconstruction/dockerimages/in:/tmp/in -v /home/roman/Documents/image-reconstruction/dockerimages/out:/tmp/out -e CAMERA_FOCAL=768 romangherta/openmvg_run

sudo docker run -it --rm -v /home/roman/Documents/image-reconstruction/dockerimages/out:/tmp/in -v /home/roman/Documents/image-reconstruction/dockerimages/out:/tmp/out romangherta/openmvs_run
