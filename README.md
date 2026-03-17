# Vulnerabilidade Econômica do Rio Grande do Sul

**Dashboard interativo para análise de vulnerabilidade socioeconômica e exposição a desastres hidrológicos nos municípios de Eldordo do Sul, Porto Alegre e Rio Grande.**

------------------------------------------------------------------------

## Objetivo

Este projeto tem como objetivo reunir, visualizar e explorar dados georreferenciados relacionados a empresas, infraestrutura urbana, saúde, segurança, educação, terrenos, quadras e edificações em Rio Grande, facilitando análises de vulnerabilidade econômica, impactos potenciais e a identificação de áreas mais expostas a eventos extremos e desastres hidrológicos.

------------------------------------------------------------------------

## Principais Funcionalidades

-   **Visualização Geográfica:** Mapa interativo (folium/Streamlit) que permite explorar camadas de dados espaciais (shapefiles, pontos georreferenciados, clusters).
-   **Painéis Analíticos:** Indicadores de impacto em empresas, empregos, massa salarial, escolas, saúde, infraestrutura urbana e social.
-   **Filtros Dinâmicos:** Seleção de áreas/camadas afetadas, filtros personalizados para tipologias de dados (educação, saúde, segurança, etc.).
-   **Contadores de Impacto:** Resuma e compare totais e percentuais de atingidos por camada (empresas, escolas, saúde, segurança, ruas, terrenos, quadras, prédios públicos).
-   **Detalhamento Expandido:** Listagem de entidades atingidas por área e categoria, com dados detalhados acessíveis por expanders.
-   **Customização Visual:** Ícones, cores, área do mapa e disposição dos painéis ajustados para excelente experiência visual e de análise.

------------------------------------------------------------------------

## Estrutura e Dados Utilizados

-   **Empresas:** Dados de geolocalização de empresas, quantidade de empregados, massa salarial.
-   **Saúde:** Localização e tipos de estabelecimentos de saúde, Profissionais e informações específicas de impacto.
-   **Educação:** Escolas, funcionários, matrículas por segmento (infantil, fundamental, médio, técnico, Eja).
------------------------------------------------------------------------

## Tecnologias & Bibliotecas

-   **Python**
-   **Streamlit:** Interface web interativa.
-   **Folium:** Visualização e manipulação de mapas interativos.
-   **Geopandas, Pandas:** Manipulação de dados geoespaciais e tabulares.
-   **Git Large File Storage (LFS):** Gerenciamento de arquivos grandes (.dbf, shapefiles).

------------------------------------------------------------------------

## Como executar

1.  Instale as dependências listadas em `requirements.txt`:

``` bash
pip install -r requirements.txt
```

2.  Execute o dashboard pela linha de comando:

``` bash
streamlit run Dashboard.py
```

3.  Os dados devem ser organizados conforme os diretórios do projeto (`Dados/`, `.icons/`, etc.), conforme aparecem no código.\
4.  Ou acesse a versão online pelo link: <https://vedh-rgs.streamlit.app/>

------------------------------------------------------------------------

## Estrutura dos diretórios

```         
.
├── Dados/
│   ├── *.dbf, *.shp, *.xlsx, *.qmd, ...   # Dados espaciais, tabulares, infraestrutura
├── .icons/
│   ├── *.png, *.datauri                  # Ícones customizados para visualização
├── Dashboard.py                          # Dashboard principal
└── requirements.txt                      # Dependências Python do projeto
```

------------------------------------------------------------------------

## Licença

Este projeto segue as licenças e direitos conforme definidos pela instituição de pesquisa e autores. Para usos acadêmicos, cite conforme normas ABNT.

------------------------------------------------------------------------

## Autores

**Alisson Tallys Geraldo Fiorentin**\
*Doutorando em Economia Aplicada*\
*Universidade Federal do Rio Grande do Sul - UFRGS*\
Contato: [alisson.fiorentin\@gmail.com](mailto:alisson.fiorentin@gmail.com)
