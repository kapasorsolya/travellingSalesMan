# travellingSalesMan

## Feladat
 Utazóügynök feladat megoldása evolúciós módszerrel. Bármilyen külső evolúciós framework használható.
 
 A városok listája alapján az utazóügynöknek meg kell határoznia a leghatékonyabb útvonalat, amely során egyszer és csakis egyszer látogat minden várost. Bármely város lehet a kiindulópont.
 
## Leírás
  ### Framework:
  - a feladat: C#  programozási nyelvben lett megvalósítva
  - a .NET  keretrendszerben található (GAF) genetikus algoritmus csomagot használtam
  
  ## Nuget package telepítése:
    PM> Install-Package GAF
    
## Bemenet:
  16 város és a koordinátái
  
## Leállási feltétel:
  - 400 generáció létrejötte után
  
## Kimenet:
  A városok listája a meglátogatási sorrendben.
  
