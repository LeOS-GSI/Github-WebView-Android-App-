Sources for creating a WebApp.
clone this repo
run follwing changes:
1. rename all 'LEOS' folders to name of new WebApp
2. run in terminal: 'grep -RiIl 'com.harvey186.LEOS' | xargs sed -i 's/com.harvey186.LEOS/com.harvey186.NameOfWebApp/g'
3. changes in AndroidManifest.xml
    - change icon (drawable/ic_launcher_foreground)
    - change WebApp Name in 'lable'

4. changes in MainActivity.kt
    - change url in 'webUrl'

that's it
