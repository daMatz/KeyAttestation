Android Key Attestation Test App
==============================

This app supports generating, saving, loading, parsing and verifying Android [key and ID attestation](https://source.android.com/docs/security/features/keystore/attestation) data.

The app is used for self-testing, so it has no network permission. The certificate revocation data is embedded in the apk and will not be updated online. If the system is compromised, parsing and verifying is not safe, you should save the data to a file and then load the file on another device to verify it.

This app also supports loading attestation data generated by other software, and the supported storage format is [PkiPath and PKCS7](https://docs.oracle.com/en/java/javase/17/docs/specs/security/standard-names.html#certpath-encodings).

License
-------

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
