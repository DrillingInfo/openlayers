Releasing OpenLayers for DrillingInfo
=====================================

To get more information on build options:  

```
python build.py --help
```

To release the DI build, minimized, in an AMD module:  

1. Create the build  

    ```
    python build.py -c closure_ws --amd=post di ../dist/OpenLayers.js
    ```

2. Check the new build with our application  

3. Commit the changes  

4. Tag OpenLayers with the next DI tag, i.e.:  

    ```
    git tag -s v2.13.1-di{#} -m "Released-by: John Doe <john.doe@drillinginfo.com>"
    ```
