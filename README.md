# SearchDK
use o método de raspagem para pesquisa no google
se você deseja obter uma redundância melhor, use.

## Requisitos

Instalar Webpage2html

```bash
git clone https://github.com/zTrix/webpage2html.git
cd Webpage2html
pip install -r requisitos.txt

#Test webpage2html
python webpage2html.py https://www.google.com > google.html
```

Requisitos de instalação
```bash
cd ..
pip install -r requisitos.txt
```
## Diagrama de fluxo
1.compilação de pesquisa do google
```bash
python3 dork4me.py (--help/-h)
python3 dork4me.py (modo 2 - onliner / no aplicativo)
```
2.exportar links para arquivo csv

salvar arquivo em links.txt

3.set tor service para pesquisa

em dork4me.py =>alterar proxy

4. salve todos os links em html
```bash
bash save.sh
```
Isso é apenas a fim de estudo.
