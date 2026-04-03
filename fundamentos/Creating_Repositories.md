<div align="center">

# Comandos Git
</div>

## 1: Criando uma pasta local
```bash
  mkdir ~/example
  cd ~/example
```
## 2: Iniciando o git na pasta
```bash
git init
```
## 3: Criando o arquivo README.md
```bash
nano README.md
```
*ou*
```bash
echo "# Example" > README.md
```
## 4: Preparando os arquivos da pasta para serem commitados
```bash
git add .
```
## 5: Commitando
```bash 
git commit -m "ADD README.md"
```
## 6: Avisando o Git o repositório que assumirá "origin"
```bash 
git remote add origin https://github.com/user/nome-do-repositorio.git
```
## 7: Enviando pela primeira vez
```bash
git push -u origin main
```
*depois* 
```bash
git push
```
---
# Fim
