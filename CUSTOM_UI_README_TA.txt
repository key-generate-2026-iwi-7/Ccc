AdAway Custom UI package
========================

இந்த மாற்றத்தில் UI resource files மட்டும் மாற்றப்பட்டுள்ளன:
- values/colors.xml மற்றும் values-night/colors.xml: புதிய teal theme
- values/styles.xml மற்றும் values-night/styles.xml: status/navigation bar styling
- home_content.xml: dashboard header மற்றும் cards styling
- drawable/custom_dashboard_header.xml: gradient header
- பிற CardView layouts: rounded card corners

Original Java source, VPN implementation, filtering engine, database, manifest,
native modules, Gradle files மற்றும் project identifiers மாற்றப்படவில்லை.

AIDE Pro compatibility:
இந்த ZIP அசல் AdAway Gradle project-ஐ அப்படியே வைத்திருக்கிறது. Project-ல்
Java 17, compileSdk 34, Android Gradle Plugin 9.5.1 (version catalog-ல்),
View Binding, AndroidX/Material dependencies மற்றும் tcpdump/webserver native
modules உள்ளன. எனவே எல்லா AIDE Pro பதிப்புகளும் இதை build செய்யும் என்று
உறுதி அளிக்க முடியாது. முதலில் Android Studio/Gradle-ல் build செய்து
பின்னர் உங்கள் AIDE Pro version-ல் சோதிக்கவும்.

GPL-3.0+:
இது AdAway-ஐ அடிப்படையாகக் கொண்ட மாற்றிய UI resource package. விநியோகிக்கும்
போது அசல் LICENSE.md, copyright notices மற்றும் GPL-3.0+ நிபந்தனைகளை
பாதுகாக்கவும்; மாற்றிய பதிப்பு என்பதை தெளிவாகக் குறிப்பிடவும்.
