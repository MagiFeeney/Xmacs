### How to use
Download the file into
```
$ cp Downloads/xmacs /usr/share/X11/xkb/symbols/
```
Add following configure
```
    <layout>
      <configItem>
        <name>xmacs</name>
        <description>Xmacs</description>
        <languageList>
          <iso639Id>eng</iso639Id>
        </languageList>
      </configItem>
      <variantList/>
    </layout>
```
to
```
/usr/share/X11/xkb/rules/evdev.xml
```
under ```<layoutList>```

Navigate to ```Settings -> KeyBoard -> Input Sources``` to find the Xmacs!