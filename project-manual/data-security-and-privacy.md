# Data privacy & security

## Types of data

### Personal data \(GDPR\)

personal data \(de: personenbezogene Daten\):

> ‘personal data’ means any information relating to an identified or identifiable natural person \(‘data subject’\); an identifiable natural person is one who can be identified, directly or indirectly, in particular by reference to an identifier such as a name, an identification number, location data, an online identifier or to one or more factors specific to the physical, physiological, genetic, mental, economic, cultural or social identity of that natural person; \([Source](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32016R0679&from=DE#d1e1489-1-1)\)

Personal data can be pseudonymized or anonymized.

#### Pseudonymization

> ‘pseudonymisation’ means the processing of personal data in such a manner that the personal data can no longer be attributed to a specific data subject without the use of additional information, provided that such additional information is kept separately and is subject to technical and organisational measures to ensure that the personal data are not attributed to an identified or identifiable natural person; \([Source](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32016R0679#d1e1489-1-1)\)

{% hint style="warning" %}
Pseudonymized data are still subject to the GDPR regulation.
{% endhint %}

#### Anonymization

Only if personal data are properly anonymized, they do not fall within the scope of the GDPR. However, requirements for anonymization are high:

{% hint style="warning" %}
**High standards for anonymization**

> Personal data that has been de-identified, encrypted or pseudonymised but can be used to re-identify a person remains personal data and falls within the scope of the GDPR. [Source](https://ec.europa.eu/info/law/law-topic/data-protection/reform/what-personal-data_en)

and

> Personal data that has been rendered anonymous in such a way that the individual is not or no longer identifiable is no longer considered personal data. For data to be truly anonymised, the anonymisation must be irreversible. [Source](https://ec.europa.eu/info/law/law-topic/data-protection/reform/what-personal-data_en)
{% endhint %}

Overall, it is very hard to properly anonymize data. Most of the times that people speak of "anonymized" data they are still pseudonymized data in the sense of GDPR and hence are still subject to the regulation.

### Non-personal data

{% hint style="info" %}
Non-personal data do not fall into the scope of GDPR.
{% endhint %}

**non-personal data** \(de: nicht-personenbezogene Daten\): for example, data on organization processes, data on institutions etc.

**open data \(de: offene Daten\):**

> Open data is data that can be freely used, re-used and redistributed by anyone - subject only, at most, to the requirement to attribute and sharealike. \([https://opendatahandbook.org/guide/en/what-is-open-data/](https://opendatahandbook.org/guide/en/what-is-open-data/)\)

## Declaration on data security

German: Datenschutzverpflichtungserklärung

Depending on the project, a declaration on data security needs to be signed by all members of the project team and the NPO.

You can download it [here](https://correlcloud.org/index.php/s/7PSskX9yN7RKmoi?path=%2Ftemplate_data_privacy). It should be adapted according to the specific requirements of the project that should've been defined in the [ideation process](project-coordinators/ideation-finding-a-team.md#data-privacy-and-data-access). The project lead is responsible for collecting the signed declarations from all project team members before any data is shared as part of the [onboarding process](project-coordinators/onboarding.md#data-privacy-policy-statement).

## Data encryption

Depending on the project, the project lead and the project team need to ensure that the data is stored encrypted on their local machines.

There are two ways to achive this goal: by encrypting the user's home folder or by using VeraCrypt.

### VeraCrypt

VeraCrypt is an encryption program and the successor of TrueCrypt. With the help of VeraCrypt, encrypted containers can be created. To decrypt \( called “to mount” \) the container, a password is needed. The encrypted \(“mounted”\) VeraCrypt container will then appear as a new drive on the computer. All data stored on this drive is automatically encrypted. Programs can still access this data, because they are encrypted in memory. The storage space of this virtual drive is determined by the size of the container. Once created, the size of the container can no longer be adjusted. The project lead must therefore estimate the amount of data that will be stored when creating the container.

### Encrypted home directory

The project data must always be encrypted so that they cannot be read by unauthorized third parties if the data medium is lost. One way to ensure this is an encrypted home directory. The data is then decrypted or encrypted automatically when the user logs in or out. Whether the encryption of the home directory is possible depends on the operating system the project team member uses.

**Windows**: An encryption of the home directory is only possible in Windows Pro and Enterprise. Windows users must fall back therefore usually to the solution with VeraCrypt \(previous section\).

**Mac**: On Mac OS, starting with Mac-OS X 10.4, FileVault can be used to encrypt the home directory and also the entire hard disk. Caution with the latter. If you forget or lose both your user password and the recovery password, your data is irretrievably lost \(encrypted\). Instructions for FileVault can be found [here](https://support.apple.com/en-us/HT204837). **Important**: If you are using TimeShift to make backups, the folder you created for CorrelAid should be excluded from the backup or encrypted.

**Linux**: In the newer versions of the most common distributions you should be able to select encryption as an additional option when creating a new user account. In most cases the software ecryptfs-utils is used for encryption. If you missed to do this for your user account, you should fall back to the VeraCrypt option.

