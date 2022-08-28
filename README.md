# CamAsSystemApp

CamAsSystemApp -> "Camera as system app" is a simple Magisk Module which installs a camera app as system app to enable some more functionality on an FP4 (to workaround some or all issues described in: https://forum.fairphone.com/t/camera-camera2-api-missing-features-bugs/83196).

To use it:
1. download it (e.g. via Code -> "Download Zip") - you need at leas the folders and files under `CamAsSystemApp`
2. put your Camera App APK (-> the whole folder e.g. the FPCamera) under `system/priv-app`
3. rename the file `system/etc/permissions/privapp-permissions-<packag-name-camera-app>.xml` to e.g. `privapp-permissions-com.fp.camera.xml` and 
4. also put the package name within the file (line 3) `<privapp-permissions package="<package-name-camera-app>">`  
5. ZIP the whole content (note: don't zip the parent folder "CamAsSystemApp" only the files and folders within this folder)
6. Transfer the ZIP file to your FP4 and install it via Magisk Modules

