# Instrucciones

Lo primero que haremos será crear una carpeta en el disco C:, en mi caso se llamara FUSIONOCS_Agent_TFG.

En esta carpeta debes meter 2 cosas: 
1-	El agente de fusióninventory.
2-	Un bloc de notas que luego lo convertiremos en un cmd.
Una vez creada la estructura abriremos el bloc de notas y escribiremos lo siguiente:

```
@echo off
C:\FUSIONOCS_Agent_TFG/fusioninventory-agent_windows-x64_2.6.exe /S /acceptlicense /server="https://IP:puerto /plugins/fusioninventory/" /runnow /delaytime=5
```

Si quisiéramos añadir un TAG deberíamos agregarle /tag=(NOMBRE) detrás del comando de Delaytime 

*Es muy importante que escribas tu IP o nombre y el puerto correspondiente. Cuando este todo escrito guarda el archivo como .cmd
