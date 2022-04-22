# mx-shufti-connector
Integration with [ShuftiPro](https://shuftipro.com/) : Real-time Identity Verification KYC, AML and KYB with AI
For now only KYC "DocumentService" is implemented.

## Usage
1. Import the module
2. Create a page where the user can configure ShuftiConfig : ClientID / SecretID (API key equivalent), or setup the values in a microflow if you prefer
3. Create a request with ``DS_NewRequest``, and set the configuration you want
4. Call microflow ``REST_KYC_DocumentService``

## Documentation
The complete API doc is (here)[https://api.shuftipro.com/api/docs].

## Version
Mendix 9

## Feedback, PR & bugs
Please submit your bugs / PR (here)[https://github.com/lordlothar99/mx-shufti-connector], and contact me at "francois at kohomai.com"
