# Polygon ID�ɂ��VC�̔��s
VC�̔��s�ɗ��p����Polygon ID�̍\�z�Ɨ��p���@�ɂ��ċL�ڂ���B

����̃f���ł́APolygon ID�̈ȉ��c�[���𗘗p����B
* VC�̔��s�FPolygon ID��[issuer-node](https://github.com/0xPolygonID/issuer-node/tree/v.2.1.0)��v.2.1.0
* VC�̒񎦁FPolygon ID Wallet App ([Google Play](https://play.google.com/store/apps/details?id=com.polygonid.wallet), [App Store](https://apps.apple.com/us/app/polygon-id/id1629870183))


## Issuer-node�̍\�z
Issuer-node�̍\�z���@�́A[Polygon ID Documentation tutorials](https://0xpolygonid.github.io/tutorials/)����[Setup Guide(Core API)](https://0xpolygonid.github.io/tutorials/issuer/setup-issuer-core/)��[Setup Guide(API UI)](https://0xpolygonid.github.io/tutorials/issuer/setup-issuer-ui/)�ɋL�ڂ̒ʂ�ł���B

�Ȃ��APolygon ID Wallet App�ɂ��VC�̒񎦂����{���邽�߁AUI API�T�[�o�ilocalhost:3002�j�Ƀp�u���b�NURL��t�^����K�v������B�p�u���b�NURL��t�^�ɂ́A[ngrok](https://ngrok.com/)�𗘗p����B

�p�u���b�NURL�t�^���@�͉��L�̒ʂ�ł���B

1. `.env-api`�t�@�C���̕ҏW

    `.env-api`���ȉ��̂悤�ɕҏW����B
    ```
    # ...
    ISSUER_API_UI_SERVER_URL=<ngrok�Ŏ擾����public URL>
    ```

2. ngrok�ɂ��forwarding service�N��

    �N���R�}���h�͈ȉ��̒ʂ�ł���B
    ```
    ./ngrok http --domain <ngrok�Ŏ擾����public URL> 3002; 
    ```

## Issuer-node�ɂ��VC�̔��s

### �J�X�^��schema�̍쐬
����̃f���ł́A�J�X�^��schema���쐬���g�p����B
�J�X�^��schema�̍쐬�ɂ�[Schema builder](https://schema-builder.polygonid.me/)�𗘗p�����B
�쐬����Schema�́A[schema](https://github.com/TeamACombinato/PolygonID/tree/main/schemas)�t�H���_�Ɋi�[���Ă���B

### VC�̔��s

VC�̔��s���@�́A[Polygon ID Documentation tutorials](https://0xpolygonid.github.io/tutorials/)����[Issuer Node UI Guide](https://0xpolygonid.github.io/tutorials/issuer-node/issuer-node-guide/)�ɋL�ڂ̒ʂ�ł���A�uDirect Issuance�v�̕��@��VC���s���s���B

### Polygon ID Wallet App��VC�̕ۑ�

Issuer Node UI�́uCredentials�v�́uDetails�v���Credential���s�p��2�����R�[�h��\������B

![Credentials](docs/img/Credentials.png)
![Credentials-details](docs/img/Credentials-details.png)
![2Dcode](docs/img/Credentials-2Dcode.png)


Polygon ID Wallet App���N�����A2�����R�[�h��ǂݍ��ނ��ƂŔ��s����VC���A�v�����ɕۑ������B

![scan-2d](docs/img/scan-2d.png)
