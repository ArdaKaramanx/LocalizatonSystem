# LocalizatonSystem.dll

bu dosya sayesinde basit bir şekilde c# ile her hangi bir projenizde kullana bilirsiniz.

# Kullanımı

Öncelikle dosya dizini şöyle olacak {ApplicationPath}/loc/tr.csv

   ```csharp
   List<LocalValue> lanvalue = new List<LocalValue>();
   lanvalue = (List<LocalValue>)LocalSystem.ReadCSVFile(Application.StartupPath, "en", "", Encoding.Default);

   List<LocalInfoValue> Infovalue = new List<LocalInfoValue>();
   Infovalue = (List<LocalInfoValue>)LocalSystem.ReadInfoCsvFile(Application.StartupPath, "en", "", Encoding.Default);
```
helo
