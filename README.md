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
