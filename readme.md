# Gradle sourceSets POC

Prova de conceito de sourceSets gradle.

Objetivo: Compilar e gerar pacotes utilizando conjuntos de arquivos diferentes, compartilhando dependências de um conjunto de arquivos principal.

```shell
./gradlew clean jarSetA jarSetB
```

Os jars são gerados no diretório `build/libs`.
