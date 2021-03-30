![image](https://user-images.githubusercontent.com/72662997/112924045-cca1d300-90e5-11eb-8637-9d19d39da52f.png)


## Gitpod RNAseq STAR pipeline - chr22 simulado

* Pré-requisito instalar o R

```bash
brew install r
```

## Download dos Apss (STAR e RSEM)
STAR e RSEM para alinhamento e contagem de reads.

> Execudando o script `run.down.apps.sh`
```bash
sh run.down.apps.sh 
```
## Indexar a referência do `chr22`

> Executando script makeRef.sh
```bash
cd reference
sh makeRef.sh
cd ..
```

## Executar o STAR e RSEM

> Executando script run.star.rsem.sh
```bash
sh run.star.rsem.sh
```
