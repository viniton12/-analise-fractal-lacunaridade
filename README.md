🧠 Análise de Imagem para Dimensão Fractal e Lacunaridade
Este projeto em Python realiza uma análise quantitativa de imagens binarizadas para extrair métricas de dimensão fractal e lacunaridade, utilizadas em estudos de padrões espaciais e complexidade de formas — especialmente úteis em ecologia, geociências, morfologia e reconhecimento de padrões.

🔍 Funcionalidades
Carregamento e binarização de imagens em tons de cinza.

Identificação de componentes conectados.

Cálculo de métricas geométricas:

Área

Perímetro

Solidez

Dimensão fractal (via box counting adaptado com validações).

Lacunaridade (usando janelas móveis de tamanhos variáveis).

Visualização gráfica da imagem original, binarizada e componentes identificados.

🛠️ Tecnologias
Python 3

NumPy

Matplotlib

Pillow (PIL)

Scikit-image

SciPy

▶️ Como executar
Instale as dependências:

bash
Copiar
Editar
pip install -r requirements.txt
Coloque sua imagem na pasta do projeto e atualize o caminho no final do main.py.

Execute o script:

bash
Copiar
Editar
python main.py
📸 Exemplo de uso
Com uma imagem binária ou convertida para escala de cinza, o script identifica os componentes e gera um resumo estatístico de até 5 regiões significativas, com gráficos exibindo o processamento.

📚 Aplicações
Este tipo de análise é especialmente útil para:

Análise de paisagens e fragmentação ecológica

Estudo da distribuição espacial de organismos

Detecção de padrões morfológicos em imagens científicas

Pesquisas envolvendo morfometria e modelagem da complexidade estrutural



