# config:export:view
The **config:export:view** command एक व्यू को YAML संरूप में एक्सपोर्ट करें ताकि वो किसी दूसरे वेबसाइट में पुनर्प्रयोग किया जाये।

**प्रयोग:**
```
$ drupal config:export:view [arguments] [options] 
$ cev  
```

## उपलब्ध विकल्प
विकल्प | विवरण
-------|-------------
--module | मोड्यूल का नाम।
--optional-config | व्यू को ऐच्छिक YAML कॉन्फिग स्वरूप अपने मॉड्यूल में निर्यात करें
--include-module-dependencies | व्यू मॉड्यूल निर्भरता को मॉड्यूल info YAML फाइल में सम्मिलित करें

## उपलब्ध तर्कों  
तर्क | विवरण
---------|-------------
view-id | व्यू आईडी
