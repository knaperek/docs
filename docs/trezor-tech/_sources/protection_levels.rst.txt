 .. note:: We are currently moving the documentation to a new platform. Please visit `Trezor Wiki <https://wiki.trezor.io/Developers_guide:Protection_Levels>`_ for the latest version of this page.

Protection Levels
=================

===================== ====== === ========== ==============
Message               Button PIN Passphrase Remark
===================== ====== === ========== ==============
Initialize
Ping                  ✔      ✔   ✔          (all optional)
ChangePin             ✔      ✔
WipeDevice            ✔
FirmwareErase         ✔
FirmwareUpload        ✔
GetEntropy            ✔
GetPublicKey                 ✔   ✔
LoadDevice            ✔
ResetDevice
SignTx                ✔      ✔   ✔
SimpleSignTx          ✔      ✔   ✔
CipherKeyValue        ✔      ✔   ✔          (button only if ask_encrypt/ask_on_decrypt flag is set)
ApplySettings         ✔      ✔
GetAddress                   ✔   ✔
SignMessage           ✔      ✔   ✔
VerifyMessage
SignIdentity          ✔      ✔   ✔
RecoveryDevice
EstimateTxSize
===================== ====== === ========== ==============
