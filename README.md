1. Install Chocolatey
   https://chocolatey.org/install
2. Install OpenCV
    ```
      choco install OpenCV -y
    ```
3. Set environment variables

    ```
    OPENCV_BIN_DIR
    C:\Tools\opencv\build\x64\vc15\bin

    OPENCV_INCLUDE_DIR
    C:\Tools\opencv\build\include

    OPENCV_LIB_DIR
    C:\Tools\opencv\build\x64\vc15\lib

    PATH
    ...;%OPENCV_BIN_DIR%
    ```
4. Clone repository and Install packages
    ```
    git clone https://github.com/chiangyiyang/opencv4nodejs_web_cam_viewer.git

    cd opencv4nodejs_web_cam_viewer
    set OPENCV4NODEJS_DISABLE_AUTOBUILD=1
    chcp 65001
    npm install

    ```

5. Run server
    ```
    node index.js
    ```

6. Open URL: http://localhost:3000