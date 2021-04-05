# install
1. install [PCL 1.9+](https://github.com/PointCloudLibrary/pcl/releases)
   1. download source
   2. unzip and change folder name to `pcl-pcl-1.xx.xx` where xx.xx is version
    ```
    mkdir build && build
    cmake -DCMAKE_BUILD_TYPE=Release ..
    make
    sudo make install
    ```
2. install eigen 3.0+
3. install [gpd](https://github.com/sbgisen/gpd)
4. build [gpd_grasp_msgs](https://github.com/TAMS-Group/gpd_grasp_msgs)
