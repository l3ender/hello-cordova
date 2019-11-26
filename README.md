## Steps to reproduce

After cloning repo...

1. Install npm dependencies:
    ```bash
    npm install
    ```
2. Ensure no platforms or plugins have been added yet:
    ```bash
    rm -rf platforms/ plugins/
    ```
3. Try and add iOS platform:
    ```bash
    cordova platform add ios --verbose
    ```

This will result in an error:
```
ENOENT: no such file or directory, open '/Users/your-user/repos/hello-cordova/platforms/ios/CordovaLib/CordovaLib.xcodeproj/project.pbxproj'
```
