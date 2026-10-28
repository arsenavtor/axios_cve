# Создание базы данных

1. Перейти в папку с сервисом:
    cd .\axios_cve\cve\services\<категория>\<cve>
    категория = [dos, proto, ssrf]
    
2. Создание базы данных в папку database - там лежат все представления кода codeql для написания к ним правил
    codeql database create .\axios_cve\database\<cve>-db --language=javascript --source-root=.