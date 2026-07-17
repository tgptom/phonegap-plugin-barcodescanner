The embedded Android AAR is built from
[tgptom/barcodescanner-lib-aar](https://github.com/tgptom/barcodescanner-lib-aar).
It contains ZXing BS-4.7.6 sources, reports library version 3.5.2, and requires
compileSdk 36. When replacing the AAR, keep the explicit AndroidX dependencies
in `barcodescanner.gradle` synchronized with the library module dependencies.
