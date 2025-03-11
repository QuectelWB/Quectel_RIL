# Quectel_RIL


This is for

- Android version <= 9

- Android version > 9 but insist on using the IRadio 1.0/1.1


        <hal format="hidl">
        <name>android.hardware.radio</name>
            <transport>hwbinder</transport>
            <version>1.0</version>
            <interface>
                <name>IRadio</name>
                <instance>slot1</instance>
            </interface>
        </hal>


# File Lists

        ├── libgps
        │   ├── arm64-v8a
        │   │   └── gps.default.so
        │   ├── armeabi-v7a
        │   │   └── gps.default.so
        │   └── gps_cfg.inf
        ├── libquectel-ril
        │   ├── arm64-v8a
        │   │   ├── chat
        │   │   ├── ip-down
        │   │   ├── ip-up
        │   │   └── libreference-ril.so
        │   ├── armeabi-v7a
        │   │   ├── chat
        │   │   ├── ip-down
        │   │   ├── ip-up
        │   │   └── libreference-ril.so
        │   └── ql-ril.conf
        └── README.md


