# Smart Traffic Vehicle Counter 🚦🚗

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![OpenCV](https://img.shields.io/badge/OpenCV-4.5%2B-orange)](https://opencv.org/)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

Um sistema inteligente de contagem de veículos com análise de semáforo, detectando infrações e evitando contagens duplicadas usando visão computacional.

## Recursos Principais
- **Contagem de veículos** baseada em uma linha virtual.
- **Análise do estado do semáforo** (vermelho, amarelo, verde) via espaço de cor HSV.
- **Rastreamento contínuo** de veículos usando YOLO e ByteTrack.
- **Detecção de infrações** quando veículos cruzam a linha durante o sinal vermelho.
- **Evita duplicações** com IDs únicos para cada veículo.

## Instalação
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/Smart-Traffic-Vehicle-Counter.git
   cd Smart-Traffic-Vehicle-Counter
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

3. Baixe o modelo pré-treinado YOLO (ex: `volo11s.pt`) e coloque-o na pasta `models/`.

## Uso
1. Execute o notebook Jupyter:
   ```bash
   jupyter notebook notebooks/Smart_Traffic_Analysis.ipynb
   ```

**Parâmetros:**
- `video`: Caminho do vídeo de entrada.
- `model`: Caminho do modelo YOLO.
- `line_y`: Posição Y da linha virtual de contagem (padrão: 600).



## Licença
Distribuído sob a licença MIT. Veja [LICENSE](LICENSE) para mais detalhes.

## Créditos
- Modelo YOLO: [Ultralytics](https://github.com/ultralytics/yolov5)
- Rastreamento: [ByteTrack](https://github.com/ifzhang/ByteTrack)
