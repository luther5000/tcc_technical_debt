# Dívida Técnica em Documentação de Software: Um Estudo de Caso no SFM

Este repositório contém os arquivos fontes em LaTeX e os artefatos da minha monografia de Trabalho de Conclusão de Curso (TCC) em Ciência da Computação pela Universidade Federal da Paraíba (UFPB), defendida com sucesso em abril de 2026.

O trabalho investiga os impactos e a presença de Dívida Técnica (Technical Debt) na documentação de software, utilizando como objeto de estudo prático o Sistema de Fomento ao Microempreendedor (SFM).

## Resumo
A dívida técnica de documentação ocorre quando a documentação de um sistema é negligenciada, desatualizada ou inadequada, impactando diretamente a manutenibilidade e a evolução do software. Este trabalho apresenta uma análise detalhada desse fenômeno dentro do ecossistema do SFM, identificando gargalos, medindo impactos e propondo melhorias com base em boas práticas de engenharia de software.

* **Orientadora:** Profa. Dra. Yuska Aguiar

---

## Estrutura do Repositório

* `/src` Arquivos fonte em LaTeX (`.tex`, `.bib`, imagens, etc.).
* `/slides`: Apresentação utilizada na defesa (em LaTeX Beamer).
* `tcc_final.pdf` : Versão final da monografia compilada para leitura direta.
* `tcc_slides.pdf`: Versão final dos slides compilada para visualização.
---

## Como Compilar Localmente

Caso queira clonar o repositório e compilar o documento PDF na sua máquina, você precisará de uma distribuição LaTeX instalada (como o TeX Live).

### Pré-requisitos (Exemplo no Ubuntu/Kubuntu)
```bash
sudo apt update
sudo apt install texlive-full latexmk
