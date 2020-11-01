# detection_of_tampered_zones
compilation steps
1. install tensorflow 1.13.1
   #pip install tensorflow==1.13.1
2. Missing cython_bbox function
You need to recompile bbox.c for your environment, generate the cython_bbox.so file and run it from
the command line.
cd /Learning-Rich-Features-for-Image-Manipulation-Detection-master-DATASET/lib/
python setup.py build_ext -i
3. Run Faster R-CNN diectely .
4. The model parametrs are in lib/config/config.py
