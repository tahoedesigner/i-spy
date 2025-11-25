# 🕵️ I-Spy - Illustrator Object Inspector

## Architecture
```
I-Spy
    ├── CSXS/
    │   └── manifest.xml
    ├── client/
    │   ├── index.html
    │   └── CSInterface.js
    │   └── main.js
    │   └── styles.css
    └── host/
        └── index.jsx
```

# Install Extension
Copy the entire I-Spy folder to:

#### Mac: /Library/Application Support/Adobe/CEP/extensions/ 
#### Windows: C:\Program Files\Common Files\Adobe\CEP\extensions\

## Enable CEP Debugging
#### Mac:
```
defaults write com.adobe.CSXS.11 PlayerDebugMode 1
```

#### Windows:

- Run regedit as administrator
- Navigate to: HKEY_CURRENT_USER\Software\Adobe\CSXS.11
- Create DWORD: PlayerDebugMode = 1



